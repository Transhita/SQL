select c.CustomerID,c.CustomerName,p.PolicyID,p.PolicyType

from CustomersList c

cross join PolicyList p 

on c.CustomerID=p.CustomerID;



![cross ques5 output](https://github.com/user-attachments/assets/acebab87-3c79-4f19-8496-1fa0054ef268)
