# 🔐 DummyJSON API Postman Testing Project  

[![Postman](https://img.shields.io/badge/Tested%20With-Postman-orange?logo=postman&logoColor=white)](https://www.postman.com/)  
[![Newman](https://img.shields.io/badge/Run%20With-Newman-blue?logo=node.js&logoColor=white)](https://www.npmjs.com/package/newman)  
[![HTML Reports](https://img.shields.io/badge/Reports-HTML-green?logo=google-chrome&logoColor=white)](#)  
[![License](https://img.shields.io/badge/License-MIT-brightgreen)](LICENSE)  
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red)](#)  

---

This repository contains a **comprehensive API testing suite** for [DummyJSON](https://dummyjson.com) built with **Postman** and executed via **Newman**.  
It demonstrates **authentication flows, CRUD operations, error handling, and automation-ready scripts** for professional QA workflows.

---

## 📂 Project Structure  
```
DummyJSON_API_Project/
├── collections/ # Postman collections
├── environments/ # Postman environment variables
├── reports/ # Newman HTML reports
├── tests/ # Test data/scripts
└── README.md
```


---

## 📌 Test Coverage

**🔑 Authentication**
- Login (valid & invalid credentials)
- Refresh token
- Get profile
- Token expiry checks  

**👥 Users**
- List all users
- Create, Get, Update, Delete user  

**⚠️ Test & Errors**
- Invalid endpoints
- Missing params
- Unauthorized requests  
- Data validation  

**🛠 Utilities**
- Token extraction & reuse
- Random data injection
- Environment variable handling  

---

## 🚀 Features

- 🌐 **Dynamic Variables** – Easy switching between environments  
- ✅ **30+ Test Cases** – Positive & negative scenarios  
- 📊 **HTML Reports** – Visual pass/fail summary  
- 🧪 **Pre & Post Scripts** – Data setup & validations  
- 🔄 **CI/CD Ready** – Run in pipelines  

---

## 🧰 Tools Used

- **Postman** – API request building  
- **Newman** – CLI test execution  
- **newman-reporter-html** – Clean HTML reports  
- **Node.js** – Dependency management  

---

## 📦 Setup & Run  

### 1️⃣ Install Newman & HTML Reporter
```bash
npm install -g newman newman-reporter-html
```
## Example HTML Report

## 🤝 Contributing

- Fork the repo
- Create your branch (git checkout -b feature/new-tests)
- Commit your changes
- Push to the branch
- Open a Pull Request

##  About the QA

# Jubair Rahman

**Software Engineer (QA) | HealthTech | Passionate about testing, tools, and UI quality.**

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jubair-rahman/) [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JubairRahman) [![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/8801645763353)
