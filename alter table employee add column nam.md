alter table employee add column name varchar(250);

**add multiple colimn at the end of the table:**

alter table employee add column age int, add column salary decimal(8,2);

**add a column at specific postion**

alter table employee add column email varchar(250) after name;

**add a column at a first position**

alter table employee add column id int first;

**change position of a column in the table**

alter table employee modify column xyz int after salary;

**rename column name in the table**

alter table employee rename column xyz to exp;

**add primary key:**

alter table employee add primary key(id);

alter table employee modify column name varchar(250) not null;

alter table employee modify column  age int not null;

alter table employee modify column email varchar(250) unique;

alter table employee modify column salary decimal(8,2) not null default 0.0;

alter table  employee modify column salary decimal(8,2) not null;



rename table employee to employees;

alter table employees drop column exp;

drop table employees;

