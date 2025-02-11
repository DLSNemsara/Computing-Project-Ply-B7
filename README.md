# Protected Area Management System (PAMS) - Horton Plains National Park

## Overview

The Protected Area Management System (PAMS) is a comprehensive solution for managing visitor data, park resources, and conservation activities at Horton Plains National Park. The system provides functionalities for visitor registration, ticket management, ranger coordination, and real-time reporting, improving efficiency, safety, and community involvement.

## Key Features

- **Visitor Registration:** Accurate and secure registration with data validation.
- **Ticket Management:** Manage ticket types and quantities with customizable limits.
- **Ranger Coordination:** Improved communication and coordination among park rangers.
- **Real-time Reporting:** Facilitates fast responses to environmental and wildlife observations.
- **Community Engagement:** Provides a platform for local communities to participate in conservation efforts.
- **Resource Management:** Transparent financial management and optimized resource allocation.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript, jQuery, Bootstrap (Responsive Design)
- **Backend:** Firebase (Realtime Database, Cloud Functions)
- **Payment Integration:** Stripe API for payments
- **CI/CD:** GitHub Actions for automated testing, deployment, and updates

## System Architecture

- **Client-Server Architecture:** Web interfaces interact with Firebase services for real-time data storage and processing.
- **Security:** Firebase security measures ensure data integrity and access control.
- **Responsive Design:** Frontend interfaces are fully responsive, ensuring smooth user interaction on all devices.

## Deployment & Hosting

- **Hosting:** Firebase Hosting for both visitor interface and admin dashboard.
- **Production URLs:**
  - Visitor Interface: [visitor-efdf6.web.app](https://visitor-efdf6.web.app/)
  - Admin Dashboard: [management-cad1f.web.app](https://management-cad1f.web.app)
- **Credentials for Admin Login:**
  - Email: `hpadmin@gmail.com`
  - Password: `admin456`

## Testing Strategy

- **Unit Testing:** Verifies the correctness of Firebase Cloud Functions and Firestore queries.
- **Integration Testing:** Ensures seamless interaction between frontend, backend, and database operations.
- **End-to-End Testing:** Simulates user actions to verify complete data flow from frontend to backend.

## Dependencies

- **Firebase Realtime Database and Firestore:** Data storage and real-time synchronization.
- **Firebase SDK:** Backend handling and interaction with Firebase services.
- **Stripe API:** Payment processing for park-related transactions.
- **Frontend Libraries:** HTML, CSS, JavaScript, jQuery

## Screenshots

Here are some visuals of the system interfaces:

### Visitor Interface

![Visitor Interface](<C:/Users/User/Documents/Projects/Computing-Project-Ply-B7/Visitor/img/Screenshot%20(137).png>)

### Admin Dashboard

![Admin Dashboard](C:/Users/User/Documents/Projects/Computing-Project-Ply-B7/Visitor/img/UI7%20dashboard.png)

## Future Development

- Ongoing enhancements in system scalability and technological upgrades.
- Planned integration of advanced analytics for data-driven decision-making.
- Multi-language support to cater to a wider audience.

## License

This project is licensed under the MIT License.
