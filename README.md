# SpringCity - Shipment Management System

[Live Demo](https://frontend-sprintcity.vercel.app/) *(Backend is not deployed, so some functionalites (login,Dashbaord, Tracking) is limited.)*

## 📌 Project Description
SpringCity is a **robust shipment management system** designed for efficiency, scalability, and ease of use. Built with **Node.js, React, and PostgreSQL**, it integrates **Cheetah’s API** for seamless shipping operations. The system follows **SOLID principles and MVC architecture**, ensuring long-term maintainability and performance optimization.

## 📖 Table of Contents
- [Features](#features)
- [Usage](#usage)
- [Images](#images)
- [Technology Stack](#technology-stack)
- [Challenges & Future Improvements](#challenges--future-improvements)
- [License](#license)

## 🚀 Features
- **Full Shipping Lifecycle Management** – Create, track, and update shipments in real time.
- **API Integration** – Seamless connectivity with **Cheetah’s API** for automated shipment processing.
- **Role-Based Access Control (RBAC)** – Secure user access levels for **admins, shippers, and customers**.
- **Real-Time Shipment Tracking** – Live shipment updates using **WebSockets**.
- **Automated Notifications** – Email & SMS alerts for shipment status changes.
- **Admin Dashboard** – Intuitive UI for managing users, shipments, and analytics.
- **Multi-Shipment Cart System** – Order multiple shipments with unique details in a single transaction.
- **Auto-Complete Address Input** – Google Maps API integration for **real-time location suggestions**.
- **Advanced Filtering & Sorting** – Sort shipments by date, status, and user preferences.
- **Optimized Performance with Caching** – Utilizes **Redis caching** to reduce API calls and enhance speed.
  To enhance performance and reduce database load:
   **Frequent API Calls** – Stores shipment tracking data to prevent redundant requests.
   **User Dashboard Data** – Caches shipment lists for faster page loads.
## 🔧 Usage
- **Admins**: Manage shipments, users, and API settings.
- **Users**: Create and track shipments through the dashboard.
- **Automated Updates**: The system **synchronizes shipment status** and sends notifications.
- **Bulk Shipment Processing**: Users can process multiple shipments efficiently via the cart system.

## 🛠 Technology Stack
- **Backend:** Node.js, Express, PostgreSQL
- **Frontend:** React, Redux, MVC
- **Authentication:** JWT, bcrypt
- **API Integration:** [Cheetah-Delivery](https://chitadelivery.co.il/) API
- **Real-Time Communication:** WebSockets
- **Caching:** Redis for **optimized API performance**



## 📸 Images
### **Admin Homepage**
- **User Management** – View and manage users.
- **Premium User Verification** – Check contract signing status.
- **Role-Based Dashboards** – Different views for admins and customers.
![Admin Dashboard](https://github.com/user-attachments/assets/aa1d9e1b-3e86-443e-8414-a7f80052e487)

### **Shipments Table**
- **User-Based Shipments** – Track shipments for each user.
- **Quick Actions** – Print labels, cancel orders, or track shipments.
-  **Advanced Filtering & Sorting**
![Shipments Table](https://github.com/user-attachments/assets/c420685d-9042-4a61-b020-14620c450a47)

### **Order Cancellation Requests**
- **Admin Approval Required** – Users request cancellations, admins approve or reject.
- **Automated Notifications** – Users get email updates.
![Premium Dashboard](https://drive.google.com/uc?id=1Fvwfxq1JgbC65q9Jhrr9Svw3XM-Xp-eU)

### **Auto-Complete Location with Google Maps API**
- **Real-Time Address Suggestions**
- **Auto-Populated Fields**
![Auto-Complete Address](https://drive.google.com/uc?id=1cnmh-hpn9d7lGpBcXkpYZUCBpK3QuJxn)

### **Multi-Shipment Ordering with Cart System**
- **Add multiple shipments with unique details**
- **Flexible address input per order**
![Multi-Shipment Cart](https://drive.google.com/uc?id=19CR7dLHMhyzU1hHrIapCIGMWaYv96gkn)

### **Mobile Homepage**
- **Responsive UI for mobile clients**
![Mobile Homepage](https://github.com/user-attachments/assets/1e4c1b37-7fc8-4032-98d4-d765e6cabc86)

## 🔍 Challenges & Future Improvements
- **Optimizing API Calls** – Further caching improvements using **Redux & Redis**.
- **Enhanced Shipment Analytics** – More detailed reporting & insights.
- **Mobile App Development** – Native **iOS & Android support**.
- **Scaling for multi-tenant B2B** – Enabling multiple businesses to operate independently within the same system.
- **AI-Based Delivery Predictions** – Predict estimated delivery times using **ML models**.

## 📜 License
This project is licensed under the [MIT License](LICENSE).

