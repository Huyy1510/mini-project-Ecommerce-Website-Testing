# 🧪 OpenCart Demo QA Mini Project

## 📌 Overview
This is a **QA mini project** to practice **manual testing** on the [OpenCart Demo Website](https://demo.opencart.com/).  
The project covers basic e-commerce features such as registration, login, cart, and checkout.

## 📂 Project Deliverables
- **Test Plan** – Strategy, scope, and resources for testing  
- **Test Scenarios** – High-level testing conditions  
- **Test Cases** – Step-by-step manual test cases  
- **Bug Reports** – List of identified defects with severity  
- **Test Summary Report** – Final execution result  

## 🛠️ Scope of Testing
- **In Scope**:
  - User Registration  
  - User Login  
  - Add to Cart, Update, Remove Items  
  - Checkout Process  

- **Out of Scope**:
  - Real Payment Integration (PayPal, Credit Card)  
  - Mobile App Testing  
  - Performance/Load Testing  

## 📊 Test Execution Summary
- **Total Test Cases**: 12  
- **Executed**: 12  
- **Passed**: 9  
- **Failed**: 3  

## 🐞 Major Bugs Found
1. Checkout allowed with missing address (Critical)  
2. Registration accepted empty password (High)  
3. Cart total not updated when quantity changed (Medium)  

## ✅ Conclusion
The OpenCart Demo still contains **critical functional bugs** in Checkout and Registration.  
It is recommended to fix these before moving to production.

---
