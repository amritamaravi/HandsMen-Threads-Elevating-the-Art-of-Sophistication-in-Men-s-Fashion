# 🧵 HandsMen Threads - Salesforce CRM Project

## 📌 Project Overview

**HandsMen Threads** is a custom-built Salesforce CRM solution tailored for a bespoke men's tailoring business. This project was developed as part of the Salesforce Virtual Internship 👨‍💻 and showcases how Salesforce tools can be used to manage customers, products, orders, inventory, and loyalty programs efficiently.

---

## 🎯 Business Goals

- ✅ Seamlessly manage custom tailoring orders  
- 📦 Track and manage inventory in real-time  
- 📧 Send automated order confirmations  
- 🏆 Reward loyal customers via automated tier upgrades  
- ⚙️ Improve efficiency with Salesforce automation

---

## 🛠️ Key Features

### 🔧 Custom Objects

- 👤 **HandsMen Customers** – Stores customer details like name, email, loyalty status, and total purchases  
- 🧾 **HandsMen Orders** – Tracks product orders and auto-calculates total amount  
- 🧵 **HandsMen Products** – Catalog of products (SKU, price, quantity)  
- 🏪 **Inventories** – Tracks stock levels and warehouse info  
- 📣 **Marketing Campaigns** – Manages promotional activities  

### ⚙️ Automation

- 🔁 **Record-Triggered Flows**:
  - 📤 Send order confirmation email when an order is marked "Confirmed"
  - 📉 Auto-update inventory quantity after order placement
  - 🚨 Trigger low stock alert if quantity < 5  

- ⏰ **Scheduled Flow**:
  - Runs daily at 12:00 AM 🕛 to update customer loyalty tiers:
    - 🥉 Bronze: ≤ ₹500  
    - 🥈 Silver: ₹501–₹999  
    - 🥇 Gold: ≥ ₹1000  
  - ✉️ Sends loyalty update emails automatically  

- 🛑 **Validation Rules**:
  - Checks for professional email format (e.g., must be `gmail.com`)  

- 💻 **Apex Trigger**:
  - Auto-calculates `Total Amount` = Quantity × Price when an order is created  

---

## 📸 Demo Screens

- 🧑‍💼 Custom App Interface  
- 🧾 Creating Orders & Customers  
- 🔁 Flow Debug Screens  
- 📦 Inventory Updates  
- ✉️ Email Templates:  
  - Order Confirmation  
  - Low Stock Alert  
  - Loyalty Upgrade  
> *(Include screenshots in `/images` folder and reference them here)*

---

## 💻 Tech Stack

- ☁️ **Platform**: Salesforce Developer Edition / Trailhead Playground  
- 🧰 **Tools Used**:
  - Flow Builder 🌀  
  - Process Automation ⚙️  
  - Apex Trigger 💻  
  - Reports & Dashboards 📊  
  - Validation Rules 🚫  
  - GitHub for Version Control 🗂️

---

## 🧪 Test Cases

- ✔️ Email validation on customer creation  
- ✔️ Order confirmation flow & email  
- ✔️ Inventory update after order  
- ✔️ Low stock alert via flow  
- ✔️ Loyalty tier update via scheduled flow  

---

## 📫 Contact

Created with 💙 by Amrita Maravi
📧 Email: amritamaravi0609@gmail.com
🔗 LinkedIn:(https://www.linkedin.com/in/amritamaravi/)


## 📄 License

📝 This project is part of the **Salesforce Virtual Internship Program 2025**.  
Feel free to fork, modify, and use it for learning purposes! 🚀
