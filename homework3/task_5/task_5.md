1. *Клиенты из Германии:*  
SELECT * FROM Customers WHERE Country='Germany';    
**Ответ на запрос: 13**
 
2. *Имена, заканчивающиеся на 'e':*  
SELECT * FROM Customers WHERE CustomerName LIKE '%e';   
**Количество записей: 15**  

3. *Вставить имя в таблицу:*  
INSERT INTO Customers (CustomerName) VALUES ('Lilya Velikzhanina');   
![insert name](/homework3/insert_name.png)

4. *Изменить имя:*  
UPDATE Customers SET CustomerName='Lilya Velik' WHERE CustomerName='Lilya Velikzhanina';   
![update name](/homework3/update_name.png)

5. *Удалить клиентов из города Nantes:*  
DELETE FROM Customers WHERE City='Nantes';   
**Результат:** You have made changes to the database. Rows affected: 2

6. *Номера заказов клиентов, сделанных работником Steven:* SELECT OrderID FROM Orders INNER JOIN Employees ON Orders.EmployeeID=Employees.EmployeeId WHERE FirstName='Steven';    
**Номера заказов:**   
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
