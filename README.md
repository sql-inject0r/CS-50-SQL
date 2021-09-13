### to see all the tables - 
.tables 

### to see the contents of the fight - 
SELECT * FROM flights;


### to insert contents into table - 
INSERT INTO flights (origin,destination,duration) VALUES ("Moscow","Srinagar",200);
INSERT INTO flights (origin,destination,duration) VALUES ("Moscow","mumbai",300);
INSERT INTO flights (origin,destination,duration) VALUES ("vladivastok","new delhi",440);
INSERT INTO flights (origin,destination,duration) VALUES ("srinagar","tokyo",500);

### to make it look more presentable - 
sqlite3>.mode columns
sqlite3>.headers yes
sqlite3>.tables

### to select certain elements from tables - 
SELECT * FROM flights WHERE origin == "Moscow"
