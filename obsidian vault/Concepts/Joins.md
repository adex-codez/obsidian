Joins is a sql construct that merges table together which have a relationship.


The general synthax for joins is as follows:
```
sql
select columns in the right or left table 
from table on the left join_type table on the right
on condition
```
where the table on the left is the table with the foreign key, the table on the left is the table referenced by the foreign key, join_type can be substituted with any join type, while after the on keyword which is where the condition will be placed which is most time a condition checking where the columns that exists in left and right table are equal.



The following are the types of joins:
## Inner Join

It joins the table on the left with the table on right and matches them up together based on whatever condition stated after the on keyword and if there is no relationship it discards the rows without the relationship.

## Left Join

when we use this join we get all the records in left table whether they have a relationship with the right table and merge it with all the records in the right table that have a relationship with the left table.

## Right Join

when we use this join we get all the records in left table that have a relationship with the right table and merge it with all the records in the right table that have a relationship or not with the left table.

