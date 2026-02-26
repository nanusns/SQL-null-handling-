# SQL-null-handling-
CREATE TABLE customers (
    customer_id SERIAL PRIMARY KEY,
    name VARCHAR(50),
    shipping_address VARCHAR(100),
    billing_address VARCHAR(100)
);

INSERT INTO customers (name, shipping_address, billing_address)
VALUES
('Rahul', 'Delhi', 'Delhi'),
('Amit', NULL, 'Mumbai'),
('Priya', 'Bhopal', NULL),
('Neha', NULL, NULL),
('Ravi', 'Indore', 'Indore');
