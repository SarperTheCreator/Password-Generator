# 🔑 Password Generator

A lightweight, modern, and highly functional web-based **Password Generator** built using **HTML5, CSS3, and Vanilla JavaScript**. This tool allows users to generate secure, customizable passwords with real-time feedback on password strength and instant clipboard copying.

---

## 🚀 Features

* **Customizable Length:** Generate passwords from 1 up to 30 characters using an interactive slider.
* **Advanced Criteria Options:** Mix and match Lowercase, Uppercase, Numbers, and Symbols to meet specific security requirements.
* **Smart Filtering:** Option to exclude duplicate characters or inject spaces into the password string.
* **Dynamic Strength Indicator:** A visual indicator bar that updates in real-time (`Weak`, `Medium`, or `Strong`) based on the selected password length.
* **One-Click Copy:** Copy the generated password immediately to your clipboard with temporary visual feedback (icon change and color shift).
* **Responsive Layout:** Clean, minimalist UI built with CSS Flexbox, custom form styling, and smooth transition states.

---

## 🛠️ Tech Stack

* **HTML5:** Semantic markup structure utilizing Google Material Symbols for sharp, scalable iconography.
* **CSS3:** Styled with the modern Poppins font family, customized range sliders, and dynamic pseudo-elements (`::before`) for character-strength transitions.
* **JavaScript (ES6+):** Vanilla script driving conditional string manipulation, real-time input event listeners, and Async Clipboard API operations.

---

## 📂 Project Structure

```text
├── index.html     # Application structure & markup
├── style.css      # Core styles, layout layout, and themes
└── script.js      # Password generation, logic filters, and DOM utility
