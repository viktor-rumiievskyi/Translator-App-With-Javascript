
# 🌍 Translator App with JavaScript

A simple and responsive **language translation web app** built with **HTML**, **CSS**, and **JavaScript** using the **MyMemory Translation API**. Instantly translate text between multiple languages via a clean and intuitive interface.

## ✨ Features

- 🔄 Translate text between various languages
- 🌐 Language selector dropdowns (source & target)
- 🧠 Copy to clipboard support
- 🎤 Text-to-speech (TTS) functionality (optional)
- 📱 Responsive design for mobile and desktop

## 💡 Technologies Used

- HTML5
- CSS3 (Flexbox/Grid)
- JavaScript (Fetch API)
- [MyMemory API](https://mymemory.translated.net/)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/viktor-rumiievskyi/Translator-App-With-Javascript.git
cd Translator-App-With-Javascript
```

### 2. Open in Browser

Open `index.html` directly in your browser.

### Optional: Use Local Server

```bash
# Python 3
python -m http.server
```

Visit `http://localhost:8000`.

## 📁 Project Structure

```
Translator-App-With-Javascript/
│
├── index.html       # Main app structure
├── style.css        # Responsive styling
├── script.js        # API interaction and app logic
└── README.md        # Documentation
```


## 🌟 Potential Improvements

- 🔐 Error handling for API failures
- 🕹️ Keyboard shortcuts for quick translation
- 🧭 Save recent translations to localStorage
- 🌓 Add dark mode support
- 📤 Share translation via link or social media

## 🛠 Example API Usage

```javascript
fetch(`https://api.mymemory.translated.net/get?q=hello&langpair=en|es`)
  .then(response => response.json())
  .then(data => {
    console.log(data.responseData.translatedText); // Output: hola
  });
```

## 👨‍💻 Author

**Viktor Rumiievskyi**  
- GitHub: [@viktor-rumiievskyi](https://github.com/viktor-rumiievskyi)

## 📄 License

This project is licensed under the MIT License.

---

![GitHub repo size](https://img.shields.io/github/repo-size/viktor-rumiievskyi/Translator-App-With-Javascript)
![GitHub last commit](https://img.shields.io/github/last-commit/viktor-rumiievskyi/Translator-App-With-Javascript)
![GitHub license](https://img.shields.io/github/license/viktor-rumiievskyi/Translator-App-With-Javascript)
