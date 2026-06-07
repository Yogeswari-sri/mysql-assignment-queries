# mysql-assignment-queries

"SQL queries and screenshots for Data Analytics Module‑3 Assignment 2, covering clauses, operators, sorting, grouping, aggregate functions, and joins in MySQL."


Queries
distinct_values.sql
alias.sql
 where_clause.sql
order_by.sql
limit.sql
aggregate_functions.sql
group_by.sql
 having.sql
inner_join.sql
left_join.sql
right_join.sql
cross_join.sql
self_join.sql
Window Functions

Screenshots

   <img width="1401" height="792" alt="S" src="https://github.com/user-attachments/assets/fd579a8e-c9d7-4bb1-89c8-29574ac7c168" />
   <img width="1600" height="857" alt="3" src="https://github.com/user-attachments/assets/120123c0-197d-4f29-a7f8-05530ee8d084" />
<img width="1598" height="852" alt="4" src="https://github.com/user-attachments/assets/68f35fc8-930c-4727-b740-1821e251badf" />
<img width="1596" height="841" alt="5" src="https://github.com/user-attachments/assets/47a2d5a3-78f5-49ab-a451-767e26fb698b" />
<img width="1598" height="754" alt="6" src="https://github.com/user-attachments/assets/7ebeebb0-432f-4b9d-ac75-eaa94c31bb5e" />

<img width="1595" height="752" alt="7" src="https://github.com/user-attachments/assets/a14f6eac-3e25-47fb-be93-96fa2b2b201b" />
<img width="1559" height="661" alt="8" src="https://github.com/user-attachments/assets/e4dd9ab5-ee01-4f3d-a65d-e7449692ce6d" />
<img width="1591" height="701" alt="9" src="https://github.com/user-attachments/assets/9da13845-0e55-4fb7-8dac-03ae054f7a4e" />
<img width="1580" height="708" alt="11" src="https://github.com/user-attachments/assets/132839d1-213e-43cd-a46c-b49e8be0d96b" />
<img width="1580" height="708" alt="11" src="https://github.com/user-attachments/assets/0d5afba1-d5a4-4ce3-af36-420a57a1325a" />
INNER JOIN
<img width="1596" height="637" alt="13" src="https://github.com/user-attachments/assets/095c0a77-0ccd-4b7e-b5f2-ee04500c99bd" />
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












    


