[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)
![Misk Logo](https://i.ibb.co/KmXhJbm/Webp-net-resizeimage-1.png)


# Relational Databases SQL

Fork and clone this Repo

# Objectives

- Practice creating an SQL database
- Practice seeding an SQL database
- Practice using SQL queries to retrieve or manipulate information in an SQL database

## Schema

On your MySQLWorkbench:

Create a new Schema and call it ```library```

A schema has been provided with the following structure:

* authors
  * id
  * name          TEXT
  * nationality   TEXT
  * birth_year    INTEGER

* books
  * id
  * title             TEXT
  * publication_date  INTEGER
  * author_id         INTEGER (Foreign key)


Load the schema into your DB:

On your MySQLWorkbench:
File-> Open SQL Script -> choose ```library.sql```

Execute the file

## Seed

Load the given seed file into your db. Take a look at it, and note
how authors and books are related.

File-> Open SQL Script -> choose ```seed.sql```

## Exercises

There are two exercises:

* [Basic Queries](basic_queries.sql) - SELECT, INSERT, UPDATE, DELETE
* [Advanced Queries](advanced_queries.sql) - JOINS
