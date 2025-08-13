# Cantilever
# 📚 Contact Book & 💰 Expense Tracker

This repository contains two Python-based command-line applications:

1. **Contact Book** – A simple tool to store, search, update, and delete contact information.
2. **Expense Tracker** – A utility to log expenses, view summaries, and visualize spending patterns.



## 🚀 Features

### 📒 Contact Book

* Add new contacts (Name, Phone, Email, Address)
* View all saved contacts
* Search contacts by name
* Update existing contact details
* Delete contacts
* Data stored in `contacts.csv` for persistence

### 💰 Expense Tracker

* Add expenses with date, category, and amount
* View all recorded expenses
* Summarize expenses by category
* Visualize spending with bar charts
* Data stored in `expenses.csv` for persistence

---

## 🛠️ Requirements

Make sure you have Python 3.x installed along with the following dependencies:

```bash
pip install pandas matplotlib
```

---

## 📂 File Structure

```
.
├── contact_book.py      # Contact Book script
├── expense_tracker.py   # Expense Tracker script
├── contacts.csv         # Auto-created contact storage file
├── expenses.csv         # Auto-created expense storage file
└── README.md            # Project documentation
```

---

## ▶️ Usage

### 1. Contact Book

```bash
python contact_book.py
```

You will see a menu:

```
1. Add Contact
2. View Contacts
3. Search Contact
4. Update Contact
5. Delete Contact
6. Exit
```

### 2. Expense Tracker

```bash
python expense_tracker.py
```

You will see a menu:

```
1. Add Expense
2. View All Expenses
3. Summary by Category
4. Plot Expenses by Category
5. Exit
```

## 📊 Example Outputs

**Contact Book**

```
📒 Contact Book
1. Add Contact
2. View Contacts
...
Contact 'John Doe' added successfully!
```

**Expense Tracker**

```
💰 Expense Tracker
1. Add Expense
...
Expense of 200.0 added under 'Groceries' on 2025-08-13
```



