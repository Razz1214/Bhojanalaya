# 🍽️ Bhojnalaya - Digital Canteen Billing System  

## 📌 Project Overview  
**Bhojnalaya** is a **smart canteen management system** designed to eliminate fraud in college canteens. The idea originated from a common **scam** where students were **reusing UPI payment screenshots** to claim multiple meals without actually paying for them.  

To solve this, **Bhojnalaya** introduces a **digital bill generation system** that creates a **QR-coded bill** after a successful payment. This QR code stores order details, payment verification, and a **unique identification number**.  

At the canteen counter, the QR code is **scanned for validation**—ensuring that each meal is served **only once per payment**, thus eliminating the scam.  

## 🎯 Problem Statement  
In many college canteens, students exploited a loophole in the manual billing system by:  
✅ Taking a **UPI payment screenshot** after paying once.  
✅ Showing the same screenshot **multiple times** to collect additional meals.  
✅ Causing **losses to the canteen** due to untracked duplicate claims.  

## 🚀 Solution - How Bhojnalaya Works  
🔹 **Step 1:** A student places an order via the Bhojnalaya system.  
🔹 **Step 2:** After successful UPI payment, the system **generates a unique QR code**.  
🔹 **Step 3:** The QR code contains:  Ordered food items & quantity | Payment confirmation |  A **Unique Identification Number (UIN)** (timestamp-based)  
🔹 **Step 4:** At the canteen counter, staff **scan the QR code** before serving food.  
🔹 **Step 5:** If the bill is **valid and unused**, the meal is served.  
🔹 **Step 6:** Once scanned, the bill is **marked as used** and cannot be reused.   

## 🛠️ Technologies Used  
- **Frontend:** HTML, CSS, JavaScript  
- **QR Code Generation:** JavaScript QR Code API  
- **Storage:** No database was used in this prototype  

## 🚀 Installation & Usage  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/prashant-g0/bhojnalaya_2.0.git
```

### 2️⃣ Open the Project
Simply open `index.html` in any browser to start using Bhojnalaya.

## 🎯 Future Enhancements
🔹 Integrate a real database for better tracking.  
🔹 Implement real-time payment verification APIs.  
🔹 Add admin panel for managing food orders and transactions.

## 📜 License
This project is licensed under the **MIT License**

## Developer
💡 Developed by: **Prashant Gupta**.  
🌟 If you like this project, don't forget to ⭐ star the repository!
