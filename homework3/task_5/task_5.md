1. *������� �� ��������:*  
SELECT * FROM Customers WHERE Country='Germany';    
**����� �� ������: 13**
 
2. *�����, ��������������� �� 'e':*  
SELECT * FROM Customers WHERE CustomerName LIKE '%e';   
**���������� �������: 15**  

3. *�������� ��� � �������:*  
INSERT INTO Customers (CustomerName) VALUES ('Lilya Velikzhanina');   
![insert name](/homework3/insert_name.png)

4. *�������� ���:*  
UPDATE Customers SET CustomerName='Lilya Velik' WHERE CustomerName='Lilya Velikzhanina';   
![update name](/homework3/update_name.png)

5. *������� �������� �� ������ Nantes:*  
DELETE FROM Customers WHERE City='Nantes';   
**���������:** You have made changes to the database. Rows affected: 2

6. *������ ������� ��������, ��������� ���������� Steven:* SELECT OrderID FROM Orders INNER JOIN Employees ON Orders.EmployeeID=Employees.EmployeeId WHERE FirstName='Steven';    
**������ �������:**   
10248  
10254  
10269  
10297  
10320  
10333  
10358  
10359  
10372  
10378  
10397  
