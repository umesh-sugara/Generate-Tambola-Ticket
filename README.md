
# Tambola Tickets Generator

This is a code for a Tambola Ticket Generator with the backend engine of Microsoft SQL Server.
![image](https://github.com/umesh-sugara/Generate-Tambola-Ticket/assets/73294581/4be1fe57-8636-4934-84f8-705c79d89861)



## Requirements.txt
Following are the Python libraries used:
  - flask (Flask, jsonify, request)
  - pandas
  - json
  - pyodbc
  - random
  - copy
  - numpy

Database Used:
  - Microsoft SQL Server (SSMS)

## Tasks

### 1) Create “N” New Tambola Sets:
- 1 Tambola set consists of 6 tickets.
-    The numbers 1 to 90 are used once only.
-    In the first column are the numbers 1 to 9, the second column has numbers 10 to 19, etc, all the way to the 9th column which has numbers 80 to 90 in it.
-   Every row must have exactly 5 numbers in it.
-   In a specific column, numbers must be arranged in ascending order from top to bottom
-   Each column must have at least 1 number.
-    All the numbers 1 to 90 are used only once in each set of 6 tickets.
-   Blank Cell fill by zero
-    Each ticket must be unique and not exist in the database.

#### Tambola Tickets with Setid = 4
![image](https://github.com/umesh-sugara/Generate-Tambola-Ticket/assets/73294581/360b8627-8d5f-4160-86de-b5b092b91d71)


###### URL used: http://127.0.0.1:5000/database/fetch_top_60_tickets
- Note: It brings top 60 tickets from the database
![image](https://github.com/umesh-sugara/Generate-Tambola-Ticket/assets/73294581/35218e39-a0e7-4efd-81fc-f8550d1bd40b)


### 2) Make a GET URL to return the tambola tickets saved in database, with pagination.

###### URL used: http://127.0.0.1:5000/database/fetch_all_tickets?page=2&size=50
- Note: It brings data after getting Page Number and Page Size from the user.
![image](https://github.com/umesh-sugara/Generate-Tambola-Ticket/assets/73294581/ebba2c59-9e3d-4210-a853-a711f507a542)


## Feedback
If you have any feedback, please reach out at umeshsugara9@gmail.com



