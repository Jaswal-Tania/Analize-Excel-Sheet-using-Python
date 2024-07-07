# Inventory Management Using Python

This Python script processes an inventory Excel file to provide insights into the products and suppliers, including the number of products per supplier, total inventory value per supplier, and products with inventory less than 10.

## Features

- **Number of Products per Supplier:** Calculates and displays the total number of products each supplier provides.
- **Total Value per Supplier:** Calculates and displays the total value of inventory for each supplier.
- **Products with Inventory Less Than 10:** Identifies and lists products with inventory counts below 10.
- **Inventory Value Calculation:** Calculates and adds the total inventory value for each product in the Excel sheet.

## Requirements

- Python 3.x
- `openpyxl` library

## Installation

1. **Install Python:** Make sure you have Python 3.x installed. You can download it from [python.org](https://www.python.org/).

2. **Install `openpyxl`:** Install the `openpyxl` library using pip:
    ```sh
    pip install openpyxl
    ```

3. **Download the Script and Excel File:**
    - Save the script to a `.py` file (e.g., `inventory_management.py`).
    - Place your `inventory.xlsx` file in the same directory as the script.

## Usage

1. **Run the Script:**
    ```sh
    python inventory_management.py
    ```

2. **Results:**
    - The script will output the number of products per supplier, the total value of inventory per supplier, and a list of products with inventory less than 10.
    - The script will save a new Excel file named `inventory_with_total.xlsx` with the total inventory value added for each product.
