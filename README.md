# 🔐 Password Manager (Advanced) – Tkinter + JSON

A secure, user-friendly **Password Manager** built with Python and Tkinter.  
It allows you to generate strong passwords, save them locally in a JSON file, and retrieve them anytime using a built-in search function.

---

## 🧠 Key Features

✅ Strong password generator (with letters, symbols, numbers)  
✅ Auto-copy password to clipboard  
✅ Saves website, email, and password data to `data.json`  
✅ Search function to retrieve credentials by website name  
✅ Input validation and error handling (e.g., missing fields, missing file)  
✅ Clean GUI with logo image

---

## 🖼️ Screenshot

<img src="https://img.icons8.com/color/96/password.png" alt="Password Manager Icon" width="100" />

*(You can add a real screenshot of your app here for a better preview.)*

---

## 📁 Project Structure

password-manager/
├── main.py # Main application
├── data.json # Stores all website/email/password info (auto-created)
├── logo.png # Lock or vault image (used in UI)
├── requirements.txt # Project dependencies
└── README.md # This file


---

## 📦 Dependencies

- `tkinter` – GUI framework
- `pyperclip` – To copy password to clipboard
- `json` – To save/retrieve data (built-in)

Install dependencies using:


pip install -r requirements.txt
- requirements.txt
- tk
- pyperclip

##🚀 Getting Started

- git clone https://github.com/yourusername/password-manager.git
- cd password-manager
- python main.py

## 🔍 Search Function

Enter the website name

Click Search

The app will retrieve and show the associated email and password

If the website doesn't exist or file is missing, you’ll get a friendly message

## 💾 Data Storage Format

Data is saved in data.json like this:
{
  "github.com": {
    "email": "your_email@example.com",
    "password": "a1B!c2D@"
  },
  "gmail.com": {
    "email": "myemail@gmail.com",
    "password": "P@ssw0rd123"
  }
}
