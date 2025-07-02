# Restaurant_Billing_System
A structured, console-based billing system in C that enables invoice generation, customer-specific searches, and historical record retrieval. Utilizes structs and binary file handling for persistent storage, with modular design and tax/discount computation support.

# Key Features
1. Inovice Generation: Add customer details and multiple items with quantity and price, then generate a detailed invoice with tax and discount.
2. Persistent Storage: All invoices are saved in a binary `.dat` file for later retrieval.
3. Invoice Search by Customer:  Search for previous invoices by entering the customer's name.
4. Bill Formatting: Separate functions for header, body, and footer display clean and structured billing output.
5. Tax and Discount Calculation:  Automatically applies 10% discount and 9% CGST + SGST on net total.
6. Menu-Driven Interface:  Simple and clear terminal interface for easy navigation.

# Tech Stack
- **Language**: C  
- **Concepts Used**:  
  - Structures (`struct`)  
  - File Handling (`fopen`, `fwrite`, `fread`)  
  - Console I/O  
  - Conditional and Loop Statements
  - Modular Function Design

