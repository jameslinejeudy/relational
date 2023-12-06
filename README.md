In-Memory Database with Transaction Support
This project implements an in-memory key-value database with transaction support in C++. It allows users to perform operations like beginning a transaction, putting values, getting values, committing changes, and rolling back transactions.

Table of Contents
Overview
Usage
Building and Running
Future Improvements
Overview
The database implemented here utilizes an in-memory data structure to store key-value pairs. It provides transactional support allowing changes made within a transaction to be committed or rolled back.

Usage
The InMemoryDB class provides the following functionalities:

begin_transaction() - Starts a new transaction.
put(key, value) - Inserts or updates a key-value pair within a transaction.
get(key) - Retrieves the value associated with a key.
commit() - Applies changes made within a transaction to the main state.
rollback() - Aborts changes made within a transaction and reverts to the state before the transaction started.


Clone this repository.
Navigate to the project directory.
Compile the code using your preferred C++ compiler.
Execute the compiled binary.
Example:

bash
Copy code
g++ main.cpp -o main
./main

Support for Multiple Data Types: Extend the database to support a wider range of data types.
Concurrency Handling: Implement mechanisms to handle concurrent transactions.
Persistence: Add functionality to persist the database state to disk.
Error Handling: Enhance error messages and handling for different scenarios.

Contributors
Jamesline Jeudy - Main Contributor
