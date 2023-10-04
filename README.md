# SQL

# Build docker
Switch to administrator
```
su root
```
View the OS version
```
cat /etc/redhat-release
```
Check whether docker is created
```
docker --version 
```
OR
```
docker -v
```
Install docker
```
sudo yum install -y yum-utils
```
```
sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
```
```
sudo yum install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
```
When the 'Complete!' display, it has been completed.

```
sudo systemctl start docker
```
```
sudo docker run hello-world
```
Check whether docker is created
```
docker --version 
```
It will show as following
```
Docker version 24.0.6, build ed223bc
```
# SQL  Basic knowledge
Database： a container to keep structured data
Database Management System(DBMS): a database software to create or manipulate data
Schema: a logical structure of a database, recording database info and table layout info.

Column: a field in a table
Row: a record in a table
## A table consists of one or more columns. 
## A table stores data by rows.

SQL (Structured Query Language): a language specifically used to communicate with databases.
MySQL: One of the DBMS based on Client-server software 
Relation: MySQL < DBMS based on Client-server software (Oracle, Microsoft SQL Server) < DBMS
## SQL not used in specified a DBMS = almost all DBMS support SQL
## SQL syntax is not quite the same between any two DBMSs.
