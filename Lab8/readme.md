## Executive Summary

### Data, Information and Knowledge
#### Relational Data

- Data - the raw bits and pieces of information. Quantitative  or Qualitative.
- Information - what is done with the data "converted context".
- Knowledge - use of the information. decision, policy, innovation.

PARENT TABLE 

| cust ID  |    item       |order ID|
|----------|:-------------:|-------:|
| 32690    |   6 - Shirt   |   20086|
| 38898    |   4 - Hoodie  |   20087|
| 42748    |   10 -Short   |   20060|

Primary Key = is a column (or group) that uniquely identify every row in that table. A primary Key can't appear more than once in the table.  A table cannot have more than one primary key.
*The example above the customer ID is the Primary Key*

CHILD TABLE

| order ID |      item     |  stock|
|----------|:-------------:|------:|
| 20086    |    Shirt      |   1600|
| 20087    |    Hoodie     |   1200|
| 20060    |    Short      |   6101|


A FOREIGN KEY is a key used to link two tables together. The foreign key is a field (or collection of fields) in one table that refers to the primary key in another table. *In this example the foreign key is the Order ID, we can create a relationship of cutomer number from parent table through dep code of child table to check stock of an item.*

The table containing the foreign key is called the child table, and the table containing the candidate key is called the referenced or parent table.

The customer and order table are related = they are all ordering items of clothing. The table has customer number what they ordered and dept the item is located. The dept number will check stock at the store.

The order table - The properties of a field describe the information of the data added to that field. A field's data type is the most important property because it determines what kind of data the field can store.

#### Big Data

Volume: Refers to the mass quantity of data that organizations have been trying to harness and to improve decision making across the enterprise.

Velocity: This characteristic represents the motion of the data. Real-time nature of data creation, enterprises have invested a lot to develop Big Data solutions which could incorporate streaming data into business processes and decision making.

Variety: It defines different types of data and data resources. Daily new categories are added to the list of data types.
*Unstructured data = the data that does not have a well-defined set of rules, for example, Twitter, Facebook, , audio files, MRI images, web pages, web logs has contributed immensely to the rise of Big Data.*

Veracity: It can be termed as the trustworthiness of the data. We may also define veracity as the level of reliability associated with certain types of data.

Two types of technology have driven the increased need for big data?

Predictive Analytics -
One of the prime tools for businesses to avoid risks in decision making, predictive analytics can help businesses. Predictive analytics hardware and software solutions can be utilized for discovery, evaluation and deployment of predictive scenarios by processing big data. Such data can help companies to be prepared for what is to come and help solve problems by analyzing and understanding them.

 Data Integration -
A key operational challenge for most organizations handling big data is to process terabytes (or petabytes) of data in a way that can be useful for customer deliverables. Data integration tools allow businesses to streamline data across several big data solutions such as Amazon EMR, Apache Hive, Apache Pig, Hadoop, MapReduce, MongoDB.

Big Data is already being used to improve operational efficiency. Companies have the ability to make informed decisions based on the very latest up-to-the-moment information.

### Structured Query Language (SQL)

RDBMS stands for Relational Database Management System. RDBMS is a database management system. And SQL is the language used for communicating with data in an RDBMS. RDBMS is the basis for SQL, and for all modern database systems such as MS SQL Server, IBM DB2, Oracle, MySQL, and Microsoft Access. The data in RDBMS is stored in database objects called tables. A table is a collection of related data entries and it consists of columns and rows. The analogy is - RDBMS is a book and SQL is the language being used in the book. The purpose of SQL is learning the language to read the book (or create tables).

I gave a similar example in my markdown table above. From the two tables = Customer and Order (details) table.  The customer ID is unique and the order ID has units - price and quantity.

Primary Key = is a column (or group) that uniquely identify every row in that table. A primary Key can't appear more than once in the table.  A table cannot have more than one primary key.
*The example above the order ID is the Primary Key*

A FOREIGN KEY is a key used to link two tables together. The foreign key is a field (or collection of fields) in one table that refers to the primary key in another table. *In this example the foreign key is the customer ID, we can create a relationship of cutomer number from parent table through dep code of child table to check stock of an item.*

### SQL Injections

SQL Injection a code injection technique that might destroy your database, one of the most common web hacking techniques, by the placement of malicious code in SQL statements, via web page input.  For example, in a financial application, an attacker could use SQL Injection to alter balances, void transactions, or transfer money to their account. Almost every technical advance, hackers discovered new attack vectors, and for as long as relational databases have been used in web applications, so too have SQL Injection attack vectors.
 The more recent the version of your software is, the less chance of having a vulnerability, or at least a widely-known one. You can also ensure your database itself is as secure as possible.  In the information security field, there exists a concept known as the principle of least privilege.  This principle states that a user or program should have only the absolute very least amount of privileges necessary to complete its tasks. 

### Ethical and Legal Implications

#### Code of Ethics

The term ethics is defined as “a set of moral principles” or “the principles of conduct governing an individual or a group. ”[https://www.merriam-webster.com/dictionary/ethics].  A code of ethics is a document that outlines a set of acceptable behaviors for a professional or social group.

Association for Computing Machinery (ACM) created a code, in this case set of rules, consisting of 24 imperatives (formulated as statements) of personal responsibility, identifies the elements of such a commitment. It contains many issues professionals are likely to face. They created this code of ethics to clarify the acceptable standards of behavior for a professional group.
 
Many places provide technology services to the public require agreement to an acceptable use policy (AUP) before those services can be accessed. Similar to a code of ethics, this policy outlines what is allowed and what is not allowed while someone is using the organization’s services. Some examples are public libraries, coffee shops and schools. ACM is more of a governing board of professionals that focuses on computing, there are more specific admonitions. The AUP is agreed upon entering specific sites.

The beginning of every school year a parent and child must sign a paper agreeing to the following:
Parents/guardians are required to adhere to the following guidelines:
1. Parents/guardians will NOT share their password with anyone, including their own children.
2. Parents/guardians will not attempt to harm or destroy the district’s data or network, or in any way impede the
district’s internet service.
3. Parents/guardians will not use the Infinite Campus Parent Portal for any illegal activity, including violation of Data
Privacy Laws. Anyone found to be violating laws will be subject to civil and/or criminal prosecution.
4. Parents/guardians will not access data or any account owned by another parent/guardian.
5. Parents/guardians who identify a security problem with the Infinite Campus Parent Portal must notify the Berea
City School District or the local school immediately without demonstrating the problem to anyone else.
6. Parents/guardians who are identified as a security risk to the Infinite Campus Parent Portal or any other Berea
City School District computers or networks, will be denied access to the Infinite Campus Parent Portal. 
https://www.berea.k12
.oh.us/cms/lib6/OH01000054/Centricity/Domain/240/Acceptable%20Use%20Policy-Parents%20Mail%20Home.pdf

#### Intellectual Property 
The World Intellectual Property Organization is comprised of 15 specialized agencies of the United Nations. WIPO was created in 1967 "to encourage creative activity, to promote the protection of intellectual property throughout the world".


#### Information Collection

## Conclusion
