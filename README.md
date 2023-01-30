## Museum-Database-ENSF300
This repo contains the CSV files and python script for the final project of ENSF 300, completed in December 2022. In the future, I will fully implement the user access, granting the appropriate priveledges to users.

## Program Requirements
To run the Program, you must import the following libraries through the terminal if you have not already:
1. mysql.connector
2. tabulate

The user must also access the database with their local MySQL server password and username when promtped.

## Running the Program
The Program implements three different user interfaces, the guest, user, and admin, each with their own access level to the database. The Python interface allows for the retrieval and manipulation of data within the database. Exception handling is implemented for incorrect Query inputs and failed connection attempts to the database. Retrieved data is printed neatly in the terminal using the "tabulate" library.
