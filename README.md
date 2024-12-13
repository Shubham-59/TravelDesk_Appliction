Travel Desk Application

Overview

The Travel Desk Application is a comprehensive travel management system designed to facilitate employees in applying for travel arrangements, streamline the approval chain process, and provide a centralized platform for travel bookings. The application is developed using:

ASP.NET 8 for the backend API.

ReactJS 16 for the frontend interface.

MySQL as the database.

The application automates the travel request lifecycle, from employee requests to final bookings, ensuring efficiency and accountability.

Key Features

1. Employee Functionality

Apply for Travel: Employees can submit travel requests, specifying destination, dates, purpose, and other details.

View Travel History: Employees can view their past travel requests and statuses.

2. Admin Functionality

Ticket and Hotel Bookings: Admins handle final ticket and hotel bookings based on approved requests.

Manage Employee Requests: Admins can view, approve, or reject travel requests at any stage.

Send Notifications: Notifications (via email) are sent to the concerned employees and managers at each step of the process.

3. Manager Functionality

Approval Workflow: Managers can review and approve/reject travel requests submitted by employees.

Chain System: The application follows a structured approval hierarchy, where managers and admins work collaboratively.

4. Automated Notifications

Email Notifications: Automatic email notifications are sent at key stages (request submission, approval/rejection, final booking).

Workflow

Travel Request Submission:

Employees submit travel requests through the application.

Approval Chain System:

Requests pass through the approval workflow: Manager ➔ Admin.

Final Booking:

Once approved, the admin books tickets, arranges hotel accommodations, and updates the system.

Notifications:

Emails are sent to employees and managers regarding the status of the requests and bookings.

Technology Stack

Backend:

ASP.NET 8: API development and business logic.

Frontend:

ReactJS 16: User interface for employees, managers, and admins.

Database:

MySQL: Data storage for employee records, travel requests, approvals, and bookings.

Email Notifications:

Configured to notify stakeholders at each stage of the process.

Installation and Setup

Backend Setup:

Install ASP.NET 8 runtime.

Set up the API project and configure the database connection string in appsettings.json.

Frontend Setup:

Install Node.js and React dependencies.

Run npm install to install all dependencies.

Start the development server using npm start.

Database Setup:

Install MySQL.

Import the database schema provided in the schema.sql file.

Email Configuration:

Update SMTP settings in the backend for email notifications.

Usage Instructions

Employees:

Log in to the application.

Submit a new travel request.

Track the status of requests.

Managers:

Log in to the manager dashboard.

Review and approve/reject requests.

Admins:

Log in to the admin panel.

Handle final bookings and notify employees.

Future Enhancements

Integration with third-party APIs for real-time ticket and hotel bookings.

Advanced analytics and reporting for travel data.

Mobile application for employees and managers.

Contributors

Ayush and Team

License

This project is licensed under the MIT License.

Contact

For any queries or support, please contact us at Shubhammagrde1995@gmail.com
