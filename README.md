# Reservia - Universal Booking System

## Introduction

Reservia is a Java-based desktop application designed to make booking services easier and more convenient. It provides a common platform for booking movies, travel, hotels, and restaurants, along with features for managing bookings, wallet balance, transactions, and user profiles.

This project was developed as a collaborative college project to apply Java programming, GUI development, and database management concepts.

## Features

- **User Account Management:** Create an account, log in, and manage profile details.
- **Multiple Booking Services:** Book movies, travel, hotels, and restaurants.
- **Wallet Management:** Add money and use the wallet balance to make bookings.
- **Transaction History:** View wallet transactions, including money added and amounts spent.
- **Booking Management:** View previous bookings and cancel bookings.
- **Ticket and Receipt Generation:** Download tickets or receipts for bookings.
- **Refund Management:** Receive booking cancellation refunds through the wallet.
- **Database Connectivity:** Store and retrieve user details, booking information, wallet balances, and transaction records.

## Technologies Used

- **Java:** Application logic
- **Java Swing:** Graphical user interface
- **Java AWT:** GUI components, layouts, fonts, and styling
- **MySQL:** Database management
- **JDBC:** Java database connectivity

## Database Design

The application uses a MySQL database named `universal_booking`.

The database includes the following tables:

- `users` - Stores user account details.
- `bookings` - Stores booking information and status.
- `wallet` - Stores user wallet balances.
- `transaction` - Stores wallet and booking transaction records.

## Getting Started

### Prerequisites

Before running the application, make sure you have:

- Java Development Kit (JDK)
- MySQL Server
- A Java IDE, such as Eclipse or NetBeans
- MySQL JDBC driver

### Setup Instructions

1. Clone or download this repository.
2. Open the project in your Java IDE.
3. Create the `universal_booking` database in MySQL.
4. Create the required database tables using the project's SQL script.
5. Configure the database connection with your local MySQL credentials.
6. Ensure the MySQL JDBC driver is added to the project.
7. Run the application's main class to launch Reservia.

**Note:** These instructions may need to be adjusted to match the project's actual folder structure and database connection configuration.

## Project Contributors

This project was developed collaboratively as part of a college project.

- **Team Members:** Yashu Gupta , Joel Daniel
- **My Contribution:** I worked more on the design of the app.

## Future Scope

- Develop a web or mobile version of the application.
- Add more booking services.
- Integrate online payment gateways.
- Introduce email and SMS booking notifications.
- Add offers, discounts, and loyalty rewards.

## Conclusion

Reservia brings multiple booking services together in one desktop application. Through this project, we applied Java programming, GUI development, and database connectivity concepts to build a practical booking management system.

