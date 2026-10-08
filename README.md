# 😊 Emotion Rating App

An interactive **Emotion Rating App** built using **HTML, CSS, and JavaScript**. Users can click emoji buttons to rate different emotions from **0 to 10**.

## 🚀 Features

- 😊 Rate Happy emotions
- 😕 Rate Confused emotions
- 😢 Rate Sad emotions
- ❤️ Rate Loving emotions
- Each emotion has an independent count.
- Counts increase from `0/10` up to `10/10`.
- Counts cannot go above `10/10`.
- Uses reusable JavaScript functions to avoid repetitive code.
- Uses `querySelectorAll()` and `forEach()` to handle multiple buttons.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript

## 🧠 JavaScript Concepts Practiced

This project helped me practice:

- `querySelector()`
- `querySelectorAll()`
- `addEventListener()`
- Callback functions
- Function parameters
- `forEach()`
- `textContent`
- `split()`
- Type conversion using `Number()`
- Template literals
- Increment operator
- Reusable functions
- NodeList

## ⚙️ How It Works

1. JavaScript selects all elements with the `.emoji-btn` class.
2. `forEach()` goes through each button.
3. A click event listener is added to every button.
4. When a button is clicked, `updateCount()` is called.
5. The current count is extracted from the `.count` element.
6. The count is increased by `1`.
7. The updated count is displayed.
8. The count stops increasing after `10/10`.

## 📂 Project Structure

```text
emotion-rating-app/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🎯 Purpose

I built this project to practice **JavaScript DOM manipulation, event listeners, reusable functions, NodeLists, and array-like structures** while creating an interactive web application.

## 👩‍💻 Author

**Shaik Fathima Zakiya**

Aspiring Software Engineer | JavaScript Learner