0.Install MySQL First things first, let’s get MySQL installed on both your web-01 and web-02 servers.
HOW TO INSTALL MYSQL 5.7
Touch signature.key
Copy the key here to your clipboard-https://alx-intranet.hbtn.io/rltoken/Zzs_TLRYjWWFxjJRArmFcQ
Add key to signature.key file and save then
sudo apt-key add signature.key
sudo sh -c 'echo "deb http://repo.mysql.com/apt/ubuntu bionic mysql-5.7" >> /etc/apt/sources.list.d/mysql.list'
sudo apt-get update
sudo apt-cache policy mysql-server
mysql-server:
Installed: (none)
  Candidate: 8.0.27-0ubuntu0.20.04.1
  Version table:
     8.0.27-0ubuntu0.20.04.1 500
        500 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 Packages
        500 http://security.ubuntu.com/ubuntu focal-security/main amd64 Packages
     8.0.19-0ubuntu5 500
        500 http://archive.ubuntu.com/ubuntu focal/main amd64 Packages
     5.7.37-1ubuntu18.04 500
        500 http://repo.mysql.com/apt/ubuntu bionic/mysql-5.7 amd64 Packages

Now install mysql 5.7
sudo apt install -f mysql-client=5.7* mysql-community-server=5.7* mysql-server=5.7*
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
