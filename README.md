# Training Week 1 - Module 3: Interactive Messaging System

## 📋 Description

This simple web application allows users to enter their full name and age into a form. The form validates the input and displays user-friendly feedback using [SweetAlert2](https://sweetalert2.github.io/). It's designed for beginners learning HTML, CSS, and JavaScript form handling.

---

## 🌐 Features

- **Form input fields** for full name and age  
- **Client-side validation** for:
  - Full name (letters and spaces only)
  - Age (must be a positive number)
- **Interactive alerts** with SweetAlert2:
  - Error messages for invalid inputs
  - Informative message if under 18
  - Success message if 18 or older
- **Responsive design** with basic styling

---

## 🛠 Technologies Used

- HTML5  
- CSS3  
- JavaScript (Vanilla)  
- [SweetAlert2](https://cdn.jsdelivr.net/npm/sweetalert2@11)

---

## ✅ How to Use

1. Clone or download the project files.
2. Open `index.html` in a web browser.
3. Fill in your **Full Name** and **Age**.
4. Click the **Submit** button to see feedback based on the entered data.

---

## 🔍 Validation Rules

- **Full Name**: Only letters and spaces allowed (including accented characters).
- **Age**: Must be a positive number.

---

## 📦 External Libraries

- SweetAlert2 is included via CDN:
  ```html
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>

---

## 📝 Notes

-  Make sure your main.js and style.css files are located in the same directory as index.html or update the paths accordingly.
-  For a better user experience, styles have been added for invalid inputs.
