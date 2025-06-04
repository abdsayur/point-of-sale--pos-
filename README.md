# 📊 POS System — Restaurant & Cafe Point of Sale

A modern, online sales system tailored for restaurants, cafes, and various commercial establishments. Designed with simplicity and flexibility in mind, this system offers a full range of transaction management features for dine-in, takeaway, and delivery services — all accessible online from any connected device.

---

## 📌 Key Features

- 🌐 **Online Access**: Accessible from any device with internet connection.
- 📱 **Integrated Menu System**: Directly linked to your existing menu program.
- ✨ **Simple & Intuitive Interface**: Clean UI and straightforward user experience.
- 🧾 **Supports Full Transaction Types**: From cashiering to delivery and table reservations.
- 📊 **Dashboard Admin Panel**: Manage products, orders, tables, employees, and their permissions from a central dashboard.

---

## 🍽️ Transaction Modes

### 🛍️ Takeaway

The cashier selects items from various categories and products, applies optional discounts (percentage or fixed amount), adjusts quantities, then checks out and prints an invoice.

**▶️ Demo Video:**  
[![Takeaway Video](https://img.shields.io/badge/Watch-Takeaway%20.mov-blue)](screenshots/take-away.mov)

---

### 🍽️ Table Service

- Cashier selects a reserved or available table (managed by the admin).
- Records customer orders per table.
- Order remains open and the table unavailable until **Check Out** is completed and the bill is paid.
- Orders cannot be printed until the cashier submits the order.

**▶️ Demo Video:**  
[![Tables Video](https://img.shields.io/badge/Watch-Tables%20.mov-blue)](screenshots/tables.mov)

---

### 🚚 Delivery

- Employee captures customer details to ensure correct delivery.
- Records the order.
- Prints an invoice for the delivery person.

**▶️ Demo Video:**  
[![Delivery Video](https://img.shields.io/badge/Watch-Delivery%20.mov-blue)](screenshots/delivery.mov)

---

## 📅 End of Day Process

At closing, the system calculates total daily income from all orders, deducts costs, and securely locks new order entries until the next day — ensuring a clean, organized accounting cycle.

**▶️ Demo Video:**  
[![End of Day Video](https://img.shields.io/badge/Watch-End%20of%20Day%20.mov-blue)](screenshots/end-of-day.mov)

---

## 🔐 Employee Login

A simple, secure login page for employees to access the POS system according to their roles and permissions.

**🖼️ Screenshot:**  
![Login Screen](screenshots/login.png)

---

## ⚙️ Technologies Used

- 🐘 **Laravel** — PHP Framework for backend and RESTful APIs
- 🖥️ **Laravel Nova** — For powerful admin panel & resource management
- 📜 **Pure JavaScript** — Lightweight, fast front-end interaction
- 🗄️ **MySQL** — Reliable relational database

---

## 🌐 Live Demo

Explore the connected online menu: [qr.algorexe.com](https://qr.algorexe.com)

---

## 📞 Contact

For more information or business inquiries, feel free to reach out via:

- [LinkedIn](https://www.linkedin.com/in/yourusername)
- [Email](mailto:yourmail@example.com)

---

## 📂 Screenshots & Media

Stored inside the `/screenshots` folder:

- **Images**
  - `login.png`
- **Videos**
  - `take-away.mov`
  - `tables.mov`
  - `delivery.mov`
  - `end-of-day.mov`

---

## 🚀 How to Install

```bash
git clone https://github.com/yourusername/pos-system.git
cd pos-system
composer install
npm install && npm run dev
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
