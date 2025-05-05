# 🛍️ Functional Myntra Clone

This is a functional clone of the popular e-commerce website **Myntra**, developed using vanilla JavaScript, HTML, and CSS. It focuses on core functionalities like dynamic product display, add-to-cart behavior, and persistent local storage handling — all without using any frontend frameworks.

---

## 🚀 Features

- 🔄 **Persistent Cart** using `localStorage` (bag item count persists on refresh)
- 🛒 **Add to Bag** functionality with live cart count update
- 📦 Dynamic rendering of items on the homepage
- ✅ Mobile-responsive layout (if CSS is added accordingly)
- ✨ Clean and minimal UI mimicking real-world e-commerce sites

---

## 🧰 Tech Stack

- **HTML**
- **CSS**
- **JavaScript (ES6)**
- **Local Storage API**

---

## 📂 Folder Structure

4 Myntra Functional Clone/
├── index.html
├── style.css
├── script.js
├── data.js (for item listings)
└── assets/
└── images/



---

## 📦 How to Run

1. **Clone this repository** or [Download the ZIP](#)
2. **Extract it** and open the project folder
3. Open `index.html` in your browser

_No build tools or npm packages are needed._

---

## 🔧 Core Logic

- On page load, `localStorage` is checked for saved cart items
- Cart (bag) count updates dynamically via `displayBagIcon()`
- Products are rendered dynamically using JS from a predefined array (`items`)
- Cart contents are saved on every `addToBag()` action

---

## 📝 Future Improvements (Optional)

- 🔍 Product search functionality
- 🧾 Checkout and billing system
- 👤 User login and authentication
- 📱 Full responsiveness with mobile-friendly design

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/a65c953f-6156-4e37-b543-e9317cda0ed5)
![image](https://github.com/user-attachments/assets/9d2d3be6-0841-4890-a126-0007fdb95648)

---

## 👨‍💻 Author

- **Your Name**
- [GitHub Profile](https://github.com/yourusername)
- [LinkedIn](https://linkedin.com/in/yourprofile)

---

## 📄 License

This project is open-source and free to use for educational purposes.
