## User stories:
```
As a user
So that I can go to web sites I saved
I would like to see a list of bookmarks
```
## Domain Model

![Bookmark Manager domain model](./domain_model.jpg)

## How to use
### To set up the project

Clone this repository and then run:

```
bundle
```
### To setup the database:
1) Connect to psql;
```
2) Create the database using the psql command CREATE DATABASE bookmark_manager;
```
3) Connect to the database using the pqsl command \c bookmark_manager;
```
4) Run the query from the file 01_create_bookmarks_table.sql to set up the appropriate tables


