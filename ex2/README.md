# Exercise 2 - Reading a CSV and data importing

**Difficulty:** 2/10

This exercise will dive further into CSV handling and introduce database interactivity.

### Scenario

Using the test user data file from exercise 1 you must import this data into an SQLite database.

This database does not exist so you will need to create it.

### Areas covered

- File reading
- CSV handling
- Database connectivity
- Database drivers

### Expectations

- The database columns should be in snake case and contain an auto increment ID column.
- Your program should work against a fresh database only. Truncating may be required.

### Tips

- You can use an ORM or SQL utility package; or use the native database/sql package to understand how it really works.

### Reading Materials

- [package/sql](https://golang.org/pkg/database/sql/)
- http://go-database-sql.org/
