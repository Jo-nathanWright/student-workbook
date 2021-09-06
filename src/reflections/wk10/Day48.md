# Day 48 -  Welcome to SQL

## Daily Questions

- In a SQL table, what is the difference between information in a row and information in a column?
  - The infomation in a column is always going to be for the same value type, such as name or id, while the rows are the whole object, such as a person.

- Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
  - CREATE TABLE characters(
    id int NOT NULL,
    description VARCHAR(255) NOT NULL,
    age int
);

- What is the difference between the following statements:
  ```
    DELETE FROM table_name; - Removes rows from tables
    DROP TABLE table_name; - Deletes entire tables
  ```
## Morning Challenge
[ArtistApi](https://github.com/Jo-nathanWright/ArtistWarmup)

## Afternoon Challenge
[A Knights Tale](https://github.com/Jo-nathanWright/KnightTale)