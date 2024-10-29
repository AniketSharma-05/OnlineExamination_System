Online Examination System

Overview

The Online Examination System is a web-based application designed to facilitate online exams. It provides features for students to take exams, view their history, and check their rankings, along with an admin panel for managing the exams and users.

Features

User Features
Home Page: Lists all available exams for students.
Exam History: Allows students to view their previous exam attempts and scores.
Ranking: Displays the ranking of students based on their exam performances.
Sign Out: Enables users to log out from their session.
Additional Features: Includes other functionalities to enhance user experience.

Admin Features

Admin Panel: Accessible to administrators for managing exams and users.
Authentication: Admin login using:
Username: Admin
Password: $_SESSION["key"] = 'sunny7785068889';


Technologies Used

HTML: For the structure of the web pages.
CSS: For styling the application.
PHP: For server-side scripting and database interaction.

Installation

Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/OnlineExamination_System.git
Set Up the Environment

Ensure you have a web server (like XAMPP, WAMP, or LAMP) installed.
Place the cloned repository in the web server's root directory (e.g., htdocs for XAMPP).
Create Database

Create a MySQL database and import the provided SQL file to set up the necessary tables.
Configure Database Connection

Edit the database connection settings in the PHP files to connect to your database.
Access the Application

Open your web browser and navigate to http://localhost/OnlineExamination_System to view the application.
Usage

For Students: Register and log in to take exams, view your history, and check your rankings.

For Admin: Log in with the provided credentials to manage exams and users.

Security

Ensure that sensitive data, such as passwords, are handled securely using hashing techniques.
Use HTTPS to encrypt data transmitted between the client and server.

License

This project is licensed under the MIT License.

Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for discussion.
