# Exercise 1 - Creating and writing a CSV file

**Difficulty:** 1/10

This exercise will dive into file and CSV handling.

### Scenario

You have been tasked to create test user data for another team in the form of a CSV file.

The test data requires the following fields:
- Email
- First name
- Last name

The test data should be randomised and realistic so that each time this program is run a fresh CSV is generated.

The generated test file to contain 10000 records and should contain a header row for the columns.

### Expectations

Your program should:
- Create a file in the current directory.
- Data should be random and realistic. Dummy data such as "abc" will not suffice.
- Each time the program is run it should create a new file. 

### Tips

Don't reinvent the wheel. You may use third party libraries to fake your data.

Helpful packages:
- encoding/csv
- os

### Reading Materials

- https://gobyexample.com/writing-files
- https://gobyexample.com/defer
- https://github.com
