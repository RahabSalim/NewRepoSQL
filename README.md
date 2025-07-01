SELECT TOP (1000) [ID]
      ,[name]
      ,[email]
  FROM [softdatabases].[dbo].Student2
  SELECT * FROM Student2
WHERE name = 'Rahab';
update student_data  set name='rahab' where id=3


SET IDENTITY_INSERT Student2  ON;
INSERT INTO Student2  ( ID, Name, email)
VALUES ( 200 ,'rahab', 'rahab47382');
SET IDENTITY_INSERT Student2  off;

DELETE FROM student_data
WHERE id = 2;

SELECT * FROM student_data;
