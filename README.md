# IDS706-Python-SQL-YuhanXue

![format workflow](https://github.com/nogibjj/IDS706-Python-SQL-YuhanXue/actions/workflows/cicd.yml/badge.svg)

This project 5 contains Python scripts/functions that perform CRUD operations in SQLite. 

## Formatting and Erorrs
Please run `make all` to ensure all codes are well-formatted and free of errors.

## Running Scripts
To run the `main.py`, issue the following command:
```
python3 main.py
```

This script performs the following:
1. Create a table in SQLite named "diabetes".
2. Load data from "diabetes.csv" to the table "diabetes".
3. Insert an extra record.
4. Update a record based on id.
5. Delete a record based on id.


## Functions in mylib/crud.py
1. load: load a csv file to diabetes database. All row ids are created automatically by SQLite. 
2. insert: insert an individual record into diabetes table.
3. read_all_records: fetch all rows and all attributes from diabetes table.
4. read_record_id: fetch the content of one row by its id.
5. update_record: update a record given a row id and all values that this record should be updated to.
6. delete_record: delete a record given a row id.
7. close_conn: close database connection.
