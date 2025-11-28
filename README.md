# 04-sql-queries-consultas-basicas.sql

SELECT * FROM customers;

SELECT name, price FROM products WHERE price > 1000;

SELECT COUNT(*) AS total_orders FROM orders;
