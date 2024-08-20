### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
Object-Relational database management system based on POSTGRES. Using object-oriented features from PostgreSQL can let you communicate with the database servers using objects in their code, define complex custom data types, define functions that work with their own data types, and define inheritance between tables.

- What is the difference between SQL and PostgreSQL?
PostgreSQL is open-source and an object-relational database, while SQL is licensed by Microsoft and a relational database system.

- In `psql`, how do you connect to a database?
You use command line options like -d, -h, -p, -U to identify the name of the target database, the host name of the server, the port number of the server, and what user you want to connect as.

- What is the difference between `HAVING` and `WHERE`?
WHERE allows you to filter data from specific rows (individual rows) from a table based on certain conditions. HAVING allows you to filter daata from a group of rows in a query based on conditions involving aggregate values.

- What is the difference between an `INNER` and `OUTER` join?
Inner Join only uses the rows that match the condition in both tables. Outer Join can use a full join (all rows from both tables), Left Join (all rows from left table and matching rows from right table), or Right Join (all rows from right table and matching rows from the left table).

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
Left Join (all rows from left table and matching rows from right table).
Right Join (all rows from right table and matching rows from the left table).

- What is an ORM? What do they do?
Object Relational Mapper allows you to make queries and handle data using simple Python objects and methods.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
AJAX runs in the user's browser and makes asynchronous requests. AJAX reqs are useful for dynamic web apps with user interaction. HTTP reqs from server side make requests to external APIs or services. HTTP reqs are useful for backend tasks that don't require instantaneous reactions from user input.

- What is CSRF? What is the purpose of the CSRF token?
Cross-Site Request Forgery. The token is a unique, secret, and unpredictable value that helps protect web apps from CSRF attacks. It could be a synchronizer token or a challenge token, as some examples.

- What is the purpose of `form.hidden_tag()`?
This element defines an extra form field that is hidden, used by Flask-WTF to implement CSRF protection.