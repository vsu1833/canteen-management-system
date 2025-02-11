Canteen Management System
Canteen Management System is a console-based C++ application that simulates a canteen's operations. It offers two modes:

Customer Mode: Browse the menu, select items, apply discount coupons, and generate an invoice.
Admin Mode: Password-protected editing of the food menu (add, remove, or replace items) and view overall sales records.


Features
Customer Experience:
Display a dynamically managed menu using linked lists.
Let customers select items by serial number and quantity.
Apply discount coupons (e.g., GET10, FREE20) during checkout.
Generate an invoice and record sales data.

Admin Functions:
Secure access via a password (7890).
Edit the menu by adding items at a specific position, at the beginning, or at the end.
Remove or replace existing menu items.
View overall sales records stored in salesdata.dat.

Technical Aspects:
Uses dynamic memory allocation (via malloc, calloc, and realloc) and linked lists.
Implements file I/O for recording sales transactions.
Utilizes system calls (like system("cls")) for console management (Windows-specific).

Requirements :
A C++ compiler (e.g., g++, Visual Studio)
Windows OS is recommended (due to Windows-specific commands)
Installation and Execution
Clone or download this repository.
Open a terminal/command prompt in the project directory.

Compile the code:
bash
Copy
Edit
g++ -o CanteenManagementSystem main.cpp
Run the executable:
bash
Copy
Edit
./CanteenManagementSystem
(On Windows, you might need to run CanteenManagementSystem.exe)

File Structure
main.cpp: Contains the full source code.
salesdata.dat: File where sales records are stored (generated during runtime).

Future Enhancements
Improve cross-platform compatibility by removing Windows-specific functions.
Enhance input validation and error handling.
Develop a graphical user interface (GUI) for a better user experience.
Implement stronger security measures for admin access.

License
This project is open source. Contributions and suggestions are welcome!

