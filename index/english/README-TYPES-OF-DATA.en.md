## Select your language of preference / Selecciona el lenguaje de tu preferencia

- ## [English](https://github.com/Jbarseg/Learning-Java-JDBC-and-MySQL/blob/master/index/english/README-TYPES-OF-DATA.en.md)

- ## [Español](https://github.com/Jbarseg/Learning-Java-JDBC-and-MySQL/blob/master/index/espa%C3%B1ol/README-TYPES-OF-DATA.es.md)

- ## [Comeback/Regresar](https://github.com/Jbarseg/Learning-Java-JDBC-and-MySQL)

# Table Variables Characteristics or available Types of Data:

 - **_PK (Belongs to primary key):_** A primary key in a MySQL table is a field or set of fields that uniquely identifies each row in the table. It is used to ensure the integrity of the data and to establish relationships between tables in the database. The primary key must contain a unique value for each row and cannot contain NULL values. It is specified using the PRIMARY KEY constraint when creating the table.

 - **_NN (Not Null):_** The NOT NULL constraint in MySQL is used to specify that a particular column in a table cannot contain a NULL value. This means that every row in the table must have a non-NULL value for that column. The NOT NULL constraint is often used in conjunction with the PRIMARY KEY constraint to ensure that the primary key column always has a unique, non-NULL value. It helps to ensure the integrity of the data in the table and can be specified when creating the table using the NOT NULL keyword.

 - **_UQ (Unique index):_** The UNIQUE constraint in MySQL is used to ensure that the values in a particular column (or set of columns) are unique across all rows in the table. This means that no two rows can have the same value for the specified column (or set of columns). The UNIQUE constraint is similar to the PRIMARY KEY constraint, but it allows for NULL values and does not automatically create an index for the column (or set of columns). It is often used to enforce business rules or to prevent data inconsistencies, and it can be specified when creating a table using the UNIQUE keyword.

 - **_B (Is binary column):_** In MySQL, the BINARY data type is used to store fixed-length binary strings. It is similar to the CHAR data type, but it stores binary data rather than character data. The BINARY data type is often used to store data that is not human-readable, such as cryptographic hashes or images. It is defined with a specific length, such as BINARY(60), which specifies that it can store a binary string up to 60 bytes in size. The BINARY data type is often used in conjunction with other data types, such as VARBINARY, which is a variable-length binary string data type.

 - **_UN (Unsigned data type):_** In MySQL, the UNSIGNED attribute is used to specify that an integer data type should only contain positive values. It is often used with the INT or BIGINT data types to ensure that the column only contains positive integers. The UNSIGNED attribute is specified when creating the table, and it ensures that the column does not contain negative values. It can only be used with integer data types and cannot be used with floating-point or decimal data types.

 - **_AI (Auto Incremental):_** In MySQL, the AUTO_INCREMENT attribute is used to specify that an integer column should automatically increment its value whenever a new row is inserted into the table. It is often used to create a unique identifier for each row, such as a customer ID or order number. The AUTO_INCREMENT attribute can only be used with integer data types and the column must also be marked as the primary key of the table. It is specified when creating the table using the AUTO_INCREMENT keyword. When a new row is inserted, the AUTO_INCREMENT column is automatically assigned a unique value that is one higher than the previous highest value.

 - **_G (Generated Column):_** In MySQL, a generated column is a virtual column that is not physically stored on disk and does not consume any storage space. It is derived from the values of other columns in the table and is automatically updated whenever the values of the underlying columns change. Generated columns can be either STORED or VIRTUAL. A STORED generated column is computed when the row is inserted or updated, and its value is stored on disk in the table. A VIRTUAL generated column is not stored on disk and is computed on-the-fly whenever it is queried. Generated columns can be useful for storing computed values that are frequently used in queries, as they can improve query performance by avoiding the need to recalculate the values each time they are needed. They are specified when creating the table using the AS keyword.

 **_This information was provided by an AI language model trained by OpenAI._**