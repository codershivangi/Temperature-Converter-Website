# 🌡️ Temperature Converter Website

A clean, user-friendly web app that converts temperatures between Celsius, Fahrenheit, and Kelvin.  
Built with HTML, CSS, and JavaScript, this tool demonstrates real-time client-side interaction and responsive design.

---

## 🔍 Overview

This project offers a simple and intuitive interface for converting temperature units.  
Users can enter a value and select source/target units to get instantaneous conversion results without page reloads.

It’s ideal for embedding in educational sites, dashboards, or as a utility widget on your portfolio.

---

## ⚙️ How It Works

1. **User Input**  
   The user enters a numerical temperature in a text field and selects the original unit (Celsius / Fahrenheit / Kelvin) and the target unit.

2. **JavaScript Conversion Logic**  
   On input or button click, JavaScript captures the value and units, applies the corresponding formula, and calculates the converted value.

3. **Display Result**  
   The result is injected into the DOM and displayed immediately, without needing to refresh the page.

4. **Validation & Edge Handling**  
   The script checks for invalid inputs (non-numbers, empty fields) and handles edge cases (e.g. converting between the same unit yields the same value).

---

## 🧮 Conversion Formulas / Models

| From → To | Formula |
|-----------|---------|
| Celsius → Fahrenheit | `°F = °C × 9/5 + 32` |
| Celsius → Kelvin | `K = °C + 273.15` |
| Fahrenheit → Celsius | `°C = (°F − 32) × 5/9` |
| Fahrenheit → Kelvin | `K = (°F − 32) × 5/9 + 273.15` |
| Kelvin → Celsius | `°C = K − 273.15` |
| Kelvin → Fahrenheit | `°F = (K − 273.15) × 9/5 + 32` |

These formulas are implemented via JavaScript functions in `script.js`.

---

## 💻 Technologies Used

- **HTML5** — structuring the web page  
- **CSS3** — styling (layout, responsiveness, user interface)  
- **JavaScript (ES6+)** — conversion logic & DOM manipulation  
- **Vanilla JS** — no external libraries or frameworks, lightweight and fast  

---

## ✨ Features

- ✅ **Real-time conversion** — instantaneous feedback as you type  
- 🔄 **Multiple units supported** — Celsius, Fahrenheit, Kelvin  
- 🚫 **Input validation** — handles invalid or empty inputs gracefully  
- 🧼 **Clean UI / UX** — simple layout with responsive design  
- 🔧 **Easy to embed** — self-contained (HTML/CSS/JS) and portable  

---

## 📁 Project Structure

