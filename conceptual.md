### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

	It is an open source object-relational database system that uses and extends the SQL language

- What is the difference between SQL and PostgreSQL?

    SQL server is a database management system which is mainly used for e-commerce and providing different data warehousing solutions. PostgreSQL is an advanced version of SQL which provides support to different functions of SQL like foreign keys, subqueries, triggers, and different user-defined types and functions.

- In `psql`, how do you connect to a database?

	psql database_name

- What is the difference between `HAVING` and `WHERE`?

	A WHERE clause is used is filter records from a result. The filter occurs before any groupings are made.
	A HAVING clause is used to filter values from a group.

- What is the difference between an `INNER` and `OUTER` join?

	The major difference between inner and outer joins is that inner joins result in the intersection of two tables, whereas outer joins result in the union of two tables.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

	I don't know

- What is an ORM? What do they do?

	An object-relational mapper provides an object-oriented layer between relational databases and object-oriented programming languages without having to write SQL queries. It standardizes interfaces reducing boilerplate and speeding development time.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

	Not waiting on promises?

- What is CSRF? What is the purpose of the CSRF token?

	A CSRF (Cross-Site Request Forgery) token is a secure random token. 
	It is used to prevent CSRF attacks. The token needs to be unique per user session and should be of large random value to make it difficult to guess.

	A CSRF secure application assigns a unique CSRF token for every user session. These tokens are inserted within hidden parameters of HTML forms related to critical server-side operations. They are then sent to client browsers.

- What is the purpose of `form.hidden_tag()`?

	To hide the CSRF token 
