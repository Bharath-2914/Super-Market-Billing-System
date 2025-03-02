# Super-Market-Billing-System
# Super Market Billing System

## Overview
The Super Market Billing System is a simple console-based application written in C++. It allows users to add items to inventory, generate bills, and manage stock levels. The system stores inventory data in a text file and provides basic functionalities for adding items and processing customer bills.

## Features
- Add new items to the inventory with item name, rate, and quantity.
- Print bills based on customer purchases.
- Automatically update inventory after a sale.
- Simple text file handling for data persistence.

## Installation & Setup
1. Ensure you have a C++ compiler (like MinGW for Windows or g++ for Linux).
2. Clone this repository or download the source code.
3. Open a terminal or command prompt in the project directory.
4. Compile the program using:
   ```sh
   g++ -o billing_system billing_system.cpp
   ```
5. Run the program:
   ```sh
   ./billing_system
   ```

## Usage
1. When you start the program, you will see the main menu with options:
   - **Add Item**: Allows adding new inventory items.
   - **Print Bill**: Processes sales transactions.
   - **Exit**: Closes the application.
2. Follow the prompts to enter item details or purchase items.
3. The inventory file (`Bill.txt`) is automatically updated as items are added or sold.

## File Handling
- **Bill.txt**: Stores inventory data in the format `Item : Rate : Quantity`.
- **Bill Temp.txt**: Temporary file used for updating inventory.

## Future Improvements
- Implement a graphical user interface (GUI) for better user experience.
- Use a database (e.g., MySQL, SQLite) instead of text files for data management.
- Add user authentication for admin and cashier roles.

## License
This project is open-source and free to use under the MIT License.

