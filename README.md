# mysql
database system: design, implementation and maintenance 14 edition 

# july 25, 12:37PM
started model all concepts references in mysql journey 

# Connect to the mysql server
```sh
sudo mysql -uroot -p
```
## Database Theory
Chapt02 Data Modeling

-One of the most vexing problems of database design is that designers, programmers,
and end users see data in different ways.

To avoid such failures,database designers must obtain a precise description of the data’s nature and many uses
within the organization.

Data Modeling require clear communication among Database Designer, Programmer and End User and eliminate communication gap. And define Entities, Relations, and Data transformations.

1. hierarchical model
2. network model
3. relational model
4. object-oriented model
5. object/relational model
6. emerging NoSQL data model

You will also learn about the use of the entity relationship diagram (ERD) as a data-modeling
tool

The first step in designing a database, refers to the process of creating a specific data model(1 out of 6 Data Models) for a determined problem domain.

***

## Database Practical

###### check on which host database is hosted

```sh
select @@hostname
```
###### View all databases hosted
```sh
show databases
```
