# DBFoundations-Module07
Assignment07

<h1>**FUNCTIONS**</h1>

<h2>**Introduction**</h2>

MS SQL, like many other database programs, has many useful built-in standard functions. In addition, users are able create their own functions.  These are called user-defined functions. Functions are very useful as they save time and maintain data integrity.

<h2>**SQL User Defined Functions**</h2>

Like views and stored procedures, UDF’s save time by calling upon saved script to run results. Limited storage is needed and the code is concealed which provides a layer of security. Applications are not interrupted if the script needs modification. SQL UDF’s are very useful for performing repetitive operations on your data. The function can be written once and called upon over and over. Unlike views, UDF’s allow parameters. Parameters act to control the input and user can define the output.

<h2>**Scalar, Inline, and Multi-Statement Functions**</h2>

There are three main types of user-defined functions: scalar, inline, and multi-statement. Scalar functions return a single value and are similar to the built-in functions. The value returned on scalar functions can be based on the value set in the parameters. Inline functions, also referred to a table valued functions, return table information like a single row or multiple rows of data. They may also include a single select statement. Multi-statement functions are advantageous as they can return several rows of data that can’t be contained in a select statement.

<h2>**Conclusion**</h2>
UDF’s are functions created by users. User-defined functions are useful in eliminating writing the same code over and over. The add an abstraction layer to which helps to maintain data integrity. 
