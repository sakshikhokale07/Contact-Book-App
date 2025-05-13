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
