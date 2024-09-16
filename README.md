# BilledIn

BilledIn is a simple billing system (Desktop application) for small businesses. It is designed to be easy to use and easy to understand. It is completely written in Python and uses the Tkinter library for the GUI and SQLite for the database.

## Features

- **Main Screen**

  - The main screen of the application is where the user will get an option to login as admin or as an employee.
    ![Main Screen](images/main_pg.png)

- **Employee Login**

  - The employee can login using their employee ID and password. One standout feature of the application is that the employee can only login if the admin has created an account for them. Additionally, the password is encrypted, ensuring the security of the employee's account.
    ![Employee Login](images/emp_lgn.png)

- **Admin Mode**

  - The admin can login using the default username and password, which is "admin01" and "admin01" respectively.
    ![Admin Login](images/admn_pg.png)
  - List of things the admin can do:
    - Inventory Management
    - Employee Management
    - Invoice Management
    - Settings

- **Inventory Management**

  - The admin can search, add, update, delete, and generate barcode stickers for the products.
    ![Inventory Management](images/inv_mngmnt.png)
  - Update Product
    ![Update Product](images/prod_updt.png)

- **Employee Management**

  - The admin can search, add, update, and delete employee accounts.
    ![Employee Management](images/emp_mngmnt.png)
  - Add Employee
    ![Add Employee](images/add_emp.png)

- **Invoice Management**

  - The admin can search invoices, generate bills, and create sales reports.
    ![Invoice Management](images/invc_mngmnt.png)
  - Sales Report
    ![Sales Report](images/sales_report.png)

- **Billing Screen**

  - The employee can generate bills for the customers.
    ![Billing Screen](images/blng_scrn.png)

- **Barcode Sticker**
  - The admin can generate barcode stickers for the products.
    ![Barcode Sticker](images/prod_stckr.png)

## Installation

1. **Clone the Repository:**

   ```bash
   https://github.com/Akshayffb/Desktop-Billing-Software.git
   cd Desktop-Billing-Software
   ```

2. **Create and Activate a Virtual Environment:**

   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
   ```

3. **Install the Required Packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application:**
   ```bash
   python app.py
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Additional Commands

To ensure that all required packages are installed, use the following commands:

```bash
pip install pywin32 svgwrite python-barcode keyboard
```
