show databases;
create schema tajholsel;
use databasename;
create table user (id int(10),name varchar(90),email varchar(90), PRIMARY KEY (id)) ;
insert into user values(1,'rafe','mrrafe11@gmail.com');
select * from user;
select id,name from user;

INSERT INTO `tajholsel`.`user` (`id`, `name`, `email`) VALUES ('2', 'farman', 'farman@gmail.com');
