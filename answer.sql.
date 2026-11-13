
-- WEEK 6 ASSIGNMENT: SQL JOINS AND RELATIONSHIPS

-- QUESTION 1: INNER JOIN - Employees and Offices

SELECT
    e.firstName,
    e.lastName,
    e.email,
    e.officeCode
FROM employees AS e
INNER JOIN offices AS o
    ON e.officeCode = o.officeCode;


-- QUESTION 2: LEFT JOIN - Products and Product Lines

SELECT
    p.productName,
    p.productVendor,
    pl.productLine
FROM products AS p
LEFT JOIN productlines AS pl
    ON p.productLine = pl.productLine;


-- QUESTION 3: RIGHT JOIN - Customers and Orders

SELECT
    o.orderDate,
    o.shippedDate,
    o.status,
    o.customerNumber
FROM customers AS c
RIGHT JOIN orders AS o
    ON c.customerNumber = o.customerNumber
ORDER BY o.orderNumber ASC
LIMIT 10;
