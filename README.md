# Sampath Food City System

The Sampath Food City System is a Python-based CLI application designed to manage and analyze the sales and branch data of a supermarket network. It provides functionalities for adding new branches and sales, as well as analyzing sales data through various metrics.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Branch Management**: Add new branches to the supermarket network.
- **Sales Management**: Record new sales transactions.
- **Data Analysis**:
  - Monthly sales analysis of specific branches.
  - Price analysis of specific products.
  - Weekly sales analysis of the supermarket network.
  - Total sales amount analysis.
  - Monthly sales analysis of all branches.
  - Yearly sales analysis of all branches.

## Installation

1. **Clone the repository**:
   ```
   git clone https://github.com/yourusername/Sampath_Food_City_System.git
   cd Sampath_Food_City_System
   ```

2. **Install required packages**:
   ```
   pip install -r requirements.txt
   ```

   *(Note: If `requirements.txt` is not provided, install the necessary packages manually: `numpy`, `matplotlib`.)*

## Usage

1. **Run the main program**:
   ```
   python Sampath_Food_City_System.py
   ```

2. **Login**: Enter your username and password to access the system. If the credentials are valid, you'll be able to access the main menu.

3. **Main Menu Options**:
   - `1. Add a New Branch`: Add new branch information.
   - `2. Add a New Sale`: Record a new sale transaction.
   - `3. Monthly Sales Analysis of a Specific Branch`: Analyze the monthly sales of a specific branch.
   - `4. Price Analysis of a Specific Product`: Analyze the price distribution of a specific product.
   - `5. Weekly Sales Analysis of Supermarket Network`: Analyze the weekly sales of the entire network.
   - `6. Analysis of Total Sales Amounts of Purchases`: Analyze the total sales amount.
   - `7. Monthly Sales Analysis of All Branches`: Analyze the monthly sales of all branches.
   - `8. Yearly Sales Analysis of All Branches`: Analyze the yearly sales of all branches.
   - `9. Log out`: Exit the system.

## Project Structure

```
Sampath_Food_City_System/
├── users.csv                 # Contains user credentials
├── branches.csv              # Contains branch information
├── products.csv              # Contains product information
├── sales.csv                 # Contains sales transactions
├── App.py                    # Main program file
└── README.md                 # This README file
```
