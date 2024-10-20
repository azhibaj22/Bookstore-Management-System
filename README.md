The focus of this software manages all important aspects of a Library. It contains data about all  the books in the library, such as ISBN of the book, title, category of the book, supplier, purchased date, purchased price, original price, selling price, author, stock. At the same time, keeps track of the sold products by bill number (or Order Id), their sold quantities, prices, and date of transaction. 
The application will have a three-level user system: Librarian, Manager and Administrator. Each has different  views and usage of the software. Note that each of the users has a username and a password to enter in the software  (obviously a role as well). 

Librarian -> Has the right to check out books that a customer may need from the bookstore. The software provides the total amount  of the bill in printable format. 

Manager -> The manager has the right to supply the bookstore with the needed books. They may also check the performance of the librarians by checking their total number of bills, books sold, and the total amount of money made for a certain date or between a certain period of time. Also, the statistics about the books sold and bought should be provided to them whenever requested with daily, monthly and/or total filters. 

Administrator -> The administrator has the right to manage almost everything that Librarian and Manager does. Beside the above permissions, the admin has the right to manage the employees (Librarian and Manager), by registering, modifying, and deleting them. The software provides to the admin data about total incomes (total  of books sold) and total cost (total of items bought and staff salaries) during a period.
Another important role of the administrator is to revoke permissions from librarians or managers. This means that the permissions are be role-based. (Assume that the admin decides that librarians can add new books to the stock beside managers).

The data of the bookstore is stored in binary and text files and managed appropriately through Serialization/Deserialization.
