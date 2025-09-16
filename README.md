# Foodie-Hub-Online-Food-Ordering-System
Food order website
# 🍔 Food Booking Website

A simple **Food Ordering & Booking System** built with **HTML, CSS, and JavaScript**.  
This project allows users to browse food items, view varieties (Pizza, Burgers, Pasta, Ice-Cream), place orders, and make payments (Cash on Delivery).  
It also includes a protected **Admin Panel** to view all customer orders.

---

## 🚀 Features
- ✅ Attractive **Home Page** with food categories  
- ✅ Separate pages for:
  - 🍕 Pizza (Veg, Non-Veg, Combos)
  - 🍔 Burgers (Veg, Non-Veg, Combos)
  - 🍝 Pasta (White, Red, Mixed)
  - 🍨 Ice-Cream (Flavors, Sundae, Special)  
- ✅ **Order Now** buttons with product & price integration  
- ✅ **Payment Page** (Cash on Delivery only)  
- ✅ Confirmation message after successful order  
- ✅ Orders stored in **LocalStorage** (simulating a backend)  
- ✅ **Admin Panel** (password-protected: `admin123`)  
  - View all placed orders with product, price & date  

---

## 📂 Project Structure

Food-Booking-Project/
│── index.html # Home Page
│── pizza.html # Pizza main page
│── burger.html # Burger main page
│── pasta.html # Pasta main page
│── icecream.html # Ice-cream main page
│── payment.html # Payment page
│── confirm.html # Confirmation page
│── admin.html # Admin Panel
│
├── pizza/
│ ├── veg.html
│ ├── nonveg.html
│ └── combo.html
│
├── burger/
│ ├── veg.html
│ ├── nonveg.html
│ └── combo.html
│
├── pasta/
│ ├── white.html
│ ├── red.html
│ └── mixed.html
│
├── icecream/
│ ├── flavors.html
│ ├── sundae.html
│ └── special.html
│
├── css/
│ ├── style.css # For index.html
│ ├── pizza.css # For pizza.html
│ ├── burger.css # For burger.html
│ ├── pasta.css # For pasta.html
│ ├── icecream.css # For icecream.html
│ └── varieties.css # For all varieties pages
│
└── js/
└── script.js # Main JavaScript logic


---

## 🛠️ How to Run
1. Clone or download this project.  
2. Open `index.html` in any modern browser.  
3. Navigate to your favorite category (Pizza, Burger, Pasta, Ice-Cream).  
4. Click **Order Now** → you’ll be redirected to the **Payment Page**.  
5. Complete payment (Cash on Delivery).  
6. You’ll see a confirmation message on the home page.  
7. For **Admin Access**, open `admin.html` → enter password `admin123`.  

---

## 🔑 Admin Panel
- **Password**: `admin123`  
- Features:
  - View all orders placed by customers
  - Order details include Product Name, Price, Status, and Date/Time

---

## 🎨 Tech Stack
- **Frontend**: HTML, CSS, JavaScript  
- **Storage**: Browser LocalStorage (to simulate a database)

---

## 📌 Future Improvements
- Add **user authentication system** (login/register)  
- Integrate with **real payment gateway** (Razorpay/Stripe)  
- Connect with **backend (Node.js / PHP / Firebase)** for permanent data storage  
- Add **cart functionality** to allow multiple items in one order  

---

## 👨‍💻 Author
Developed by **Ruturaj Ghutugade** ✨  



