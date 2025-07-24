# 📝 Spring Boot Quote API with Rate Limiting

This is a simple Spring Boot REST API that returns random motivational quotes.  
It also includes **IP-based rate limiting** using [Bucket4j](https://github.com/bucket4j/bucket4j), and supports **Swagger UI** for API testing.

---

## 🚀 Features

- ✅ Returns a random quote on every API call
- ✅ Limits requests to **5 per minute per IP**
- ✅ Easy to extend with more quotes
- ✅ Swagger UI for documentation and testing

---

## 📦 Technologies Used

- Java 17+
- Spring Boot
- Bucket4j (rate limiting)
- Swagger (OpenAPI 3)
- Maven

---

## 📁 Project Structure

quoteapi/  
├── controller/  
│   └── QuoteController.java  
├── service/  
│   └── QuoteService.java  
├── serviceimpl/  
│   └── QuoteServiceImpl.java  
├── config/  
│   └── BucketConfig.java  
├── ratelimiter/  
│   └── RateLimiterServiceClass.java  
└── QuoteApiApplication.java  


---

## 🔧 Setup & Run

### ✅ Prerequisites

- Java 17+
- Maven
- Postman or browser for testing

### 📥 Clone the repo

```bash
git clone https://github.com/Sanjeev-Uppu/quoteapi.git
cd quoteapi

---

## 🚀 Run the Application

```bash
mvn spring-boot:run

# for running in the browser
http://localhost:9090/api/quotes/random

# Wants to run using swagger
http://localhost:9090/swagger-ui/index.html

---

## 🎬 Final Output Demo

📽️ [Click here to watch the demo video](./demo.mp4)


 



