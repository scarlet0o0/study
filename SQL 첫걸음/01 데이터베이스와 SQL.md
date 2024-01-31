# 데이터베이스와 SQL

<br/>

<br/>

##  DBMS(Database management System)

DB 에서 데이터를 꺼내 이를 효율적으로 관리하는 소프트웨어

- 생산성
- 기능성
- 신뢰성

<br/>

### SQL

 관계형 데이터베이스에서 데이터를 관리하기 위해 사용되는 언어

- DML(Data Manipulation Language) : 데이터베이스에서 새롭게 데이터 추가, 갱신, 업데이트 등 데이터를 조작할때 사용된다. (select, insert, update, delete)
  - 테이블 안의 데이터 하나하나를 추가하고 삭제하고 수정하는 것.
- DDL(Data Define Language) : 데이터 베이스 객체 만들거나 삭제하는 명령어 (create, alter, drop, rename)
  - 테이블을 생성하고, 테이블 내용을 변경하고, 테이블을 없애버리는 것.
- DCL(Data Control Language) : 데이터를 제어하는 명령어 트랜젝션 제어, 데이터 접근권한 제어 명령 등등 (commit, rollback, grant, revoke)
  - 보안/무결성/회복/병행 제어 등을 정의하는데 사용한다. 데이터 관리 목적.

<br/>

###  RDBMS의 종류

1. Oracle
2. PostgreSQL
3. MySQL