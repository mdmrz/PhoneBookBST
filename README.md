Phone Book Management Using Binary Search Tree (BST)

 📖 Description
A Python console application that manages a simple phone book using a **Binary Search Tree (BST)**.  
Contacts are stored as tree nodes with the **name** as the key and the **phone number** as the value.  
All operations (insert, delete, search, display) are implemented recursively without using built-in Python data structures like `dict`, `set`, or `list`.

🛠 Features
● Add a new contact (name must be unique)
● Delete a contact by name
● Search for a contact by name
● Display all contacts in **alphabetical order** (Inorder Traversal)
● Console-based application

🏗 Data Structure

● **Contact Node**:
  - `name` (key)
  - `phone` (value)
  - `left` child
  - `right` child
● **Binary Search Tree**:
  - Ensures contacts are automatically **sorted alphabetically**
  - Recursive operations for insertion, deletion, search, and traversal

▶ How to Run

1. Clone the repository or download the files  
2. Navigate to the project folder in terminal  
3. Run the main Python file:
python main.py
4. Use the menu to add, delete, search, or display contacts

💬 Example Usage

Insert Contacts:

Add: Reza - 09120000000
Add: Amir - 09350000000
Add: Sara - 09910000000

Display All Contacts (Inorder):

Amir - 09350000000
Reza - 09120000000
Sara - 09910000000

Search:

Enter name: Amir
Found: Amir - 09350000000

Delete:

Enter name to delete: Reza
Contact deleted.

👨‍💻 Author

Mohammadreza Shafaghati

B.Sc. Student in Computer Engineering
University of Guilan
