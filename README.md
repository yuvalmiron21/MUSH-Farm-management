# 🍄 Mushroom Farm Management System

![Dashboard Preview](assets/dashboard_preview.png)

## Overview
**Mushroom Farm Management System** is a comprehensive, data-driven platform designed to optimize the operations of modern mushroom farms. Built with **Python (PyQt5)** and **Firebase**, it provides real-time tracking of inventory, growing conditions, orders, and customer analytics.

This project demonstrates full-stack capabilities, integrating a desktop GUI with a cloud-based real-time database, ensuring seamless management from spore to shipment.

## 🚀 Key Features
*   **Real-time Dashboard**: Live visualization of revenue, active orders, and bed occupancy rates.
*   **Inventory & Warehouse Management**: Track stock levels of products and raw materials with automated alerts for low stock.
*   **Growing Cycle Tracking**: Monitor specific growing beds through stages (Spawn Run → Pinning → Fruiting → Harvesting).
*   **Order Management System**: End-to-end processing of customer orders with status tracking (Pending → Shipped → Delivered).
*   **Data Analytics**: Visual insights into sales trends and production efficiency using Matplotlib.
*   **User Role Management**: Secure login with role-based access control (Admin vs. Standard User).
*   **Multi-language Support**: Interface available in English, Hebrew, and Arabic.

## 🛠️ Technology Stack
*   **Frontend**: Python, PyQt5 (Custom Widgets, QSS Styling)
*   **Backend/Database**: Firebase Realtime Database (admin SDK)
*   **Data Analysis**: Pandas, Matplotlib, NumPy
*   **Security**: bcrypt for password hashing
*   **Environment**: Cross-platform compatible (Windows/macOS/Linux)

## ⚙️ Installation & Setup

### Prerequisites
*   Python 3.8+
*   A Firebase project with Realtime Database enabled

### 1. Clone & Install
```bash
git clone https://github.com/StartUpYuval/farm-management-MUSH.git
cd farm-management-MUSH
pip install -r requirements.txt
```

### 2. Configure Credentials
The system connects to Firebase. You have two options to provide authentication:

**Option A (Environment Variable - Recommended)**:
Set the `FIREBASE_CREDENTIALS_PATH` environment variable to point to your Service Account JSON file.
```bash
export FIREBASE_CREDENTIALS_PATH="/path/to/your-firebase-adminsdk.json"
```

**Option B (Local File)**:
Place your `farm-management-FireBase_credentials.json` file inside the `db/` directory.
*(Note: The `db/` folder is ignored by git to keep secrets safe.)*

### 3. Run the Application
```bash
python UI/main.py
```

## 👨‍💻 Author
**Yuval Miron**


---
*Developed for the advanced management of agricultural environments.*
