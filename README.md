create database <DATA_BASE_NAME>;
drop database <DATA_BASE_NAME>;
\q ==> Quit From Psql shell
\c ==> Connect to database that you created
CREATE TABLE STUDENT(id BIGSERIAL PRIMARY KEY, name TEXT);
DROP TABLE STUDENT;
INSERT INTO STUDENT (NAME) VALUES('ALEX'),('JAMILA');
SELECT * FROM STUDENT;
