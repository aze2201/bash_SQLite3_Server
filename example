# bash_SQLite3_Server
SQLite Server over TCP


put this script to any folder where you want to create SQLite database and execute below command.

nc -l -p 6667 -e ./expect.exp -k

# EXAMPLE:

[root@xxxx ~]# telnet localhost 6667
Trying 127.0.0.1...
Connected to localhost.
Escape character is '^]'.
spawn sqlite3 example.db
SQLite version 3.7.17 2013-05-20 00:56:22
Enter ".help" for instructions
Enter SQL statements terminated with a ";"
sqlite> 
sqlite> attach database 'bb.db' as b ;
attach database 'bb.db' as b ;
sqlite> 
sqlite> create table b.tbl ( clm1 text );
create table b.tbl ( clm1 text );
sqlite> 
sqlite> insert into b.tbl values ('fake data');
insert into b.tbl values ('fake data');
sqlite> 
sqlite> select * from b.tbl;
select * from b.tbl;
fake data
sqlite> 
sqlite> 
