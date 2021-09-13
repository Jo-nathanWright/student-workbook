# Day 52 -  Relationships

## Daily Questions

- What is the difference between a primary key and a foreign key
  - Primary Keys are unique vaules. Foreign Keys are used to refernce other primary keys.
- What is an Alias?
  - A naming convention when caling to the database for a column on the table
- Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:
  SELECT p.*, d.* FROM doctors JOIN patients p ON p.id = d.patientId JOIN doctors d ON d.id = d.doctorId;

## Afternoon Challenge
[Contracted](https://github.com/Jo-nathanWright/Contracted)