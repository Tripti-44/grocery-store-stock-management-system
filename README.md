# grocery-store-stock-management-system
A simple terminal-based stock management system for a grocery store. It supports two types of users — Customer and Grocer — and allows operations like viewing, adding, updating, deleting stock, and generating bills. The backend uses Python and MySQL.
---
📌 Features

👤 For Customers:

View stock by:

Name

Code

Quantity

Price

Search for items using any of the above attributes

🧑‍💼 For Grocers (Password Protected):

View stock

Add new items to stock

Update existing stock

Delete stock items

Search stock

Generate a bill for purchases

---
🗃️ Technologies Used

Python 3

MySQL (via mysql-connector-python)

Console/Terminal for user interfac

---
⚙️ Setup Instructions

1. Requirements

Python 3.x

MySQL server

mysql-connector-python module
Install it using:

pip install mysql-connector-python

2. Database Configuration

The script creates a new MySQL database called project.

Default MySQL credentials used:

host='localhost'
user='root'
password='dpsd'

3. Running the Program

Simply run:

python gssms.py

The program will display a menu where you can select if you're a customer or grocer.

> 🧾 Grocer password is currently hardcoded as 2024.
---

🧪 Sample Data Included

The following items are inserted initially:

Name	Code	Quantity	Price

Biscuits	111	50	10

Chips	222	50	10

Bread	333	15	25

Flour	444	65	80

Pulses	555	45	30

Rice	666	21	78

---

🚧 Known Limitations

Basic console UI (no GUI).

No user login or authentication system beyond a hardcoded password.

SQL queries use string formatting and are not fully protected against SQL injection (for learning/demo only).

The same quantity/price for multiple items may cause ambiguity in update/delete operations.

---

💡 Future Improvements

Add GUI using tkinter or PyQt

Use parameterized queries for security

Add item categories (e.g., food, household, etc.)

Add user login system

Export bill to PDF or CSV

---

📸 Demo 
![image](https://github.com/user-attachments/assets/47294b1e-16cd-41fc-9aaa-a8a9c1231c50)
![image](https://github.com/user-attachments/assets/4b7b4501-e6d3-4f50-bbc7-d83e5d9ac2d6)

---
🙋‍♀️ Author

TRIPTI
Student at IGDTUW
---
