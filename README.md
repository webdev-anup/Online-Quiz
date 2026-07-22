# Online-Quiz
# 🧠 Quiz App

A clean, interactive quiz application built with vanilla HTML, CSS, and JavaScript — featuring a countdown timer, animated progress bar, auto-correct highlighting, and a score result screen.

> Built as part of my frontend development journey 🚀

---

## 🔴 Live Demo

[👉 View Live](https://github.com/webdev-anup/Online-Quiz.git) <!-- Replace with your actual GitHub Pages link -->

---

## ✨ Features

- ⏱️ **15-second countdown timer** per question
- 📊 **Animated time progress bar** that shrinks as time runs out
- ✅ **Instant feedback** — highlights correct and wrong answers on selection
- 🔒 **Auto-lock** — options are disabled once an answer is selected or time runs out
- 🏆 **Score result screen** with personalized messages based on performance
- 🔁 **Replay option** to retake the quiz without refreshing the page

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure & layout |
| CSS3 | Styling, transitions, animations |
| JavaScript (ES6) | Quiz logic, timer, DOM manipulation |
| Font Awesome 5 | Tick & cross icons |
| Google Fonts (Poppins) | Typography |

---

## 📁 Project Structure

```
quiz-app/
├── index.html          # Main HTML file
├── style.css           # All styles
└── js/
    ├── questions.js    # Question bank (data)
    └── script.js       # Core quiz logic
```

---

## 🚀 Getting Started

### Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/quiz-app.git
   ```

2. Open the project folder:
   ```bash
   cd quiz-app
   ```

3. Open `index.html` directly in your browser — no server needed!

---

## ➕ How to Add Questions

Open `js/questions.js` and add a new object to the `questions` array:

```js
{
  numb: 6,
  question: "Your question goes here?",
  answer: "Correct Answer",
  options: [
    "Option 1",
    "Option 2",
    "Correct Answer",
    "Option 4"
  ]
}
```

> Make sure `numb` values are sequential and `answer` exactly matches one of the `options`.

---

## 📸 Screenshots

| Start Screen | Quiz Screen | Result Screen |
|---|---|---|
| *(coming soon)* | *(coming soon)* | *(coming soon)* |

---

## 🙋‍♂️ Author

**Anup Patwa**
- GitHub: [@anup-patwa](https://github.com/webdev-anup)
- LinkedIn: [linkedin.com/in/your-profile](https://www.linkedin.com/in/anup-patwa-8b91b8372/)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ If you found this helpful, consider giving it a star!
