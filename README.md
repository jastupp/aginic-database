#Database

This is a place holder project. The database and table 
are created within 'userData' in the cloud formation script.
The table created is ServerTasks. 

```sql
create table <database>.ServerTasks (
	id int not null AUTO_INCREMENT,
    URL varchar(100) not null,
    state ENUM ('WAITING', 'PENDING', 'SUCCESS', 'FAILURE'),
    CONSTRAINT SERVER_TEST_PK primary key (id)
);
