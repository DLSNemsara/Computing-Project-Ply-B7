# Protected Area Management System (PAMS) - Horton Plains National Park

## Overview

The **Protected Area Management System (PAMS)** is a comprehensive solution designed to manage visitor data, park resources, and conservation activities at Horton Plains National Park. This system enhances operational efficiency, safety, and community involvement by providing functionalities such as visitor registration, ticket management, ranger coordination, and real-time reporting.

## Key Features

- **Visitor Registration:** A secure and accurate system for visitor registration with data validation.
- **Ticket Management:** Flexible management of ticket types and quantities, with customizable limits.
- **Ranger Coordination:** Improved communication and coordination among park rangers for effective management.
- **Real-time Reporting:** Facilitates quick responses to environmental changes and wildlife observations.
- **Community Engagement:** A platform for local communities to actively participate in conservation efforts.
- **Resource Management:** Transparent financial management and optimized allocation of park resources.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript, jQuery, Bootstrap (Responsive Design)
- **Backend:** Firebase (Realtime Database, Cloud Functions)
- **Payment Integration:** Stripe API for secure payment processing
- **CI/CD:** GitHub Actions for automated testing, deployment, and updates

## System Architecture

- **Client-Server Architecture:** The web interfaces communicate with Firebase services for real-time data storage and processing.
- **Security:** Firebase security rules ensure data integrity and proper access control.
- **Responsive Design:** The frontend is fully responsive, ensuring smooth user experiences across all devices.

## Deployment & Hosting

- **Hosting:** Hosted on Firebase for both the visitor interface and admin dashboard.
- **Production URLs:**
  - Visitor Interface: [visitor-efdf6.web.app](https://visitor-efdf6.web.app/)
  - Admin Dashboard: [management-cad1f.web.app](https://management-cad1f.web.app)
- **Admin Login Credentials:**
  - Email: `hpadmin@gmail.com`
  - Password: `admin456`

## Testing Strategy

- **Unit Testing:** Verifies the correctness of Firebase Cloud Functions and Firestore queries.
- **Integration Testing:** Ensures seamless integration between frontend, backend, and database operations.
- **End-to-End Testing:** Simulates user actions to ensure proper data flow from frontend to backend.

## Dependencies

- **Firebase Realtime Database & Firestore:** For data storage and real-time synchronization.
- **Firebase SDK:** Backend interaction with Firebase services.
- **Stripe API:** For payment processing of park-related transactions.
- **Frontend Libraries:** HTML, CSS, JavaScript, jQuery

## Screenshots

Below are some visuals of the system interfaces:

### Visitor Interface

![Visitor Interface](https://github.com/DLSNemsara/Computing-Project-Ply-B7/blob/main/Visitor/img/Screenshot%20(137).png?raw=true)

### Admin Dashboard

![Admin Dashboard](https://github.com/DLSNemsara/Computing-Project-Ply-B7/blob/main/Visitor/img/UI7%20dashboard.png?raw=true)

## Future Development

- Ongoing improvements for system scalability and performance upgrades.
- Planned integration of advanced analytics for data-driven decision-making.
- Multi-language support to cater to a wider audience.

## Contributors

The following individuals contributed to the development of this project:

- **Sinel Nemsara**
- **Thejan Rajapaksha**
- **Yohan Nanayakkara**
- **Sachitha Eshan**
- **Charith Bandara**
- **Devin Fernando**

## License

This project is licensed under the **MIT License**.
