# sqlite

## 1.安装sqlite

安装后在cmd里输入sqlite3

## 2.创建数据库

直接用了.open textDB.db来创建数据库

## 3.创建表

输入CREATE TABLE COMPANY(
   ID INT PRIMARY KEY     NOT NULL,
   NAME           TEXT    NOT NULL,
   AGE            INT     NOT NULL,
   ADDRESS        CHAR(50),
   SALARY         REAL
);

## 4.删除表

DROP TABLE COMPANY;
