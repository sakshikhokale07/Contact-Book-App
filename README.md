# 📒 Contact Book App

A simple, menu-driven Python program to manage a contact book. This command-line application allows users to create, view, update, delete, search, and count contacts using a dictionary-based data structure.

---

## 🚀 Features

- ✅ Create a new contact with name, age, email, and mobile number
- 🔍 View details of a specific contact
- 📝 Update an existing contact's information
- 🗑️ Delete a contact by name
- 🔎 Search for contacts by name (partial or full, case-insensitive)
- 🔢 Count total number of contacts
- ❌ Exit the application gracefully

---

## 🧱 Data Structure

Contacts are stored in a Python dictionary:

```python
contacts = {
    'Alice': {'age': 30, 'email': 'alice@example.com', 'mobile': '1234567890'}
}
Each contact's name is a key.

The value is another dictionary with:

'age' (int)

'email' (str)

'mobile' (str)

💻 How to Run
Make sure you have Python installed (version 3.x).

Save the script as contact_book.py.

Run it using your terminal or command prompt:

bash
Copy
Edit
python contact_book.py
🧪 Sample Menu
markdown
Copy
Edit
Contact Book App
1. Create contact
2. View contact
3. Update contact
4. Delete contact
5. Search contact
6. Count contact
7. Exit
