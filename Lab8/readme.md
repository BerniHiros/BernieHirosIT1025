## Executive Summary

### Data, Information and Knowledge
#### Relational Data

- Data - the raw bits and pieces of information. Quantative or Qualitative.
- Information - what is done with the data "converted context".
- Knowledge - use of the information. decision, policy, innovation.

PARENT TABLE 

| cust num |    order      |Dep code|
|----------|:-------------:|-------:|
| 32690    |   6 - Shirt   |   20086|
| 38898    |   4 - Hoodie  |   20087|
| 42748    |   10 -Short   |   20060|

Primary Key = is a column (or group) that uniquely identify every row in that table. A primary Key can't appear more than once in the table.  A table cannot have more than one primary key.

*The example above the customer number is the Primary Key*

CHILD TABLE

| Dep code |      item     |  stock|
|----------|:-------------:|------:|
| 20086    |    Shirt      |   1600|
| 20087    |    Hoodie     |   1200|
| 20060    |    Short      |   6101|


A FOREIGN KEY is a key used to link two tables together. The foreign key is a field (or collection of fields) in one table that refers to the primary key in another table.

The table containing the foreign key is called the child table, and the table containing the candidate key is called the referenced or parent table.

*In this example the foreign key in Deptcode, we can create a relationship of cutomer order form parent table throught dep code of child talbe to check stock of an item.*

The customer and order table are related = they are all ordering items of clothing. The table has customer number what they ordered and dept the item is located. The dept number will check stock at the store.

The order table - The properties of a field describe the information of the data added to that field. A field's data type is the most important property because it determines what kind of data the field can store.

#### Big Data

Volume: Refers to the mass quantity of data that organizations have been trying to harness and to improve decision making across the enterprise.
Velocity: This characteristic represents the motion of the data. Real-time nature of data creation, enterprises have invested a lot to develop Big Data solutions which could incorporate streaming data into business processes and decision making.
Variety: It defines different types of data and data resources. Daily new categories are added to the list of data types.
*Unstructured data = the data that does not have a well-defined set of rules, for example, Twitter, Facebook, , audio files, MRI images, web pages, web logs has contributed immensely to the rise of Big Data.*
Veracity: It can be termed as the trustworthiness of the data. We may also define veracity as the level of reliability associated with certain types of data.

Two types of technology have driven the increased need for big data?

Predictive Analytics
One of the prime tools for businesses to avoid risks in decision making, predictive analytics can help businesses. Predictive analytics hardware and software solutions can be utilised for discovery, evaluation and deployment of predictive scenarios by processing big data. Such data can help companies to be prepared for what is to come and help solve problems by analyzing and understanding them.

 Data Integration
A key operational challenge for most organizations handling big data is to process terabytes (or petabytes) of data in a way that can be useful for customer deliverables. Data integration tools allow businesses to streamline data across a number of big data solutions such as Amazon EMR, Apache Hive, Apache Pig, Apache Spark, Hadoop, MapReduce, MongoDB and Couchbase.

In conclusion, Big Data is already being used to improve operational efficiency. Companies have the ability to make informed decisions based on the very latest up-to-the-moment information.

Structured Query Language (SQL)


SQL Injections
Ethical and Legal Implications
Code of Ethics
Intellectual Property
Information Collection

## Conclusion
