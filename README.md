## Build with

`docker build -t tree .`

## Run with

`docker run -d -p 8800:8800 tree`

## Exec into the container and create a project

`tspawn new blogapp`

## Create a sqlite database file
`sqlite3 db/blogdb`

## Then create the tables with
`CREATE TABLE blog (id INTEGER PRIMARY KEY AUTOINCREMENT, title VARCHAR(20), body VARCHAR(200), created_at TIMESTAMP, updated_at TIMESTAMP, lock_revision INTEGER);`

## Quit sqlite

`.quit`