# 🛒 NxtTrendz – React eCommerce Application

A full-fledged **React eCommerce web application** built with **React Router, Context API, and JWT authentication**, designed to replicate a modern shopping platform. The project demonstrates secure login, protected routing, product exploration, filtering, and cart management — all crafted with clean, maintainable code.

---

## ✨ Core Features

### 🔐 Authentication & Authorization
- Login functionality with **username & password**.
- JWT Token storage using **js-cookie**.
- **Protected Routes** ensure that only authenticated users can access pages like Products, Cart, and Product Details.

### 🌐 Routing (React Router)
- `/login` → User authentication.
- `/` → Home page.
- `/products` → Product listing with filters & sorting.
- `/products/:id` → Product details page.
- `/cart` → Cart management.
- `*` → 404 Not Found page.

### 🛍 Products Module
- **Product Listing Page** with:
  - Search bar.
  - Category filter.
  - Rating filter.
  - Sorting by price (low-high / high-low).
- **Product Detail Page**:
  - Displays full product information.
  - Add-to-cart functionality.

### 🛒 Cart Module
- Add/remove products.
- Quantity management.
- Total price calculation.
- Persisted cart state using **Context API**.

### 📊 Error & Loading States
- Graceful **failure views** for API errors.
- **No Results** view for empty searches.
- Loading indicators with **react-loader-spinner**.

---

## 🛠 Tech Stack

- **Frontend**: React
- **State Management**: Context API
- **Routing**: React Router
- **Authentication**: JWT (via js-cookie)
- **Styling**: CSS
- **API**: Backend integration via REST API (CCBP backend)

---

## 📂 Project Structure
```bash 
  src/
    │── context/
      └── CartContext.js # Context API for cart management
    │── components/
    │ ├── LoginForm/ # Login screen
    │ ├── Home/ # Landing page
    │ ├── Products/ # Product listing page
    │ ├── ProductItemDetails/ # Product details view
    │ ├── Cart/ # Cart page
    │ ├── FiltersGroup/ # Search, category, and rating filters
    │ ├── ProductCard/ # Reusable product card component
    │ ├── ProtectedRoute/ # Guards private routes
    │ ├── FailureView/ # API error view
    │ └── NotFound/ # 404 error page
    │── App.js # Root component, sets up routes  
    │── App.css # Global styles

```
---

# ⚡️ Installation & Setup Guide

Follow the steps below to set up and run the **NxtTrendz** application on your local machine.

---

## 1. Clone the Repository
```bash
git clone https://github.com/your-username/nxttrendz.git
cd nxttrendz
```

##  2. Install Dependencies
```bash
npm install
```

## 3. Run the Development Server
```bash
npm start
```

### 4. Open in Browser
```bash
Navigate to:
👉 http://localhost:3000
```


## 🔑 Test Credentials

Use the following credentials to explore the application:

- **Username:** `rahul`  
- **Password:** `rahul@2021`

---

# 🚀 Deployment

This project is deployed on **Vercel** for live preview.  
You can access the application here: [https://nxt-trendz-ecommerce-bice.vercel.app/]
