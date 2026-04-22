# 🌡️ Temperature Converter

A simple, interactive **Temperature Converter** built with **HTML, CSS, and JavaScript**.

---

## 📖 Overview
This project allows users to:
- Enter a numeric temperature value
- Choose a conversion direction (**Celsius ➡️ Fahrenheit** or **Fahrenheit ➡️ Celsius**)
- Click a button to instantly see the converted result

---

## ✨ Features
- **User-friendly form** with textbox and radio buttons  
- **Conversion logic** implemented in JavaScript  
- **Responsive design** styled with CSS (centered form, background color, rounded borders, bold labels)  
- **Error handling**: prompts user if no conversion option is selected  

---

## 🔢 Conversion Formulas
- **Celsius ➡️ Fahrenheit**  
  \[F = C \times \frac{9}{5} + 32\]

- **Fahrenheit ➡️ Celsius**  
  
\[ C = (F - 32) \times \frac{5}{9}\]



---

## ⚙️ How It Works
1. The **HTML file** defines the form structure.  
2. The **CSS file** styles the form for readability and visual appeal.  
3. The **JavaScript file**:
   - Connects to HTML elements using `document.getElementById`
   - Defines a `convert()` function
   - Uses `.checked` to determine which radio button is selected
   - Applies the correct formula and updates the result display

---

## 📂 Project Structure
Temperature-Converter/
│── index.html   # Form structure
│── style.css    # Styling rules
│── script.js    # Conversion logic


---

## 🚀 Usage
1. Clone or download the repository.  
2. Open `index.html` in your browser.  
3. Enter a temperature, select conversion type, and click **Convert**.  

---

## 🎯 Example
- Input: `0` with **Celsius ➡️ Fahrenheit** selected  
- Output: `32 °F`  

---

✅ This combination of **HTML for structure**, **CSS for design**, and **JavaScript for functionality** makes the converter interactive, intuitive, and easy to use.
