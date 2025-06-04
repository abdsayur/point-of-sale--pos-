# 📊 POS System — Restaurant & Cafe Point of Sale

A modern, online sales system tailored for restaurants, cafes, and various commercial establishments. Designed with simplicity and flexibility in mind, this system offers a full range of transaction management features for dine-in, takeaway, and delivery services — all accessible online from any connected device.

---

## 📌 Key Features

- 🌐 **Online Access**: Accessible from any device with an internet connection.
- 📱 **Integrated Menu System**: Directly linked to your existing menu program.
- ✨ **Simple & Intuitive Interface**: Clean UI and straightforward user experience.
- 🧾 **Supports Full Transaction Types**: From cashiering to delivery and table reservations.
- 📊 **Dashboard Admin Panel**: Manage products, orders, tables, employees, and their permissions from a central dashboard.

---

## 🍽️ Transaction Modes

### 🛍️ Takeaway

The cashier selects items from various categories and products, applies optional discounts (percentage or fixed amount), adjusts quantities, then checks out and prints an invoice.

**▶️ Demo Video:**  
<video src="screenshots/take-away.mp4" controls width="600"></video>

---

### 🍽️ Table Service

- Cashier selects a reserved or available table (managed by the admin).
- Records customer orders per table.
- Orders remain open and tables unavailable until **Check Out** is completed and the bill is paid.
- Orders cannot be printed until the cashier submits the order.

**▶️ Demo Video:**  
<video src="screenshots/tables.mp4" controls width="600"></video>

---

### 🚚 Delivery

- Employee captures customer details to ensure correct delivery.
- Records the order.
- Prints an invoice for the delivery person.

**▶️ Demo Video:**  
<video src="screenshots/delivery.mp4" controls width="600"></video>

---

## 📅 End of Day Process

At closing, the system calculates total daily income from all orders, deducts costs, and securely locks new order entries until the next day — ensuring a clean, organized accounting cycle.

**▶️ Demo Video:**  
<video src="screenshots/end-of-day.mp4" controls width="600"></video>

---

## 🔐 Employee Login

A simple, secure login page for employees to access the POS system according to their roles and permissions.

**🖼️ Screenshot:**  
![Login Screen](screenshots/login.png)

---

## ⚙️ Technologies Used

- 🐘 **Laravel** — PHP Framework for backend and RESTful APIs.
- 🖥️ **Laravel Nova** — For powerful admin panel & resource management.
- 📜 **Pure JavaScript** — Lightweight, fast front-end interaction.
- 🗄️ **MySQL** — Reliable relational database.

---

## 🌐 Live Demo

Check out the connected online menu: [qr.algorexe.com](https://qr.algorexe.com)

---

## 📞 Contact

For more information or business inquiries, feel free to reach out via:

- [LinkedIn](https://www.linkedin.com/in/abdulrahman-derbass-aaa3021b3?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
- [Email](mailto:abdulrahmanderbass@gmail.com)

---

## 📂 Media Assets

All screenshots and demo videos are available inside the `/screenshots` folder:

- **Images**
  - `login.png`
- **Videos**
  - `take-away.mp4`
  - `tables.mp4`
  - `delivery.mp4`
  - `end-of-day.mp4`
