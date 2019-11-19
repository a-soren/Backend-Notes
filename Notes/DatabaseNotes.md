# DB Intro notes

## Expectations
-this week is about using a database, not managing
-self study is necessary
-we use SQLite to introduce Relational Databases and SQL
-using SQLite removes the complexity of installing and managing a database server.

## What We Cover
-an introduction to what Relational Databases and RElational DB Management Systems are
-an introduction to SQL
-managing data using SQL
-managing data using a Query Builder called Knex
-working with multiple tables
-designing the structure (called Schema) for realtional database
=using SQLite Stuidio ( a graphical tool) to interact with a SQLite database

## what we don't cover
-installing a DB server
-db servers admin (totally different career)


a Relation is a Table

Relational database store data in Tables

a table has a collection of rows (record).
a row has many columns (fields).

A table (collection of tables) is where resources are stored.

## SQL= Structured Query Language
-manage (CRUD) data <<<we do this>>>
-manage the Database schema
-manage objects inside the DB
-manage the DB server. (security, monitoring, performance, analysis)


## Realtional DB Management System (RDBMS)
-software to manage Realtional databases
--SQLite, postgreSQL, mySQL, MS SQL server, oracle, MariaDB

## Using a realtional DB from a node.js API

[client] http(= JSON =) [API] proprietary protocol(= SQL =) [DBMS server]

a **query builder (we use Knex)** translates between the API (JS for node.js) language and SQL.

[API] == Knex == DB driver(SQLite3) == [RDBMS]

an Object Relational Mapper (ORM like SQLite and Bookshelf) is another way to connect an API to a RDB.

ORM are more complex because they do more than a simple query builder. 