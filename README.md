# 🧪 Postman API Testing Projects

This repository showcases a series of **Postman API Testing Projects** developed as part of my learning journey and certification path. These projects demonstrate end-to-end testing skills across REST and SOAP APIs, utilizing tools such as **Newman**, **Postman Scripting**, and **HTML Extra Reporting**.

---

## 📚 Project List

| Project                                                         | Type | Description                                                        |
| --------------------------------------------------------------- | ---- | ------------------------------------------------------------------ |
| [Project 1: Library API](./postman-library-api-v2)              | REST | Digital library simulation with authentication and test validation |
| [Project 2: SOAP API - Number to Words](./soap-number-to-words) | SOAP | Conversion of numbers to English words via DataAccess SOAP service |
| [Project 3: RESTful Booker](./restful-booker)                   | REST | Booking system API tests covering full CRUD and auth flow          |
| [Project 4: E-commerce Store Management](./ecommerce-api-store) | REST | CRUD, filtering, auth, performance and DDT on Fake Store APIs      |

---

## 🔍 Key Skills Demonstrated

* ✅ REST & SOAP API testing
* 🔐 Authentication (Token, Basic Auth)
* 🧪 JavaScript-based assertions (`pm` API)
* 📤 Newman CLI execution
* 📊 HTML Extra Reporter for dashboards
* 🔁 Variable chaining and data-driven testing
* ⏱️ Performance testing

---

## 📈 Newman Dashboards (Snapshots)

### 🏨 RESTful Booker API Test Result

![Booker Dashboard](https://github.com/ChiragRathava29/Postman-API-Testing-Projects/blob/master/Project%203%20-%20RESTful%20Booker%20API%20Testing/Newman/screenshot-newman-dashboard.png)

### 🛒 E-commerce Store API Test Result

![E-commerce Dashboard](https://github.com/ChiragRathava29/Postman-API-Testing-Projects/blob/master/Project%204%20-%20E-commerce%20Store%20Management%20API%20Testing/Newman/ecommerce-newman-report.png)

---

## 🚀 Running Tests via Newman CLI

To execute any Postman collection from the terminal:

```bash
newman run "<collection_file>.postman_collection.json" \
  --environment "<env_file>.postman_environment.json" \
  --reporters cli,htmlextra
```

To install the extra HTML reporter:

```bash
npm install -g newman-reporter-htmlextra
```


---

## 👨‍💻 Author

**Mahesh M**


---

Happy Testing! 🚀
