0.Install MySQL
First things first, let’s get MySQL installed on both your web-01 and web-02 servers.
1. Let us in!
we need you to create a user and password for both MySQL databases which will allow the checker access to them.

Create a MySQL user named holberton_user on both servers
2. If only you could see what I've seen with your eyes
Create a database named tyrell_corp.
Within the tyrell_corp database create a table named nexus6 and add at least one entry to it.
3. Quite an experience to live in fear, isn't it?
create a new user for the replica server.
4. Setup a Primary-Replica infrastructure using MySQL
Setup replication for the MySQL database named tyrell_corp
5. MySQL backup
Requirements:

The MySQL dump must contain all your MySQL databases
The MySQL dump must be named backup.sql
The MySQL dump file has to be compressed to a tar.gz archive
This archive must have the following name format: day-month-year.tar.gz
The user to connect to the MySQL database must be root
The Bash script accepts one argument that is the password used to connect to the MySQL database
