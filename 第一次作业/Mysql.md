# Mysql

## 1.安装

初始化并得到初始密码，太复杂了，改了一个。

## 2.加载数据库

输入mysql -u root -p后，输入初始密码，开始加载。

## 3.创建数据库

输入create DATABASE RUNOOB;后创建了一个数据库

## 4.创建表

CREATE TABLE IF NOT EXISTS runoob_tbl(
    -> runoob_id INT UNSIGNED AUTO_INCREMENT,
    -> runoob_title VARCHAR(100) NOT NULL,
    -> runoob_author VARCHAR(40) NOT NULL,
    -> submission_date DATE,
    -> PRIMARY KEY ( runoob_id )
    -> )ENGINE=InnoDB DEFAULT CHARSET=utf8;

## 5.插入数据

INSERT INTO runoob_tbl
    -> (runoob_title, runoob_author, submission_date)
    -> VALUES
    -> ("学习 PHP", "菜鸟教程", NOW());

……

插入了三项数据

## 6.查询数据

使用select * from runoob_tbl;语句来查询数据

## 7.删除表删除数据库

输入DROP TABLE runoob_tbl删除表；

输入drop database RUNOOB;删除数据库；