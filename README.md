1. Insert Data into PRODUCT Table

INSERT INTO PRODUCT (Product_Id, Product_Name, Category, Price)

VALUES ('P01', 'Samsung Galaxy S20', 'Smartphone', 3299);


INSERT INTO PRODUCT (Product_Id, Product_Name, Category, Price)

VALUES ('P02', 'ASUS Notebook', 'Laptop', 4599);


2. Insert Data into CUSTOMER Table

INSERT INTO CUSTOMER (Customer_Id, Customer_Name, Customer_Tel)

VALUES ('CO1', 'ALI', NULL);


INSERT INTO CUSTOMER (Customer_Id, Customer_Name, Customer_Tel)

VALUES ('CO2', 'ASMA', NULL);

3. Insert Data into ORDERS Table

INSERT INTO ORDERS (Customer_Id, Product_Id, OrderDate, Quantity, Total_Amount)

VALUES ('CO1', 'P02', SYSDATE, 2, 9198);


INSERT INTO ORDERS (Customer_Id, Product_Id, OrderDate, Quantity, Total_Amount)


VALUES ('CO2', 'P01', TO_DATE('28/05/2020', 'DD/MM/YYYY'), 1, 3299);
