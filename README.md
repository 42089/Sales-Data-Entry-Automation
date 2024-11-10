# Sales-Data-Entry-Automation
Python script to automate sales data entry in an Excel file called `sales_data.xlsx`. This program also ensures the Excel file is created if it doesn’t already exist.

## Features
- Creates an Excel file named `sales_data.xlsx` if it doesn't exist.
- Adds sales data (product, quantity, price, and total sales) into the Excel file.
- Automatically calculates total sales as `Quantity x Price`.
- Handles errors for invalid inputs.
- Prompts the user to continue adding data or exit the program.

## Installation Instructions

1. Ensure that Python 3.x is installed on your machine.
2. Install the required dependencies using pip:

    ```bash
    git clone https://github.com/42089/Sales-Data-Entry-Automation
    ```
   ```bash
    pip install openpyxl pandas keyboard
    ```
3. Now you can use the tool.
   
   ```bash
    python script.py
    ```

## Usage

1. Run the script `sales_data_entry.py`.
2. When prompted, enter the following details:
    - **Product Name**: Name of the product sold.
    - **Quantity Sold**: Number of units sold.
    - **Price Per Unit**: Price for a single unit of the product.

3. The program will calculate the total sales and add the data into `sales_data.xlsx` under the "Sales Data" sheet.

4. You can continue adding more sales data or press **'0'** to exit.

## License

Proprietary - Code is not available for public viewing or modification.

## Contact

For support or questions, email: mareehanadeem@gmail.com
