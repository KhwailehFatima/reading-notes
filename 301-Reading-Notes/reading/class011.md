# [SQL VS No-SQL](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

### Fill in the chart below with five differences between SQL and NoSQL databases:

  	 
 <table>
    <tr>
        <td>SQL</td>
        <td>No SQL</td>
    </tr>
    <tr>
        <td>called rational database
        </td>
        <td>called non-rational database</td>
    </tr>
    <tr>
        <td>table based database</td>
        <td>document based</td>
    </tr>
    <tr>
        <td>predefined schema</td>
        <td>dynamic schema for unstructured data</td>
    </tr>
    <tr>
        <td>vertically scalable </td>
        <td>horizontally scalable</td>
    </tr>
    <tr>
        <td>uses SQL ( structured query language ) for defining and manipulating the data, which is very powerful. </td>
        <td>queries are focused on collection of documents.</td>
    </tr>
    <tr>
        <td> examples: MySql, Oracle, Sqlite, Postgres and MS-SQL</td>
        <td>examples: MongoDB, BigTable, Redis, RavenDb, Cassandra, Hbase, Neo4j and CouchDb</td>
    </tr>
    <tr>
        <td> SQL databases are good fit for the complex query intensive environment</td>
        <td> not good fit for complex queries</td>
    </tr>
    <tr>
        <td> not best fit for hierarchical data storage</td>
        <td> fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data.</td>
    </tr>
    <tr>
        <td> best fit for heavy duty transactional type applications</td>
        <td> transactions purpose, it is still not comparable and sable enough in high load and for complex transactional applications</td>
    </tr>
    <tr>
        <td>Excellent support are available for all SQL database from their vendors</td>
        <td> some NoSQL database you still have to rely on community support</td>
    </tr>
    <tr>
        <td> emphasizes on ACID properties ( Atomicity, Consistency, Isolation and Durability)</td>
        <td> follows the Brewers CAP theorem ( Consistency, Availability and Partition tolerance)</td>
    </tr>
</table>
 	 

## What kind of data is a good fit for an SQL database?
If your data is highly structured and associations among the program entities are clearly defined.
## Give a real world example.
for instance, if you are developing a point of sale system where you need to store customer orders and product records
## What kind of data is a good fit a NoSQL database?
large data with simple schema
## Give a real world example.
Games
## Which type of database is best for hierarchical data storage?
noSQL
## Which type of database is best for scalability?
NoSQL, earning it's name by being “not only SQL” makes it easier to store all different types of data together. It's used for its flexibility and therefore speed and scalability in managing large volumes of data.

# [Source](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
## What does SQL stand for?
Structured Query Language

## What is a relational database?
database which works with certain assumptions
## What type of structure does a relational database work with?
Tables - like a storage container
## What is a ‘schema’?
## What is a NoSQL database?
 called MongoDB which stands for Humongous because it can store lots and lots of data in a very effiecient way.
## How does it work?
we have data bases and we have collections instead of tables and inside it we have documents (rows and tables) they look like JSON and they dont have to use the same schema, we can have multiple documents in one collection which have different fields.
## What is inside of a Mongo database?
## Which is more flexible - SQL or MongoDB? and why.
MongoDB
## What is the disadvantage of a NoSQL database?
You could have duplicated data, it needs to be updated