# auto-text-completer

This is a simple text auto-completion web application built using a *Trie (prefix tree)* data structure. It suggests word completions based on the characters typed by the user.

## ✨ Features

- Real-time word suggestions
- Built using Python Flask (backend)
- Trie data structure for fast prefix lookups
- Simple and clean frontend using HTML, CSS, and JavaScript
- Automatically saves new words to a file if not already present

## 🚀 How to Run

1. Clone the repository:

bash
git clone https://github.com/MANIKAAGARG/auto-text-completer.git
cd text-autocompleter

2.Install Flask (if not already installed):
pip install flask

3. Run the app:
python app.py

4.Open your browser and go to:
http://localhost:5000

📚 How It Works
The backend uses a Trie to store and search words quickly by prefix.
On every keypress, frontend sends the typed prefix to the server via AJAX.
The server returns a list of suggestions, which are displayed below the input box.
If a new word is typed and used, it gets saved into dictionary.txt.

✅ Future Improvements
Add ability to delete or edit words
Track most frequently used suggestions
Sync dictionary with a database

