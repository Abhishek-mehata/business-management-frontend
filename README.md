# Business Management System — Frontend

A modern React-based frontend for a Business Management / ERP system.

The application provides a centralized interface for managing products, categories, suppliers, customers, purchases, sales, inventory, and business reports.

---

## Features

### Authentication

- User login
- User signup
- JWT-based authentication
- Protected application routes
- Logout functionality

### Dashboard

Provides an overview of the business with:

- Total products
- Customers
- Suppliers
- Sales
- Purchases
- Inventory information
- Recent business activity

### Categories

- View categories
- Add categories
- Edit categories
- Delete categories
- Category descriptions

### Products

- View products
- Add products
- Edit products
- Delete products
- Product search
- Category association
- SKU management
- Barcode management
- Purchase price
- Selling price
- Stock quantity
- Reorder level
- Product status

### Suppliers

- View suppliers
- Add suppliers
- Edit suppliers
- Delete suppliers
- Supplier contact information
- Supplier address

### Customers

- View customers
- Add customers
- Edit customers
- Delete customers
- Customer contact information
- Customer address

### Purchases

- View purchase history
- Create purchases
- Edit purchases
- Delete purchases
- Supplier selection
- Invoice management
- Purchase item management
- Automatic purchase total calculation

### Sales

- View sales history
- Create sales
- Edit sales
- Delete sales
- Customer selection
- Invoice management
- Sale item management
- Automatic sale total calculation

### Inventory

- View current inventory
- Search products
- Filter inventory by stock status
- View stock quantity
- View reorder level
- View purchase price
- View selling price
- View inventory value
- Identify low-stock products
- Identify out-of-stock products

### Reports

Business summary containing:

- Total products
- Low-stock products
- Out-of-stock products
- Total customers
- Total suppliers
- Number of sales
- Total sales amount
- Number of purchases
- Total purchase amount
- Current inventory value

---

## Tech Stack

### Frontend

- React
- Vite
- JavaScript
- Tailwind CSS
- React Router
- Axios
- React Icons

### Backend Communication

The frontend communicates with the Business Management REST API through Axios.

---

## Project Structure

```text
src/
├── api/
│   └── axios.js
│
├── assets/
│
├── components/
│   ├── Common/
│   ├── Dashboard/
│   ├── categories/
│   ├── customers/
│   ├── products/
│   ├── purchases/
│   ├── sales/
│   └── suppliers/
│
├── layouts/
│   └── DashboardLayout.jsx
│
├── pages/
│   ├── Categories.jsx
│   ├── Customers.jsx
│   ├── Dashboard.jsx
│   ├── Login.jsx
│   ├── Products.jsx
│   ├── Purchases.jsx
│   ├── Reports.jsx
│   ├── Sales.jsx
│   ├── Signup.jsx
│   └── Suppliers.jsx
│
├── routes/
│   └── router.jsx
│
├── services/
│   ├── authService.js
│   ├── categoryService.js
│   ├── customerService.js
│   ├── dashboardService.js
│   ├── productService.js
│   ├── purchaseService.js
│   ├── reportService.js
│   ├── saleService.js
│   └── supplierService.js
│
├── utils/
│   └── authStorage.jsx
│
├── App.jsx
├── App.css
├── index.css
└── main.jsx
```

---

# 👨‍💻 Author

**Abhishek Mehata**

GitHub:
https://github.com/Abhishek-mehata
