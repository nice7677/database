# RDBMS

### RDB (Relational Database)

- 데이터를 2차원의 테이블 형태로 표현한다.
- 자연스럽고 직관적으로 이해하기 쉽다.
- 프로그래밍 언어를 몰라도 데이터 조작이 쉽다.

### RDBMS (Relational Database Management System)

- RDB를 생성, 수정하고 관리하는 Management System
- MySQL, Oracle, PostgreSQL, MariaDB, MS SQL

DBMS와 RDBMSD의 차이점

|DBMS|RDBMS|
|------|---|
|DBMS stores data as file.|RDBMS stores data in tabular form.|
|DBMS stores data as file.|RDBMS stores data in tabular form.
|Data elements need to access individually. |Multiple data elements can be accessed at the same time.|
|No relationship between data.|Data is stored in the form of tables which are related to each other.|
|Normalization is not present.|Normalization is present.|
|DBMS does not support distributed database.|RDBMS supports distributed database.|
|It stores data in either a navigational or hierarchical form.|It uses a tabular structure where the headers are the column names, and the rows contain corresponding values.|
|It deals with small quantity of data.|It deals with large amount of data.|
|Data redundancy is common in this model.|Keys and indexes do not allow Data redundancy.|
|It is used for small organization and deal with small data.|It is used to handle large amount of data.|
|It supports single user.|It supports multiple users.|
|Data fetching is slower for the large amount of data.|Data fetching is fast because of relational approach.|
|The data in a DBMS is subject to low security levels with regards to data manipulation.|There exists multiple levels of data security in a RDBMS.|
|Low software and hardware necessities.|Higher software and hardware necessities.|
|Examples: XML, Window Registry, etc.|Examples: MySQL, PostgreSQL, SQL Server, Oracle, Microsoft Access etc.|

참조 [Difference between RDBMS and DBMS](https://www.geeksforgeeks.org/difference-between-rdbms-and-dbms/)

### Transaction

트랜잭션이란 복수의 쿼리를 한 단위로 묶은것을 의미한다.

트랜잭션에는 4가지의 특성으로 정의되며 앞글자를 따 `ACID 특성`이라 한다.

 - Atomicity(원자성)
: 트랜잭션의 작업이 부분적으로 실행되거나 중단되지 않는 것을 보장하는 것이다.
(불가능한 최소의 단위인 하나의 원자처럼 동작한다는 의미이다.)

 - Consistency(일관성)
: 미리 정의된 규칙에서만 수정이 가능한 특성을 의미한다.
(숫자 컬럼에 문자열값이 저장이 안되도록 보장한다.)

 - Isolation(고립성)
: 트랜잭션 수행시 다른 트랜잭션의 작업이 끼어들지 못하도록 보장하는 것이다.

 - Durability(영구성)
: 성공적으로 수행된 트랜잭션은 영원히 반영이 되는 것을 의미한다.
(한번 반영(commit)된 트랜젝션의 내용은 영원히 적용된다.)

참조 [SQL vs NoSQL](https://velog.io/@thms200/SQL-vs-NoSQL)

