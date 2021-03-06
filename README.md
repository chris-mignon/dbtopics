# Database Topics

## final report
`Very Important Notice May 16, 2020`
Please write a final report about database and distributed system, this final report as one part of final grade is very important.
Please Submit this final report before June 20, 2020.

## Lectures

#### The Relational Theory Design: Normal Form
[The Relational Theory Design](./lectures/lecture008DbSystemBCNFR6.pdf)

#### The E-R Model
[E-R Model](./lectures/lecture007DbSystemERModelR6.pdf)

#### Relational Algebra & Calculus
[Relational Algebra & Calculus](./lectures/lecture006DbSystemRelationalAlgebraCalculus.pdf)

#### The SQL Language
[SQL Language](./lectures/lecture003DbSystemSQL1basicR6.pdf)

#### Lecture 8: The Paxos Consensus
[The The Paxos Consensus](./docs/lamport-paxos.pdf)

### Lecture 7
The Byzantine Generals Problem

### Lecture4~6
SQL Languages

### Lecture3
[Relational Model](./lectures/DbSystemRDbModel.pdf)

### Lecture2
[Virtual Machine & MySQL DB installation](./docs/DbSystemLabEnvForMysql.pdf)

### Lecture1
Introduction & CAP theorem

## Tasks
`Write a report for each task and send me email.`<br/>
**Current Task:** Task4<br/>
### Task4
Read the following paper and finish one report: write a report for presenting all the steps using OM(3) and comment the paper. <br/>

Lamport, et al. "The Byzantine Generals Problem." Acm Transactions on Programming Languages & Systems 4.3(1982):382-401.


### Task3
[Task3](./tasks/task3):Design full relational schemas for movies <br/>
[Datasets](https://github.com/albertleecn/MovieLensDatasets) <br/>

References: <br/>
[F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19.](./docs/harper_TheMovieLensDatasets_HistoryandContext_tiis2015.pdf) <https://doi.org/10.1145/2827872> 

### Task2
[Task2](./tasks/task2): Design a schema for movies, and import all data from movies.csv, and The Requirements are as follows: <br/>
1. Data File is in tasks/task2: Movies Data File Structure (movies.csv)
2. retrieve the number of movies in each genre
3. reverse engineer the new schema

### Task1
Task1: Install mysql server and import the test data which is provided by "Database System Concepts 6th Edition", and The Requirements are as follows: <br/>
1. create a database schema in mysql, the new schema's name is your student id
2. import the test data (DDL_createtbwithpredrop & largeRelationsInsertFile)
3. retrieve the number of students in each department
4. reverse engineer the new schema



## Readings
`Please read them and we will discuss later.`

### Google File System & Bigtable
[Ghemawat, S., H. Gobioff, and S.T. Leung, The Google file system. Acm Sigops Operating Systems Review, 2003. 37(5): p. 29-43.](./docs/GoogleFileSystem_ghemawat.pdf)

[Chang, F., et al., Bigtable:A Distributed Storage System for Structured Data. Acm Transactions on Computer Systems, 2008. 26(2): p. 1-26.](./docs/BigtableADistributedStorageSystemforStructuredDatachang.pdf)

### CAP
[Gilbert, S. and N. Lynch, Perspectives on the CAP Theorem. Computer, 2011. 45(2): p. 30-36.](./docs/Brewer_PerspectivesontheCAPTheorem.pdf) 


## Resources

### Books

Avi Silberschatz, Henry F. Korth, S. Sudarshan. **Database System Concepts 6th Edition**. McGraw-Hill, ISBN 0-07-352332-1


### Test Data for MySQL
`These files are in task1:` <br/>
[DDLcreatetbwithpredrop.sql](./tasks/task1/DDLcreatetbwithpredrop.sql)<br/>
[largeRelationsInsertFile.sql](./tasks/task1/largeRelationsInsertFile.sql)