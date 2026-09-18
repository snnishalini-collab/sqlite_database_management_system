

 README.md✓

# Contact Management Dashboard

 A simple **Contact Management System** built with **Python and SQLite3**. This project allows users to store, view, update, and delete contact records through a command-line dashboard.

 ## Features

 - Add new contact records
- View all saved contacts
- Update existing contact information
- Delete contact records
- Persistent data storage using SQLite
- Automatically creates the database table if it does not exist

 ## Contact Information Stored

 Each contact contains:

 - ID
- Name
- Age
- Gender
- Address
- Contact Number
- Email Address

 ## Technologies Used

 - **Python 3**
- **SQLite3**
- Python's built-in `sqlite3` library

 ## Database Structure

 The application creates a table named `datas`:

 | Column | Type | Description |
| --- | --- | --- |
| `id` | INTEGER | Primary key |
| `name` | TEXT | Contact name |
| `age` | INTEGER | Contact age |
| `gender` | TEXT | Contact gender |
| `address` | TEXT | Contact address |
| `contact` | TEXT | Contact number |
| `mail` | TEXT | Email address |

## Installation

 ### 1\. Clone the project

```
git clone https://github.com/snnishalini-collab/sqlite_database_management_system.git
cd sqlite_database_management_system
```

 ### 2\. Check Python

 Make sure Python 3 is installed:

```
python --version
```

 No external packages are required because `sqlite3` is included with Python.

 ## Usage

 Run the Python program:

```
python Database.py
```

 You will see the following menu:

```
1)Insert Record
2)Fetch Record
3)Update Record
4)Delete Record
```

 ### Insert Record

 Select `1` and enter:

```
Name
Age
Gender
Address
Contact
Email
```

 The record will be saved to the SQLite database.

 ### Fetch Records

 Select `2` to display all stored contacts.

 ### Update Record

 Select `3`, choose the field you want to change, and provide the contact ID.

 Available fields:

```
1. Name
2. Age
3. Gender
4. Address
5. Contact
6. Mail
```

 ### Delete Record

 Select `4`, enter the contact ID, and the corresponding record will be deleted.

 ## Database

 The application automatically creates:

```
Sqlitedatabasenew.db
```

 The database table is created automatically when the application starts.

 ## Project Structure

```
contact-management/
│
├── main.py
├── Sqlitedatabasenew.db
└── README.md
```

 > `Sqlitedatabasenew.db` will be generated automatically when the program is executed, so it does not need to be manually created.

 ## Future Improvements

 - Add a graphical user interface
- Add search functionality
- Validate email and phone numbers
- Add confirmation before deleting records
- Improve error handling
- Add password/login authentication
- Export contacts to CSV or Excel
- Convert the project into a web dashboard

 ## License

 This project is open-source and available for educational and personal use.