#### FactFinding
<p>AWSre/StartProjects - Fact Finding Exercise: Allow learners to work on the self-paced exercise for the allotted time.</p>


<h1 align="center">Python Fact Finding exercise</h1>

## Questions

<ol>
<li><h3>Define a list and tuple in Python. Provide some examples.</h3></li>
<ul>
<li>List:</li>
<ul>
<li>A list is a data structure in Python that is a mutable, or changeable, ordered sequence of elements and can be defined using any variable name. Each element or value that is inside of a list is called an item. Lists are defined by having values between square brackets [ ]
Lists can have/store different data types.
</br>
<li>List items are ordered, changeable, and allow duplicate values.</li>
<li><em>Below are some examples of how to define a list and what data types they can contain.</em></li>
<ul>
<li><code>myList=[]  <em>This defines an empty list.</em></code></li>
<li><code>myList=[name, 35, 5.11, 5J, True, data, including, duplicates]
</code></li>
<li><code>friends = ['John','Michael','Terry','Eric','Graham']
print(friends[0],friends[4])
print(friends[3])
print(friends[2:])
print(friends[2:4])</code></li>
<ul>
<li><code><em>output:</em>
John Graham</br>
Eric</br>
['Terry', 'Eric', 'Graham']</br>
['Terry', 'Eric']</code></li>
</ul>
</ul>
<li>List items are indexed, the first item has index [0], the second item has index [1] etc.</li>
<li>Lists contain items and it can be of any data types. Integers, Complex, Strings, Float, Boolean and can have multiple duplicates with unlimited amount of items</li>
</ul>
</br>
<li>Tuple:
<ul>
<li>Tuples are used to store multiple items in a single variable, can be defined using any variable name and assigning different values 
to the tuple inside the round brackets (). The tuple is ordered, unchangeable, and allows duplicate values.</li>
<li>Ordered means that the items have a defined order, and that order will not change.</li>
<li>Unchangeable means that we cannot change, add or remove items after the tuple has been created.</li>
<li>Indexed means that they can have items with the same value.</li>
<ul>
<li>example of same value:</br>
<code>thistuple = ("apple", "banana", "cherry", "apple", "cherry")</code></li>
<li>A tuple with strings, integers and boolean values:</br>
<code>tuple1 = ("abc", 34, True, 40, "male")</code></li>
<li>To create a tuple with only one item, you have to add a comma after the item, otherwise Python will not recognize it as a tuple.</br>
<code>thistuple = ("apple",)</br>
print(type(thistuple))</br>
</br>
#NOT a tuple</br>
thistuple = ("apple")</br>
print(type(thistuple))</code></li>
</ul>
<li>Tuples make the code safe from any accidental modification. If a data is needed in a program which is not supposed to be changed, then it is better to put it in ‘tuples’ than in ‘list’. They are also faster then lists and Tuples can be used as dictionary keys if it contains immutable values like strings, numbers or another tuple.</li>
</ul>
</ul>
</br>
<li><h3>What is a namespace in Python?</h3></li>
<ul>
<li>A namespace is a collection of names and the details of the objects referenced by the names. </li>
<li>In python, there are four types of namespaces, namely built-in namespaces,global namespaces, local namespaces and enclosing namespaces.</li>
<li>A built-in namespace contains the names of built-in functions and objects. It is created while starting the python interpreter, exists as long as the interpreter runs, and is destroyed when we close the interpreter. It contains the names of built-in data types,exceptions and functions like print() and input().</li>
<li>Global namespaces are defined at the program or module level. It contains the names of objects defined in a module or the main program. A global namespace is created when the program starts and exists until the program is terminated by the python interpreter.</li>
<li>A local namespace is defined for a class, a function, a loop, or any block of code. The names defined in a block of code or a function are local to it. The variable names cannot be accessed outside the block of code or the function in which they are defined. The local namespace is created when the block of code or the function starts executing and terminates when the function or the block of code terminates.</li>
<li>A function or a block of code defined inside any function can access the namespace of the outer function or block of code. Hence the outer namespace is termed as enclosing namespace for the namespace of the inner function or block of code.</li>
</ul>
</br>
<li><h3>What is the difference between a local variable and a global variable?</h3></li>
<ul>
<li>Local Variables are created when a function starts its execution and are lost when the function ends.  Also local variables do not offer data sharing.</li>
<li>Global variables are declared outside functions and are accessible by all functions in the program. Global variables are not very reliable because any function in the program can alter its value. They are useful when many functions are using the same set of data.</li>
</ul>
</br>
<li><h3>What is an IDE? Mention some common IDEs that could be used with Python.</h3></li>
<ul>
<li>An Integrated Development Environment (IDE) is software that developers/programers use to write code.  It increases developer productivity by combining capabilities such as software editing, building, testing and packaging in a easy to use application.</li>
<li>Here are few IDE's:</li>
<ul>
<li>Visual Studio Code - using it while I am typing this Markdown file</li>
<li>PyCharm - is a dedicated python IDE.</li>
<li>Spyder - is an open-source cross-platform integrated development environment for scientific programming in the Python language</li>
<li>Thonny - is an integrated development environment for Python that is designed for beginners.</li>
<li>Atom - it was a free and open-source text and source code editor for macOS, Linux, and Microsoft Windows with support for plug-ins written in JavaScript, and embedded Git Control. Developed by GitHub, Atom was a desktop application built using web technologies.</li>
</ul>
</ul>
</br>
<li><h3>What are modules in Python?  Provide some examples.</h3></li>
<ul>
<li>Module is a file that contains code to preform a specific task. A module may contain variables, functions and classes etc.  We use modules when our code gets bigger so we call them in to our program and reuse the code in the module instead of putting everything in our program. This makes our code organised and easier to maintain </li>
<ul>
<li>Example 1:</br>
 <em>import standard math module</em></br> 
<code>import math</br></code>

 <em>use math.pi to get value of pi</em></br>
<code>print("The value of pi is", math.pi)</code>
</li>
<li>Example 2:</br>
<em>importing os module</em></br> 
<code>import os</code></br>
<em>Get the current working</br> 
directory (CWD)</em></br>
<code>cwd = os.getcwd()</code></br>
<em>Print the current working</br> 
directory (CWD)</em></br> 
<code>print("Current working directory:", cwd)</code> 
</li>
</ul>
<li>As shown above using OS Module.  OS module in python provides functions for interacting with the operating system. </li>
</ul>

</br>
<li><h3>What is the difference between an array and a list?</h3></li>
<ul>
<li>The main difference between a list and array is that list can't manage arithmetic operations and Array can manage arithmetic operations. </li>
<li>When it comes to flexibility, the list is perfect as it allows easy modification of data. Whereas the array is not suitable as it does not allow easy modification of data.</li>
<li>Arrays consume less memory, and it favours longer sequence of data than a list.</li>
</ul>
</br>
<li><h3>What are operators?  Provide some examples.</h3></li>
<ul>
<li>An operator is a character that represents a specific mathematical or logical action or process.</li>
<li>In Python there are 7 different operators. Python divides the operators in the following groups: </li>
<ul>
<li>Arithmetic operators examples:</li>
<ul>
<li>"*"  multiplication</li>
<li>"+"	 Addition</li>
<li>"//" Floor division</li>
</ul>
<li>Logical Operators example:</li>
<ul>
<li>"and" 	Returns True if both statements are true	</li>
<li>"or"	Returns True if one of the statements is true</li>
<li>"not"	Reverse the result, returns False if the result is true</li>
</ul>
<li>Assignment Operators examples:</li>
<ul>
<li>"="     x = 5 <em>is same as</em> x = 5</li>
<li>"-="	x -= 3 <em>is same as</em>	x = x - 3</li>
<li>"^="	x ^= 3 <em>is same as</em>	x = x ^ 3</li>
</ul>
<li>Comparison Operators examples:</li>
<ul>
<li>"=="	Equal</li>
<li>">"     Greater than</li>
<li>"<="	Less than or equal to</li>
<li></li>
</ul>
<li>Membership Operators examples:</li>
<ul>
<li>"in" 	Returns True if a sequence with the specified value is present in the object. <em>example :</em> x in y</li>
<li>not in	Returns True if a sequence with the specified value is not present in the object. <em>example :</em> x not in y </li>
</ul>
<li>Bitwise Operators examples:</li>
<ul>
<li>"&" <em>is named "AND" </em>	Sets each bit to 1 if both bits are 1</li>
<li>"|"	<em>is named "OR"</em>	Sets each bit to 1 if one of two bits is 1</li>
<li>"^"	<em>is named "XOR"</em>	Sets each bit to 1 if only one of two bits is 1</li>
</ul>
</ul>
</Ul>
</br>
<em>If you would like a copy of this information, please use the [fork] feature on GitHub to get a copy.</br>
 scroll to very top and click fork.</br>
 Thanks.
 </em>

</br>
<h1 align="center">Database Fact Finding Exercise</h1>

## Questions

<ol>
<li><h3>What is the difference between a relational and a non-relational database?</h3></li>
<ul>
<li>A relational database stores data in tables, which consist of rows and columns. Each table represents a specific entity, such as a customer, product, or order. The data in each table is structured and organized based on predefined relationships between the tables. These relationships are typically established using primary keys and foreign keys. Relational databases use SQL (Structured Query Language) for querying and manipulating data.</li>
<li>A non-relational database (also called a NoSQL database) stores data in a flexible and unstructured way. Instead of tables, data is stored in collections or documents. Collections or documents can be thought of as containers for storing related data. Each document can have a different structure, and the relationships between documents are typically more flexible and dynamic than in a relational database. Non-relational databases often use non-SQL query languages, such as MongoDB's query language.</li>
</ul>
<li><h3>What are indexes?</h3></li>
<ul>
<li>Indexes are data structures that improve the speed of data retrieval operations on a database table. An index is created on one or more columns of a table, and it stores a sorted copy of the values in those columns.</li>
</ul>
<li><h3>What are primary keys and secondary keys?</h3></li>
<ul>
<li>In database design, a primary key is a unique identifier for each row in a table. The primary key serves as a reference point for related tables, and it ensures that each row in the table can be identified and accessed quickly and efficiently</li>
<li>A secondary key, also known as a non-primary key, is any column or set of columns in a table that is indexed for faster data retrieval. Unlike the primary key, a secondary key does not necessarily have to be unique. Secondary keys are used to speed up queries that involve searching, sorting, or grouping on specific columns.</li>
<ul><li>For example, in a table of customers, the primary key might be the customer ID column, which has a unique value for each customer. The table might also have a secondary key on the customer name column, which would allow queries to retrieve all customers with a specific name quickly and efficiently</li>
</ul>
</ul>
<li><h3>What are inner joins and outer joins?</h3></li>
<ul>
<li>In SQL, a join operation is used to combine rows from two or more tables based on a related column between them. The two most common types of join operations are inner joins and outer joins.</li>
<li>An inner join returns only the rows that have matching values in both tables being joined. The result set includes only the rows where the join condition is true. Inner joins can be expressed using the JOIN keyword or by simply listing the tables and using the WHERE clause to specify the join condition.</li>
<ul><li>For example, suppose we have two tables, Customers and Orders, with a common column of CustomerID. An inner join between the two tables would return only the rows where the CustomerID value appears in both tables:</li>
<code>SELECT *
FROM Customers
JOIN Orders
ON Customers.CustomerID = Orders.CustomerID;</code>
<li>An outer join, on the other hand, returns not only the matching rows but also the non-matching rows from one or both of the tables being joined. There are three types of outer joins: left outer join, right outer join, and full outer join.</li>
</ul>
</ul>
<li><h3>What is the difference between DROP TABLE and TRUNCATE TABLE?</h3></li>
<ul>
<li>In SQL, both the DROP TABLE and TRUNCATE TABLE commands are used to remove all data from a table. However, they differ in how they accomplish this task and the effects they have on the table and its related objects.</li>
<li>DROP TABLE is a DDL (Data Definition Language) command that permanently removes a table and all its related objects, including indexes, constraints, triggers, and permissions. Once a table is dropped, all data and metadata associated with the table are deleted from the database. The DROP TABLE command cannot be rolled back, so it should be used with caution.</li>
<li>TRUNCATE TABLE, on the other hand, is a DML (Data Manipulation Language) command that removes all rows from a table but keeps the table structure and its related objects intact. TRUNCATE TABLE resets the identity value of any auto-increment columns and releases the storage space allocated to the table. TRUNCATE TABLE is faster than DELETE because it does not log individual row deletions.</li>

</ul>

<li><h3>What are the different data types in SQL?</h3></li>
<ul>
<li>In SQL, data types are used to define the type of data that can be stored in a database column. The most common data types in SQL are:</li>
<ul>
<li>Numeric data types</li>
<li>Character data type</li>
<li>Date and time data types</li>
<li>Boolean data type</li>
<li>Binary data types</li>
</ul>
</ul>

<li><h3>Explain the WHERE and HAVING clauses.</h3></li>
<ul>
<li>In SQL, the WHERE and HAVING clauses are used to filter data in a query, but they are used in different contexts.</li>
<li>The WHERE clause is used to filter rows in a query based on one or more conditions. It is used with the SELECT, UPDATE, and DELETE statements. The WHERE clause can be used to specify conditions that involve comparison operators eg: <code>=, <>, >, <, >=, <= </code>and logical operators eg: <code>AND, OR, NOT</code> For example:</li>
<ul>
<li><code>SELECT *
FROM customers
WHERE age > 30 AND city = 'New York';</code></li>

</ul>
<li>The HAVING clause is used to filter groups in a query based on one or more conditions. It is used with the SELECT statement when using aggregate functions e.g:<code> COUNT, SUM, AVG, MAX, MIN</code> to group data. The HAVING clause can be used to specify conditions that involve comparison operators and logical operators, just like the WHERE clause. For example:</li>
<ul>
<li><code>SELECT city, COUNT(*)
FROM customers
GROUP BY city
HAVING COUNT(*) > 100;</code></li>
</ul>
<li>The key difference between WHERE and HAVING is that WHERE is used to filter rows before grouping, while HAVING is used to filter groups after grouping. In other words, WHERE is applied to individual rows, while HAVING is applied to groups created by the GROUP BY clause.</li>
</ul>
