# TOURNAMENT RESULTS
***
### Introduction
This project is about developing a database schema in PostgreSQL to store the game matches between players. Also, Developed Python module to rank the players and pair them up in matches in a tournament.
### Features
* Written in Pyhton
* Install Vagrant and VirtualBox
### What's included
```
Tournament/
  |-- tournament.py
  |-- tournament.sql
  |-- tournament_test.py
```

### Library Requirement:
psycopg2, build of vagrant from UDACITY

### Instruction:
* Install Vagrant and VirtualBox 
* Clone this repository
* Launch the Vagrant VM
   * If you are new to vagrant and virtual box,
    1. After downoading vagrant, opent terminal and cd to the vagrant directory
    2. Then type `vagrant up`
    3. And type `vagrant ssh`, you should be inside virtual machine *
* Edit table definitions in a file (tournament.sql), if you want to make changes in database
    * To add this database in psql, inside the open terminale from above step *, type `psql`
    * Then type \i tournament.sql
* Edit Python functions of an API (tournament. py)
* Run a test suite to verify your code (tournament_test.py)
   * Run this test by typing `python tournament_test.py` in terminal

### File description:
**`tournament.py`**
This is the main project API file, which has all the function defined to connet to the database, request or submit a query  
**`tournament.sql`**
This file is the definition of all tables and views  
**`tournament_test.py`** 
This is a unit test script to test the tournament. py
