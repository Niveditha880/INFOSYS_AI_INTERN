
## 🛒 IntelliCart AI — AI-Based E-Commerce Recommendation System

### 📌 Overview

IntelliCart AI is an intelligent e-commerce platform designed to enhance user shopping experience using multiple machine learning techniques. The system provides personalized product suggestions by combining different recommendation strategies and allows users to dynamically switch between them.

The platform is built using a modern full-stack architecture with a responsive frontend and a scalable backend, demonstrating real-world AI integration in online shopping systems.

---

### ⚙️ Tech Stack

* **Frontend:** React (Vite) with Tailwind CSS
* **Backend:** FastAPI (Python)
* **Machine Learning:** scikit-learn
* **Data Handling:** Pandas, NumPy
* **State Management:** Zustand
* **API Communication:** Axios

---

### 📊 Dataset Details

* ~4000 records of beauty & personal care products
* Includes product details, user ratings, reviews, and tags
* Around 1600+ products and 1600+ users

---

### 🤖 Recommendation Techniques Used

1. **Top Rated (Weighted Scoring Model)**
   Uses a statistical formula to rank products by considering both rating and number of reviews, ensuring fairness.

2. **Content-Based Filtering**
   Recommends products similar to what the user is viewing using TF-IDF and cosine similarity on product features.

3. **Collaborative Filtering**
   Suggests items based on similar users' preferences by analyzing user-product interaction patterns.

4. **Hybrid Model**
   Combines all approaches to generate more accurate and balanced recommendations.

---

### 🚀 Key Features

* 🔄 Switch between different AI recommendation modes
* 🛒 Complete shopping flow (cart, checkout, orders)
* ❤️ Wishlist functionality
* 🔍 Smart search by product, brand, or category
* 📱 Fully responsive design
* 🌙 Dark-themed modern UI
* 💳 Multiple payment options (Card, UPI, COD)
* 🏷️ Coupon system for discounts

---

### 🏗️ System Architecture

* Frontend communicates with backend via REST APIs
* Backend processes data and generates recommendations
* ML models are initialized during server startup
* Data is stored and handled in-memory for fast performance

---

### 💡 Unique Highlights

* Real-time comparison of multiple recommendation algorithms
* No database dependency (lightweight demo model)
* Fast performance using Vite and optimized API calls
* Designed as a scalable base for future production systems

---

### 🎯 Conclusion

IntelliCart AI demonstrates how artificial intelligence can be integrated into e-commerce platforms to deliver personalized shopping experiences. It showcases practical implementation of recommendation systems in a user-friendly environment.

