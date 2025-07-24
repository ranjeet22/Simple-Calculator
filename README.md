# 🧮 Simple Calculator

A stylish and responsive **Calculator Web App** built using **HTML**, **CSS**, and **JavaScript**.  
This project is ideal for beginners learning DOM manipulation, layout design, and event handling in the browser.

![Calculator Preview](./assets/calculator-preview.png) <!-- Replace with actual path if hosted -->

---

## 📱 Live Preview

> 🔗 **[Open Calculator in Browser](http://127.0.0.1:5500/calculator/index.html)**  
_(Make sure you're running it via a local development server like Live Server in VS Code)_

---

## 🚀 Features

- 🔢 Perform basic arithmetic operations: `+`, `−`, `×`, `/`
- 🧼 Clear button (`C`) to reset the display
- 💡 Supports decimal input
- 📱 Mobile responsive layout
- 🎨 Modern, dark-themed UI with colored operator buttons

---

## 🛠️ Built With

| Language | Usage            |
|----------|------------------|
| HTML     | Markup structure |
| CSS      | Styling and layout |
| JS       | Interactive logic (DOM manipulation, event handling) |

---

## 📂 Folder Structure
```
calculator/
├── index.html # Main HTML file
├── style.css # Styling for calculator
├── index.js # JavaScript logic
└── README.md # Project documentation

```

---

## 🧠 How It Works

1. Each button triggers a JavaScript function using `onclick`.
2. Digits and operators append to the display using `appendToDisplay(value)`.
3. `=` button evaluates the expression using `eval()` and displays the result.
4. `C` button clears the display with `clearDisplay()`.

---

## 🔒 Safety Note

The calculator uses JavaScript's built-in `eval()` function, which works for this simple case. However, for production apps, **never use `eval()` with user input** due to potential security risks.

---

## 🎯 Future Improvements

- Add keyboard support (typing instead of clicking)
- Improve accessibility with ARIA roles
- Add parentheses and more advanced operations
- Implement custom expression parser (to avoid using `eval()`)

---

## 📸 Screenshot

> ![Calculator UI](./assets/f0fa3fef-0000-4529-a92b-2336f6dd0313.png)

---

## 🙌 Contributing

If you have suggestions or improvements, feel free to fork the repository and submit a pull request.  
New UI themes, bug fixes, or feature additions are all welcome!

---

## 📄 License

This project is licensed under the **MIT License** — you’re free to use, modify, and distribute it.

---

> 💡 *Made for learning and fun — practice your front-end skills and build cool stuff!*
