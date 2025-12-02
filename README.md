# Library Management System (C++)

A simple and beginner-friendly **Library Management System** built using C++.  
This project allows users to add books, search books, issue/return books, and view all records.  
All data is stored in a text file (`books.txt`) so records stay saved even after the program closes.

---

## 🚀 Features

- Add new books (ID, Title, Author)
- View all books with availability status
- Search for a book by ID
- Issue a book
- Return a book
- Data stored permanently in a text file
- Simple command-line interface

---

## 📁 Folder Structure

project-7-library-cpp/
│── main.cpp
│── books.txt
│── README.md

`books.txt` is created automatically when the program runs.

---

## ▶️ How to Run

1. Compile the program:
g++ main.cpp -o library

2. Run:
./library

3. Use the menu:
1 → Add Book
2 → View All Books
3 → Search Book
4 → Issue Book
5 → Return Book
0 → Exit

---

## 🛠️ Technologies Used

- C++
- File Handling
- Vectors & Classes

---

## 📜 Usage Example

**Add Book → View Books → Issue → Return**

Books will always show status:
- `Available`
- `Issued`

---

## 👨‍💻 Author

**Kartikey Gautam**

---

## 📜 License

This project is free to use and modify.
