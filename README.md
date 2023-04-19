# Agrivision4u-Assignment-190551-iitk
1. Install postgres sql
2. Open pg admin then write a query to create a table
CREATE TABLE users (
    id UUID NOT NULL,
    username TEXT NOT NULL UNIQUE,
    password TEXT NOT NULL,
    CONSTRAINT users_pkey PRIMARY KEY(id)
)
WITH (oids = false);

NOTE : make sure the name of the database is postgres or you can write your own .env file and config the data base in the .env file as 

PGHOST=<postgres_host>
PGPORT=<postgres_port>
PGDATABASE=<database_name>
PGUSER=<postgres_username>
PGPASSWORD=<postgres_password>

For example 

PGHOST=localhost
PGPORT=5432
PGDATABASE=postgres
PGUSER=postgres
PGPASSWORD=password

3. Then in the editor of your choice open the terminal and install the packages using npm install

4. Finally Run the application using node server.js from terminal of the editor.

For any query or if it is not working email at nikhilk@iitk.ac.in
