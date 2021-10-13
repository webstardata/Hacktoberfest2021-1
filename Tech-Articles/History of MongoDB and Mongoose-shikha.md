
=======================================================

Article Title: History of MongoDB and Mongoose
Author Name: Shikha Rai
Author Profile: https://github.com/srai0109
Date: 13th Oct 2020

=======================================================

A Little Historical Context

Databases fall into several different categories. The earliest databases, up through the mid-1980’s, were so-called CODASYL databases. These organized data into records and related occurrences of different record types to one another using hashes to form a network. Although generally efficient CODASYL-style databases, like IDMS from Cullinet Software and IMS from IBM the context and navigation required that the application bet exposed to the physical relationship between records.
When new requirements surfaced for applications to combine data in new ways the database administrator was required to create the new physical relationship to support the requirement, all before application development could begin. This could be as simple as merely defining the new relationship, but it always required careful planning and often resulted in extensive database reorganization.
Exposing this level of physical database structure onto the applications had the impact of increasing their complexity. In addition, the embedded dependency of the physical database schema into the application meant that database changes required extensive application modification and testing.
For example, a common relationship is that of a parent and child where a parent record occurrence owns one or more occurrences of child records. This type of relationship is used to maintain Savings Account records for an individual and connect them with individual Transaction records representing activity against it.
The following pseudo-code shows how an application accesses the records for this type of relationship in a CODASYL database, in this case CA-IDMS:

```

INITIALIZE ACCOUNT
Move account number ‘111111’ to the Account field in record
OBTAIN CALC ACCOUNT
Do-Forever
  OBTAIN NEXT Transaction WITHIN Account-Transaction
  If no more Transaction records then BREAK
  If transaction-type = ‘deposit’ then
    <<do something with the data>>
  End-If
End-Do

```

In the early 1980’s a new type of database based on the Structured Query Language (SQL) began to take hold. The main advantage of a SQL database had over a CODASYL database is that manipulating data was simpler since data in a SQL database is organized relationally rather than physically. Application logic was based on the concept that data would be returned in a tabular format consisting of rows and columns and data from different tables could be aggregated based on the shared data values in tables rather than on physical relationships. This meant that application programs became simpler to write and maintain.

```

SELECT account-no, transaction-date, transaction-type, 
       transaction-amount
  FROM ACCOUNT, TRANSACTION
  WHERE account-no = ‘111111’
    AND transaction-account-no = account-no
    AND transaction-type = ‘deposit’
END-SELECT

```

The SQL example above demonstrates the power of SQL. Rather than requiring navigational logic in the application to traverse the database, data is retrieved based on a shared key value between the Account and Transaction. Namely, the account number. The SELECT directive results in the database management system returning a the exact set of data required by the program.
With the rise of the Internet in the late 1990’s applications shifted from dealing strictly with highly structured data, like accounts and transactions, to also dealing with unstructured data like plain text. Just as important was the fact that applications needed to be able to quickly adapt to new requirements and to scale to support transactional volumes which far exceeded what was seen in older mainframe and distributed computing environments.
NoSQL database were developed to provide an environment that supported change without requiring radical reengineering of the underlying data model, high volumes of data, and an architecture that was easy to scale.


