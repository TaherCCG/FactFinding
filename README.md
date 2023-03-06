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
</ol>
</br>
<em>If you would like a copy of this information, please use the [fork] feature on GitHub to get a copy.
 scroll to very top and click fork.</br>
 Thanks.
 </em>

---

</br>
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
</ol>

---

</br>
</br>
<h1 align="center">AWS Cloud Foundations – One Fact Finding exercise</h1>

## Questions

<ol>
<li><h3>Define what IaaS, PaaS and SaaS is.</h3></li>
<ul></br>
<li>IaaS is a cloud service where a cloud service provider (CSP) rents out highly scalable and automated IT infrastructure, usually over the internet, to a small and medium business (SMBs) or individual developers.</li>
<ul><li> Popular IaaS examples include Amazon EC2, Rackspace, Windows Azure, and Google Compute Engine</li>
</ul></br>
<li>PaaS gives you a cloud platform complete with components and working framework upon which you can build custom applications. The required storage, server, network, runtime, middleware, virtualization, and OS is provided for and managed by the vendor while you get to maintain and control your apps and data.</li>
<ul><li>Common examples of PaaS are AWS Elastic Beanstalk, Google App Engine, and Adobe Commerce</li></ul></br>
<li>SaaS is the end result, allowing businesses to deliver software on demand to customers. With SaaS, vendors are able to provide software via the internet to users and customers. A connected device and browser are all users need to access and use the software.</li>
<ul><li>Common examples of SaaS are Gmail, Slack, and Microsoft Office 365</li></ul>
</ul>
</br></br>
<li><h3>Provide 6 advantages of cloud computing.</h3></li>
<ol></br>
<li><strong>Trade capital expense (capex) for variable expense:</strong>
You don’t need to invest in data centres and servers before you know how you will use them. Instead, you can pay only when you use computing resources, and pay for how much you use.
</li></br>
<li><strong>Benefit from massive economies of scale:</strong>
By using cloud computing, you can achieve a lower variable cost than you can get on your own. Because usage from hundreds of thousands of customers is aggregated in the cloud, providers such as AWS can achieve higher economies of scale. These economies translate into lower, pay-as-you-go prices.</li></br>
<li><strong>Reduce guessing about capacity:</strong>
You can reduce guessing about your infrastructure capacity needs. When you make a capacity decision before you deploy an application, you often have either expensive idle resources or insufficient capacity. Cloud computing reduces these problems. You can access as many or as few resources as you need, and you can scale up and down as required with only a few minutes’ notice.
</li></br>
<li><strong>Increase speed and agility:</strong>
In a cloud computing environment, new IT resources are only a click away. Thus, you reduce the time that it takes to make those resources available to your developers from weeks to minutes. The result is a dramatic increase in agility for the organization. The cost and time that are needed to experiment and develop are much lower.
</li></br>
<li><strong>Stop spending money on running and maintaining data centres:</strong>
Running and maintaining data centres is expensive and time consuming. Focus on projects that differentiate your business, instead of focusing on the infrastructure. Cloud computing enables you to focus on your customers, instead of focusing on the tasks of racking, stacking, and powering servers.
</li></br>
<li><strong>Go global in minutes:</strong>
You can deploy your application in multiple AWS Regions around the world with a few clicks. As a result, you can provide a lower latency and better experience for your customers simply, and at minimal cost.
</li>
</ol>
</br></br>
<li><h3>Define what an AWS region and an Availability Zone is.</h3></li>
<ul></br>
<li>AWS Region is a separate geographic area. Each AWS Region has multiple, isolated locations known as Availability Zones. For information about finding the Availability Zones for an AWS Region, see Describe your Availability Zones in the Amazon EC2 documentation.</li></br>
<li>Availability Zones are multiple, isolated locations within each Region. Local Zones provide you the ability to place resources, such as compute and storage, in multiple locations closer to your end users.</li>
</ul>
</br></br>
<li><h3>List all the AWS regions.</h3></li>
<ol>
<li>US East (N. Virginia)</li>
<li>US East (Ohio)</li>
<li>US West (N. California)</li>
<li>US West (Oregon)</li>
<li>Asia Pacific (Hong Kong)</li>
<li>Asia Pacific (Mumbai)</li>
<li>Asia Pacific (Osaka-Local)</li>
<li>Asia Pacific (Seoul)</li>
<li>Asia Pacific (Singapore)</li>
<li>Asia Pacific (Sydney)</li>
<li>Asia Pacific (Tokyo)</li>
<li>Canada (Central)</li>
<li>Europe (Frankfurt)</li>
<li>Europe (Ireland)</li>
<li>Europe (London)</li>
<li>Europe (Milan)</li>
<li>Europe (Paris)</li>
<li>Europe (Stockholm)</li>
<li>Middle East (Bahrain)</li>
<li>South America (São Paulo)</li>
<li>Africa (Cape Town)</li>
</ol>
</br></br>
<li><h3>What are the categories in which the AWS services are grouped?</h3></li>
<ul></br>
<li>Compute: This category includes services that provide computing resources, such as EC2 (Elastic Compute Cloud), ECS (Elastic Container Service), and Lambda.</li></br>
<li>Storage: This category includes services that provide storage resources, such as S3 (Simple Storage Service), EBS (Elastic Block Store), and Glacier.</li></br>
<li>Database: This category includes services that provide database resources, such as RDS (Relational Database Service), DynamoDB, and ElastiCache.</li></br>
<li>Networking: This category includes services that provide networking resources, such as VPC (Virtual Private Cloud), Direct Connect, and Route 53.</li></br>
<li>Security: This category includes services that provide security resources, such as IAM (Identity and Access Management), KMS (Key Management Service), and WAF (Web Application Firewall).</li></br>
<li>Analytics: This category includes services that provide analytics resources, such as Redshift, EMR (Elastic MapReduce), and Kinesis.</li></br>
<li>Machine Learning: This category includes services that provide machine learning resources, such as SageMaker, Rekognition, and Comprehend.</li></br>
<li>Application Integration: This category includes services that provide application integration resources, such as SQS (Simple Queue Service), SNS (Simple Notification Service), and Step Functions.</li></br>
<li>Management and Governance: This category includes services that provide management and governance resources, such as CloudFormation, CloudTrail, and Config.</li></br>
<li>Developer Tools: This category includes services that provide developer tools, such as CodeCommit, CodeBuild, and CodeDeploy</li>
</ul>
</br></br>
<li><h3>What is the difference between object storage and block storage?</h3></li>
<ul></br>
<li>Object storage and block storage have different characteristics and are used for different purposes. Object storage is suitable for storing large amounts of unstructured data, while block storage is suitable for high-performance applications that require direct access to data.</li>
</ul></br></br>

<li><h3>List two AWS compute services and explain them.</h3></li>
<ul></br>
<li>Amazon Elastic Compute Cloud (EC2): EC2 is a scalable cloud computing service that provides virtual servers, or instances, in the cloud. EC2 instances can be launched in minutes and can be configured with different types of compute power, memory, storage, and networking capacity to meet different application requirements. EC2 supports a wide range of operating systems and software, allowing you to run almost any application in the cloud. EC2 instances can be managed using the AWS Management Console, command-line tools, or programmatically using APIs.</li></br>
<li>AWS Lambda: Lambda is a serverless compute service that allows you to run code in the cloud without provisioning or managing servers. With Lambda, you can upload your code and the service will automatically execute it in response to events, such as changes to data in an S3 bucket or a new message in an SQS queue. Lambda supports multiple programming languages, and you only pay for the compute time used to run your code, with no upfront fees or commitments. Lambda can be used for a wide range of applications, such as data processing, web and mobile backends, and IoT (Internet of Things) applications.</li>
</ul>
</br></br>
<li><h3>List two AWS storage services and explain them.</h3></li>
<ul></br>
<li>Amazon EBS (Elastic Block Store): EBS is a block storage service that provides persistent block-level storage volumes for use with EC2 instances. EBS volumes are automatically replicated within their availability zone for high availability, and they can be attached to EC2 instances to provide persistent storage for applications, databases, and other workloads. EBS volumes support multiple volume types, including general-purpose SSD, provisioned IOPS SSD, and magnetic, allowing you to choose the right storage type for your workload. EBS volumes also provide features such as snapshots, encryption, and multi-attach to help you protect and manage your data.</li></br>
<li>Amazon S3 (Simple Storage Service): S3 is a scalable and durable object storage service that allows you to store and retrieve any amount of data from anywhere on the web. S3 is designed for 99.999999999% (11 9's) durability, and it stores data across multiple availability zones for high availability and data durability. S3 supports a wide range of storage classes, including standard, standard-infrequent access, and Glacier for archival storage. S3 also provides a powerful set of features, such as versioning, lifecycle policies, cross-region replication, and access control to help you manage your data securely and cost-effectively.</li>
</ul>
</ol>
---

</br>
</br>
<h1 align="center">AWS Cloud Foundations – Two Fact Finding exercise</h1>

## Questions
<ol>
<li><h3>Explain the AWS Shared responsibility model?</h3></li>
<ul>
<li>The AWS Shared Responsibility Model is a security framework that outlines the security responsibilities of AWS and its customers. The model describes how security responsibilities are shared between AWS and the customer, and helps to ensure that both parties understand their respective security roles.</li>
<li>In the AWS Shared Responsibility Model, AWS is responsible for the security of the cloud, which includes the physical security of data centers, the security of the underlying infrastructure, and the security of AWS services. This includes tasks such as patching and updating the infrastructure, protecting the physical data centers, and securing the AWS platform.</li>
<li>Customers are responsible for the security of their data in the cloud, as well as the security of their applications and services. This includes tasks such as configuring their own security groups, managing access control to their resources, implementing encryption for their data, and ensuring the security of their applications.</li>
<li>The level of customer responsibility depends on the type of service used. For example, for Infrastructure as a Service (IaaS) offerings like Amazon EC2, customers are responsible for securing their own operating systems, applications, and data, while for Platform as a Service (PaaS) offerings like AWS Elastic Beanstalk, AWS manages the operating system and customers are responsible for securing their applications and data.</li>
<li>The AWS Shared Responsibility Model helps to ensure that security is a shared responsibility between AWS and its customers, and that both parties are aware of their respective security responsibilities. This enables customers to take an active role in securing their own data and applications in the cloud, while also allowing AWS to focus on providing secure and reliable cloud services.</li>
</ul>
</br>

<li><h3>Explain an Identity and Access Management (IAM) Role?</h3></li>
<ul>
<li>An Identity and Access Management (IAM) role is a set of permissions that define a specific set of actions that can be performed by an entity, such as a user or application, within a system or service.</li>
<li>IAM roles are used to grant permissions to perform certain tasks without the need for long-term access credentials, such as a username and password. Instead, roles are assigned to entities through an IAM policy that defines the permissions associated with the role.</li>
<li>IAM roles provide a more secure way to manage access to resources by allowing permissions to be granted based on specific needs rather than granting broad access. They are often used in cloud computing environments to manage access to services and resources across multiple accounts or applications.</li> 
<li>In summary, an IAM role is a collection of permissions that can be assigned to an entity through an IAM policy, allowing for more secure and fine-grained access control to resources within a system or service.</li>
</ul>
</br>

<li><h3>Explain an Identity and Access Management (IAM) Policy?</h3></li>
<ul>
<li>An IAM policy is a document that defines permissions and access control for entities, such as users or applications, within a system or service. It outlines the actions that are allowed or denied based on various conditions and can be used to manage access to resources and services within an organization. IAM policies are often used in conjunction with IAM roles to provide secure and granular access control to resources.</li>
</ul>
</br>

<li><h3>Describe an Amazon Machine Image (AMI)?</h3></li>
<ul>
<li>An Amazon Machine Image (AMI) is a pre-configured virtual machine image that can be used to create an instance on the Amazon Web Services (AWS) cloud platform. An AMI includes the operating system, application server, and any additional software needed to run an application. It also includes any custom configurations and data specific to the user's needs.</li>
</ul>
</br>

<li><h3>List the different EC2 instance types with use cases for each type?</h3></li>
<ul>
<li>General Purpose: These instances are a good fit for most workloads that require a balance of compute, memory, and network resources. They are ideal for running small to medium-sized databases, web servers, and development environments. Examples include the t2, m5, and m6g instance families.</li>
<li>Compute Optimized: These instances are designed for workloads that require high compute power, such as high-performance computing (HPC), batch processing, and scientific computing. They offer a higher ratio of compute resources to memory and network resources. Examples include the c5 and c6g instance families.</li>
<li>Memory Optimized: These instances are designed for workloads that require large amounts of memory, such as in-memory databases, real-time big data processing, and caching. They offer a higher ratio of memory resources to compute and network resources. Examples include the r5 and r6g instance families.</li>
<li>Storage Optimized: These instances are designed for workloads that require high storage capacity, such as data warehousing, log processing, and large-scale file systems. They offer a higher ratio of storage resources to compute and memory resources. Examples include the i3 and d3 instance families.</li>
<li>GPU Optimized: These instances are designed for workloads that require high-performance graphics processing, such as video rendering, machine learning, and gaming. They come with one or more graphics processing units (GPUs) and offer a higher ratio of GPU resources to compute and memory resources. Examples include the p3 and g4 instance families.</li>
<li>FPGA Optimized: These instances are designed for workloads that require high-performance hardware acceleration, such as genomics, financial analysis, and data compression. They come with one or more field-programmable gate arrays (FPGAs) and offer a higher ratio of FPGA resources to compute and memory resources. Examples include the f1 instance family.</li>

</ul>
</br>

<li><h3>Explain Virtual Private Cloud (VPC)?</h3></li>
<ul>
<li>A Virtual Private Cloud (VPC) is a virtual network infrastructure that allows users to create isolated and secure network environments within the Amazon Web Services (AWS) cloud platform. It provides complete control over the virtual networking environment, including IP address ranges, subnets, and routing tables.</li>
</ul>
</br>

<li><h3>Differentiate between a Public and a Private subnet?</h3></li>
<ul>
<li> A subnet is a logical subdivision of an IP network that enables network administrators to segment a larger network into smaller, more manageable subnetworks. When creating subnets, network administrators can choose between public and private subnets.</li>
<li> The main difference between a public and a private subnet is how they are accessed from the internet.</li>
<li>A public subnet is a subnet that is accessible from the internet. It has a publicly routable IP address that can be reached from anywhere on the internet. Public subnets are typically used for resources that need to be accessed from the internet, such as web servers, mail servers, or other public-facing services.</li>
<li>A private subnet is a subnet that is not accessible from the internet. It uses private IP addresses that are not routable on the public internet. Private subnets are typically used for resources that do not need to be accessed from the internet, such as internal database servers, application servers, or other internal resources.</li>
<li>To access a resource in a private subnet from the internet, you need to use a mechanism such as VPN or a bastion host that provides a secure and controlled entry point into the private subnet.</li>
</ul>
</ol>
</br>




---

</br>
</br>
<h1 align="center">AWS Well-Architected Framework - Fact Finding exercise</h1>

## Questions
<ol>
<li><h3>What are the five pillars of the Well Architected Framework (WAF)?</h3></li>
<ul>
<li>The Well-Architected Framework (WAF) is a set of best practices and guidelines designed to help architects build secure, high-performing, resilient, 
and efficient infrastructure in the cloud. The WAF consists of five pillars, which are: </li>
<ol>
<li>Operational Excellence</li>
<li>Security</li>
<li>Reliability</li>
<li>Performance Efficiency</li>
<li>Cost Optimization</li>
</ol>
<li>By following these pillars, architects can design and implement cloud solutions that are secure, reliable, efficient, and cost-effective.</li>
</ul>
</br>

<li><h3>What are the 3 areas of operational excellence in the cloud?</h3></li>
<ul>
<li>The three areas of operational excellence in the cloud are:</li>

<ol>
<li>Managing and automating changes</li>
<li>Responding to events</li>
<li>Defining and managing performance</li>
</ol>
<li>By focusing on these three areas of operational excellence, organizations can improve the efficiency and reliability of their cloud infrastructure, reduce costs, and better meet the needs of their business.</li>
</ul>
</br>

<li><h3>What are the design principles that strengthen system security?</h3></li>
<ul>
<li>There are several design principles that can be followed to strengthen system security:</li>
<ul>
<li>Implement a strong identity and access management (IAM) strategy.</li>
<li>Use a defense-in-depth approach</li>
<li>Apply the principle of least privilege</li>
<li>Implement security by design</li>
<li>Continuously monitor and audit the system</li>
<li>Use encryption</li>
<li>Regularly patch and update the system</li>
</ul>
<li>By following these design principles, organizations can improve the security posture of their systems and better protect against security threats and attacks</li>
</ul>
</br>

<li><h3>What are the design principles that increase reliability?</h3></li>
<ul>
<li>These are some design principles that can increase the reliability of a system:</li>
<ul>
<li>Build for scalability</li>
<li>Use automation</li>
<li>Ensure resiliency</li>
<li>Implement monitoring and logging</li>
<li>Use well-architected patterns</li>
<li>Test for reliability</li>
</ul>
<li>By following these design principles, organizations can increase the reliability of their systems and minimize the risk of downtime, data loss, and other disruptions.</li>
</ul>
</br>

<li><h3>What are the areas to focus on to achieve performance efficiency in the cloud?</h3></li>
<ul>
<li>To achieve performance efficiency in the cloud, there are several areas to focus on</li>

<ul>
<li>Instance selection: Choose the right instance types based on the specific needs of the application, workload, and budget. Consider factors such as CPU, memory,
storage, and network performance when selecting instance types.</li>
<li>Resource scaling: Implement auto-scaling to automatically adjust resources up or down based on workload demands</li>
<li>Data storage optimization: Optimize data storage by using caching, compression, and deduplication to reduce the amount of data that needs to be stored and processed.</li>
<li>Content delivery optimization: Use a content delivery network (CDN) to optimize content delivery and improve the performance of web applications and websites.</li>
<li>Database optimization: Optimize database performance by implementing indexing, caching, and sharding to reduce query times and improve overall system performance.</li>
<li>Application architecture optimization: Optimize application architecture by using microservices and decoupling components to improve scalability and performance.</li>
<li>Performance testing: Conduct performance testing to identify performance bottlenecks and optimize system performance. This includes load testing, stress testing,
and capacity planning.</li>

</ul>

</ul>
</br>

<li><h3>What are the different approaches to using AWS resources in a cost-effective manner?</h3></li>
<ul>
<li>Right-sizing: Use the appropriate size of resources, such as instances and storage, based on the workload requirements. Avoid overprovisioning resources, which can result in unnecessary costs.</li>
<li>Reserved instances: Purchase reserved instances to reduce costs over time. This involves paying upfront for a period of one or three years, and receiving a discount on the hourly usage rate.</li>
<li>Spot instances: Use spot instances to take advantage of unused EC2 capacity, which is available at a significantly lower price than on-demand instances. However, spot instances can be interrupted
at any time if the demand for capacity increases.</li>
<li>Autoscaling: Use autoscaling to automatically add or remove resources based on demand. This ensures that resources are only used when needed, and reduces costs during periods of low demand.</li>
<li>Storage optimization: Optimize storage by using appropriate storage types, implementing data compression, and using lifecycle policies to move data to cheaper storage tiers as it ages.</li>
<li>Use managed services: Use managed services, such as managed databases and managed caching, to reduce the operational overhead and cost of managing infrastructure.</li>
<li>Cost allocation and tagging: Use cost allocation and tagging to track and analyze costs by different resources, projects, and departments. This helps to identify areas where costs can be optimized and reduced.</li>
</ul>
</br>

</ol>
</br>
