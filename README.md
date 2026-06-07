# mysql-assignment-queries

"SQL queries and screenshots for Data Analytics Module‑3 Assignment 2, covering clauses, operators, sorting, grouping, aggregate functions, and joins in MySQL."

MySQL-Assignment-2/
│
├── README.md
├── Queries/
│   ├── distinct_values.sql
│   ├── alias.sql
│   ├── where_clause.sql
│   ├── order_by.sql
│   ├── limit.sql
│   ├── aggregate_functions.sql
│   ├── group_by.sql
│   ├── having.sql
│   ├── inner_join.sql
│   ├── left_join.sql
│   ├── right_join.sql
│   ├── cross_join.sql
│   └── self_join.sql
│
└── Screenshots/
    <img width="1401" height="792" alt="S" src="https://github.com/user-attachments/assets/2c12741b-8563-4f0d-913b-dc31672c34b3" />

    <img width="1600" height="849" alt="2" src="https://github.com/user-attachments/assets/f7390b7c-8a45-4bda-bf17-826a55de7419" />
    <img width="1600" height="857" alt="3" src="https://github.com/user-attachments/assets/67ef61ff-1335-4ce1-a4e1-b518edc206c9" />
    <img width="1598" height="852" alt="4" src="https://github.com/user-attachments/assets/65a7162b-0e96-49aa-ac77-58eed314403d" />
    <img width="1596" height="841" alt="5" src="https://github.com/user-attachments/assets/1f79e62e-c48b-42b6-8b2c-6f8fa559d48b" />
    <img width="1598" height="754" alt="6" src="https://github.com/user-attachments/assets/df4ad0ee-73d0-43b1-b72f-29c1f90ba495" />
    <img width="1595" height="752" alt="7" src="https://github.com/user-attachments/assets/d487907e-9dc7-429c-bf5b-2b53906f7c14" />
    <img width="1559" height="661" alt="8" src="https://github.com/user-attachments/assets/81815d6c-4c13-4851-9336-9670fcf4cd9e" />
    <img width="1591" height="701" alt="9" src="https://github.com/user-attachments/assets/714776ef-5c7b-4b92-87eb-c7b44eb3cad6" />
    <img width="1580" height="708" alt="11" src="https://github.com/user-attachments/assets/6ffd2667-5410-4727-9d24-038f5bbc081b" />
    INNER JOIN
    <img width="1600" height="741" alt="12" src="https://github.com/user-attachments/assets/ffb76adb-4514-4878-a88e-30896a8ebddc" />
    RIGHT JOIN
    <img width="1596" height="734" alt="u" src="https://github.com/user-attachments/assets/b090f54d-cb33-4567-a8cd-8f5bd25a6b05" />
    LEFT JOIN
    <img width="1600" height="681" alt="l" src="https://github.com/user-attachments/assets/4a784709-0d5d-405f-8928-569bdcae589f" />
    CROSS JOIN
    <img width="1598" height="685" alt="c" src="https://github.com/user-attachments/assets/e54dd443-e7d7-45c9-8d65-e77c8132e521" />
    SELF JOIN
    <img width="1600" height="657" alt="self" src="https://github.com/user-attachments/assets/9ec80855-155d-477d-97bf-899b3a319637" />

    
    WINDOW FUNCTIONS
    The WINDOW function is a type of analytic function used in SQL (and also in DAX/Power BI with similar concepts) to perform calculations across a set of rows that are related to the current row, without collapsing them into a single output like aggregate functions do.

✨ Key Points about WINDOW Functions
Operate over a "window" of rows: Instead of calculating over the entire dataset, they work on a subset defined by PARTITION BY and ORDER BY.

Do not reduce row count: Each row still appears in the result, but with additional computed values.

Common examples:

ROW_NUMBER() → assigns sequential numbers to rows.

RANK() / DENSE_RANK() → assigns ranking based on ordering.

LEAD() / LAG() → access values from subsequent or previous rows.

SUM() OVER(...), AVG() OVER(...) → running totals or moving averages.

RANK()
<img width="1600" height="678" alt="rank" src="https://github.com/user-attachments/assets/e2e55ba1-1728-4e38-8b67-bdbc5c7c68b2" />

DENSE_RANK()
<img width="1600" height="729" alt="dense" src="https://github.com/user-attachments/assets/b79b0e35-b761-475b-b4da-2e831fd50b51" />
RUNNING TOTAL
<img width="1600" height="760" alt="running" src="https://github.com/user-attachments/assets/2c2acb71-e7d7-4e0f-9f51-e77bc8100d49" />












    


