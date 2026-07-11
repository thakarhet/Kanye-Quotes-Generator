# 🎤 Kanye Quotes Generator

A simple desktop application built with **Python** and **Tkinter** that fetches random Kanye West quotes using the **Kanye REST API** and displays them in a clean graphical interface.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green)
![API](https://img.shields.io/badge/API-Kanye%20REST-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📖 About

This application demonstrates how to integrate a REST API into a Python desktop GUI.

Whenever the Kanye button is clicked, the app:
- Sends a GET request to the Kanye REST API.
- Receives a random quote in JSON format.
- Updates the quote displayed on the interface instantly.

---

## ✨ Features

- 🎤 Random Kanye West quotes
- 🌐 API integration using the `requests` library
- 🖥️ Interactive GUI built with Tkinter
- ⚡ Fast and lightweight
- 🎨 Custom background and button images

---

## 🛠️ Technologies Used

- Python
- Tkinter
- Requests Library
- REST API

---

## 📂 Project Structure

```
kanye-quotes/
│
├── main.py
├── background.png
├── kanye.png
└── README.md
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/kanye-quotes.git
```

### 2. Navigate into the project

```bash
cd kanye-quotes
```

### 3. Install dependencies

```bash
pip install requests
```

### 4. Run the application

```bash
python main.py
```

---

## ⚙️ How It Works

1. The application starts with a default quote.
2. Clicking the **Kanye** button triggers an API request.
3. The app fetches a random quote from:

```
https://api.kanye.rest/
```

4. The returned quote replaces the current text on the canvas.

---

## 📌 API Used

**Kanye REST API**

Returns random Kanye West quotes in JSON format.

Example Response:

```json
{
  "quote": "Believe in your flyness... conquer your shyness."
}
```

---

## 📚 What I Learned

Through this project, I learned:

- Making HTTP requests using the `requests` library
- Working with JSON responses
- Updating Tkinter widgets dynamically
- Integrating APIs into desktop applications
- Event-driven programming in Python

---

## 🔮 Future Improvements

- Copy quote to clipboard
- Save favorite quotes
- Dark mode
- Quote history
- Share quotes on social media

---

## 👨‍💻 Author

**Het Thakar**

GitHub: https://github.com/thakarhet

---

## 📄 License

This project is licensed under the MIT License.
Kanye Quotes Generator
