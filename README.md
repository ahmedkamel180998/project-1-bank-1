# Bank Management System [Procedural Programming]
This C++ project is a simple console-based Bank Management System. It allows users to manage client accounts, including adding new clients, updating details, deleting accounts, and viewing a list of all clients. The client data is stored in a text file to ensure persistence between sessions.

## Table of Contents
- [Project Information](#Project-Information)
- [Live Demo](#Live-Demo)
- [Features](#features)
- [How It Works](#how-it-works)
- [Project Flow](#Project-Flow)

## Project Information
This C++ simple console-based Bank Management System project was created at the end of the [7th course](https://programmingadvices.com/p/algorithms-and-problem-solving-level-3) from the Roadmap for General Foundation in Programming @ [Programming Advices](https://programmingadvices.com/).

## Live Demo
https://github.com/user-attachments/assets/8e7707f5-044a-4a4b-bd98-c34e7ed88bde

## Features
- **Client List:** Display a list of all clients, including account number, pin code, name, phone, and account balance.
- **Add New Client:** Add new client information such as account number, pin code, name, phone, and balance.
- **Delete Client:** Remove a client from the system by account number.
- **Update Client Info:** Modify the details of an existing client.
- **Find Client:** Search for a client by account number and display their details.
- **Data Persistence:** All client information is saved to and retrieved from a file (`clients.txt`).

## How It Works
1. **Menu Interface:** The system presents a simple menu with options to view clients, add new ones, delete or update client information, or find a client by their account number.
2. **Client Operations:** Based on the user's selection, the system performs operations like displaying client data, adding new entries, or making updates.
3. **File Handling:** All client records are stored in `clients.txt`, ensuring data is saved after the program ends and can be reloaded when it restarts.
4. **User Input:** The user interacts with the program by inputting data such as account numbers, pin codes, and other client details via the console.

## Project Flow
1. **Main Menu:** Upon running the program, the user is presented with options to:
   - View the list of clients
   - Add a new client
   - Delete a client
   - Update a client's information
   - Find a client by account number
   - Exit the program
2. **File Interaction:** When clients are added, updated, or deleted, the changes are reflected in the `clients.txt` file.
3. **Client Data:** Each client record contains an account number, pin code, name, phone number, and balance, which are managed through the system's options.

## File Structure
`main.cpp`: The main program file containing the source code for the Bank Management System.
`clients.txt`: The data file where client information is stored. This file is created automatically when the program runs.
