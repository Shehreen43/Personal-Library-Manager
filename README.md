# 📚 Book Collection Manager

**Book Collection Manager** is a command-line Python application that allows users to manage their personal book collections. You can store, organize, and track your reading progress using a simple menu interface. All data is saved in a local JSON file for persistence.

## 🧩 Features

- ✅ Add new books to your collection
- ❌ Remove books by title
- 🔍 Search books by title or author
- ✏️ Update book details
- 📖 View your full collection
- 📊 Track your reading progress
- 💾 Automatically saves data in `books_data.json`

## 🛠 How It Works

When you run the program, it displays a menu:

📚 Welcome to Your Book Collection Manager! 📚

1. Add a new book

2. Remove a book

3. Search for books

4. Update book details

5. View all books

6. View reading progress

7. Exit


### Book Details

When adding or editing a book, you'll provide:
- **Title**
- **Author**
- **Publication Year**
- **Genre**
- **Read Status** (`yes` or `no`)

### Storage

All books are saved in a file named `books_data.json` so your collection persists across sessions.

## 💻 How to Run

1. Make sure Python 3 is installed.
2. Clone the repository or download the Python file.
4. Open terminal and run:

```bash
python main.py
```

📁 Project Structure
```bash
Personal-Library-Manager/
├── main.py            # Main Python script
└── books_data.json    # Data file (auto-generated)
```
