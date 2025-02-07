# SpringCity - Shipment Management System
Link - [Sprintcity](https://frontend-sprintcity.vercel.app/) - (vercel), Backend isn't deployed so you can't access the dashbaord. 
## Project Description
SpringCity is a shipment management system built with Node.js, React, and PostgreSQL. It integrates Cheetah’s API to streamline shipping operations, providing an efficient and scalable solution for businesses. Designed with SOLID principles and MVC architecture, the system ensures maintainability and scalability.

## Table of Contents
- [Features](#features)
- [Usage](#usage)
- [Technology Stack](#technology-stack)
- [Images](#images)
- [Challenges & Future Improvements](#challenges--future-improvements)
- [License](#license)

## Features
- **Full Shipping Lifecycle Management** – Create, track, and update shipments in real time.
- **API Integration** – Seamless integration with Cheetah’s API for automated shipment processing.
- **Role-Based Access Control** – Secure access with user roles for admins, shippers, and customers.
- **Real-Time Shipment Tracking** – Live updates on shipment status with WebSockets.
- **Automated Notifications** – Email and SMS alerts for shipment status changes.
- **Admin Dashboard** – Intuitive interface for managing users, shipments, and analytics.
- **Scalable Architecture** – Follows MVC and SOLID principles for maintainability.

## Usage
- Admins can manage shipments, users, and API settings.
- Users can create and track shipments through the dashboard.
- The system automatically updates shipment status and notifies customers.

## Technology Stack
- **Backend:** Node.js, Express, PostgreSQL
- **Frontend:** React, Redux, MVC
- **Authentication:** JWT, bcrypt
- **API Integration:** [Chita-delivery's](https://chitadelivery.co.il/) API
- **Real-Time Communication:** WebSockets

## Images

### **Admin Homepage**
- Users Manager  
- View separate shipment order lists for each user.  
- Check if a user is approved as a premium user by verifying contract signing status.
![image](https://github.com/user-attachments/assets/aa1d9e1b-3e86-443e-8414-a7f80052e487)

### **Shipments Table**
The shipments table provides a detailed view of all shipment orders, allowing admins to efficiently track and manage deliveries.

#### **Key Features:**
- **User-Based Shipments** – View shipment orders separately for each user.
- **Shipment Type & Status** – Displays whether the shipment is a pickup or delivery and its current status (e.g., "In Progress," "Delivered").
- **Tracking Number** – Each shipment has a unique tracking number for easy identification.
- **Recipient & Date** – Shows the recipient's details and the shipment date.
- **Quick Actions** – Includes options to print a label, cancel an order, or track the shipment on a map.

![Shipments Table](https://github.com/user-attachments/assets/aa1d9e1b-3e86-443e-8414-a7f80052e487)



###  **Mobile homepage**
  
![image](https://github.com/user-attachments/assets/1e4c1b37-7fc8-4032-98d4-d765e6cabc86)

## Challenges & Future Improvements
- **Optimizing API Calls** – Reduce redundant requests for better performance using REDUX for caching.
- **Improved Analytics** – More detailed shipment analytics and reporting.
- **Mobile App Support** – Extend features to mobile platforms.


## License
This project is licensed under the [MIT License](LICENSE).
