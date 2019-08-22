# online Book Shop Portal
## Tables
### Table 1: books

| id | bookname| price| category |year|
|-- |--| --| -- |--|
| 101 |Core Java| 200| technical|2019|
| 102 |romoo juliet| 100| story|1999|



####List all books

select*from books;

##### list all books in descending order

select * from books order by price desc;

###### list the books within the given range;

select*from books name where price between 100 and 500;

