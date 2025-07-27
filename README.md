###SWP-Project Backend - Court Booking System
##📌 Overview
This is the backend system for a badminton court booking platform that supports three types of scheduling:

Fixed Schedule: Book the same court at the same time every week.

Daily Schedule: One-time booking for a specific day.

Flexible Schedule: Choose flexible time slots based on availability.

The system is built to support Users, Court Owners, and Administrators with robust authentication, court management, booking, and revenue tracking features.

##✨ Key Features
#1. Authentication
Register: Create a new account by providing username, password, email, phone number, and full name.

Login: Access the system using registered credentials.

Forgot Password: Reset password via OTP sent to phone or email.

#2. Court Information
Search Courts: Find courts by name, play time, or location.

Filter Courts: Filter results by location, hours of operation, and available play times.

#3. Profile Management
View Profile: Display saved personal information.

Edit Profile: Update user information.

Logout: Securely end the session.

#4. Competitions
Create Competition: Allow customers to organize competitions.

View Competitions: View existing competitions.

Join Competition: Participate in listed competitions.

#5. Court Booking
Fixed Schedule Booking: Reserve a court for the same time slot each week.

Daily Booking: One-time booking for a specific day.

Flexible Booking: Book flexible time slots.

Checkout: View booking information and pay using QR codes.

Booking History: View past bookings and transactions.

Check-in: Confirm arrival at the booked court.

Cancel Booking: Cancel bookings based on policy.

#6. Admin Features
Manage Accounts: View, create, search, and update account statuses.

Manage Clubs: View, create, update, delete, and search clubs.

Revenue Dashboard: View revenue by location.

View All Bookings: Access complete booking history.

Search Bookings: Quickly find specific bookings.

#7. Court Owner Features
Manage Payment Info: View, add, update, and delete payment information.

Manage Court Info: View, create, update, and delete court/location information.

Promo Codes: Create, update, delete, and view promotional codes.

Manage Staff: View, create, update, and search staff accounts.

Manage Scheduling Types: View, create, update, and delete scheduling types.

##🛠 Technology Stack
Language: Java (Spring Boot)
Database: MySQL
Authentication: JWT (JSON Web Tokens)
Other:JPA, Hibernate,Spring Security, VNPay MySQL, Firebase, GitHub, Jira, Reactjs

Payment: QR Code-based checkout flow

Build Tool: Maven

