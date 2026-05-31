# ⛽ Petrol Management System (PMS)

A comprehensive Fuel Station Management Solution built with Laravel, React, TypeScript, Inertia.js, and MySQL to automate and streamline fuel station operations. The system manages inventory, purchases, sales, customers, vehicles, stations, pumps, nozzles, staff, accounting, and business reporting from a centralized dashboard.

---

## 🚀 Tech Stack

### Backend
- Laravel 12
- PHP 8+
- Eloquent ORM
- RESTful Architecture
- Laravel Middleware
- Authentication & Authorization

### Frontend
- React
- TypeScript
- Inertia.js
- Tailwind CSS

### Database
- MySQL

### Deployment
- CPanel/MilesWeb

---

# 📌 Key Features

## 📊 Executive Dashboard

Provides real-time business insights:

- Today's Revenue
- Today's Profit
- Cash In Hand
- Bank Balance
- Customer Outstanding Amount
- Shift Performance
- Payment Split Analysis
- Operational Statistics

---

## 🏢 Party Management

Manage fuel suppliers and vendors.

### Features
- Supplier Registration
- Vendor Management
- GST Information
- Contact Details
- Supplier Tracking

---

## 👥 Customer Management

Manage individual and corporate customers.

### Features
- Customer Registration
- Corporate Customer Support
- GST Management
- Customer Outstanding Tracking
- Customer Ledger

---

## 🚚 Vehicle Management

Associate vehicles with customers.

### Features
- Vehicle Registration
- Vehicle-Customer Mapping
- Fuel Type Assignment
- Active/Inactive Status
- Vehicle Validation During Sales

---

## ⛽ Product Management

Manage fuel and lubricant products.

### Features
- Petrol
- Diesel
- Lubricants
- Product Categories
- Purchase Price Management
- Sale Price Management
- Product Status Management

---

## 📦 Purchase Management

Manage inventory purchases from suppliers.

### Features
- Purchase Entry Creation
- Supplier Selection
- Bill Number Tracking
- Reference Number Tracking
- Multiple Product Purchase
- Automatic Inventory Updates
- Purchase History

---

## 💰 Sales & Billing

Create fuel sales invoices and process payments.

### Features
- Customer Selection
- Vehicle Selection
- Product Selection
- Nozzle Selection
- Quantity-Based Sales
- Invoice Generation
- Payment Processing
- Sales History

### Supported Payment Methods
- Cash
- Card
- UPI
- RTGS

---

## 📑 Accounts Management

Manage financial transactions and ledgers.

### Modules

### Supplier Payments
- Pending Invoice Tracking
- Supplier Settlement

### Customer Collections
- Receivable Tracking
- Payment Collection

### Contra Entries
- Cash Transfer
- Bank Transfer

### Expenses
- Expense Recording
- Expense Tracking

---

## 🏭 Station Management

Manage multiple fuel stations.

### Features
- Station Registration
- Location Management
- Station Statistics
- Station-wise Operations

---

## ⛽ Pump Management

Manage fuel dispensing pumps.

### Features
- Pump Registration
- Station Assignment
- Pump Tracking
- Search & Filter

---

## 🔥 Nozzle Management

Manage dispensing nozzles and fuel mapping.

### Features
- Nozzle Registration
- Pump Assignment
- Product Mapping
- Meter Tracking
- Flow Monitoring

---

## 👨‍💼 Staff Management

Manage station personnel.

### Features
- Staff Registration
- Station Assignment
- Personnel Tracking
- Contact Information

---

## 🕒 Shift Management

Handle daily fuel dispensing operations.

### Features
- Shift Start
- Shift End
- Staff Assignment
- Nozzle Assignment
- Meter Reading Tracking
- Shift Reconciliation

---

## 📈 Reports & Analytics

Generate detailed business reports.

### Available Reports

- Sales Reports
- Purchase Reports
- Customer Reports
- Inventory Reports
- Payment Reports
- Collection Reports
- Contra Reports
- Expense Reports

### Features

- Date Range Filtering
- Export Functionality
- Financial Analysis
- Operational Insights

---

# 🔄 Business Workflow

```text
Supplier
    ↓
Purchase Entry
    ↓
Inventory Stock
    ↓
Product Allocation
    ↓
Pump
    ↓
Nozzle
    ↓
Sales Transaction
    ↓
Invoice Generation
    ↓
Customer Payment
    ↓
Accounts & Reports
```

---

# 🏗️ Project Structure

```text
Dashboard
│
├── Party Management
├── Customer Management
├── Vehicle Management
├── Product Management
├── Purchase Entry
├── Sales & Billing
├── Accounts
├── Stations
├── Pumps
├── Nozzle Management
├── Staff Management
├── Shift Operations
└── Business Reports
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/pms.git
```

```bash
cd pms
```

## Install Dependencies

```bash
composer install
```

```bash
npm install
```

## Environment Setup

```bash
cp .env.example .env
```

```bash
php artisan key:generate
```

## Database Setup

Update database credentials inside `.env`

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=pms
DB_USERNAME=root
DB_PASSWORD=
```

Run migrations:

```bash
php artisan migrate
```

(Optional)

```bash
php artisan db:seed
```

## Start Development Server

```bash
php artisan serve
```

```bash
npm run dev
```

---

# 📋 Core Modules

| Module | Description |
|----------|------------|
| Dashboard | Business overview and KPIs |
| Party Management | Supplier management |
| Customer Management | Customer records and tracking |
| Vehicle Management | Vehicle registration and assignment |
| Product Management | Fuel and lubricant inventory |
| Purchase Entry | Supplier purchase transactions |
| Sales & Billing | Fuel sales and invoice generation |
| Accounts | Payments, collections, contra, expenses |
| Stations | Fuel station management |
| Pumps | Pump registration and assignment |
| Nozzles | Nozzle-product mapping |
| Staff | Personnel management |
| Shifts | Shift monitoring and reconciliation |
| Reports | Business analytics and reporting |

---

# 🔒 Security Features

- Server-Side Validation
- CSRF Protection
- Authentication Middleware
- Input Sanitization
- Secure Database Operations
- Route Protection

---

# 📈 Future Enhancements

- Mobile Application
- QR-Based Payments
- SMS Notifications
- WhatsApp Invoice Delivery
- Fuel Tank Monitoring
- IoT Pump Integration
- Advanced Analytics Dashboard
- Multi-Branch Management

---

# 👨‍💻 Author

**Abhisek Pradhan**

Full Stack Developer

### Skills

- Laravel
- React
- TypeScript
- Inertia.js
- MySQL
- REST APIs
- RBAC Systems
- Real-Time Applications

---

## Project Summary

Petrol Management System (PMS) is a production-grade web application designed to automate and manage complete fuel station operations, including inventory management, fuel sales, supplier and customer tracking, station management, accounting, shift monitoring, and business reporting through a modern and responsive dashboard.
