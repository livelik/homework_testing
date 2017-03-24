1. *Клиенты из Германии:*  
SELECT * FROM Customers WHERE Country='Germany';    
**Îòâåò íà çàïðîñ: 13**
 
2. *Имена, заканчивающиеся на 'e':*  
SELECT * FROM Customers WHERE CustomerName LIKE '%e';   
**Êîëè÷åñòâî çàïèñåé: 15**  

3. *Âñòàâèòü èìÿ â òàáëèöó:*  
INSERT INTO Customers (CustomerName) VALUES ('Lilya Velikzhanina');   
![insert name](/homework3/task_4/insert_name.png)

4. *Èçìåíèòü èìÿ:*  
UPDATE Customers SET CustomerName='Lilya Velik' WHERE CustomerName='Lilya Velikzhanina';   
![update name](/homework3/task_4/update_name.png)

5. *Óäàëèòü êëèåíòîâ èç ãîðîäà Nantes:*  
DELETE FROM Customers WHERE City='Nantes';   
**Ðåçóëüòàò:** You have made changes to the database. Rows affected: 2

6. *Íîìåðà çàêàçîâ êëèåíòîâ, ñäåëàííûõ ðàáîòíèêîì Steven:* SELECT OrderID FROM Orders INNER JOIN Employees ON Orders.EmployeeID=Employees.EmployeeId WHERE FirstName='Steven';    
**Íîìåðà çàêàçîâ:**   
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
