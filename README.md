# SQL-operation
Learning SQL
Selec Clasue:
USE sql_store;-- each step needs semicolom to terminate queries
SELECT * -- select clause
FROM customers -- select from dataset
WHERE customer_id = 1 -- filter and sort data
ORDER BY first_name -- ordering data, right order matters

SELECT 
	last_name, 
    first_name, 
    points,
    (points + 10) * 100 AS discount_factor
FROM sql_store.customers
