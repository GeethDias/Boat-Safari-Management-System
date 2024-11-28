# Boat-Safari-Management-System
This project is a web-based management system designed to handle boat safari packages, reservations, user profiles, and other essential functionalities for a seamless user experience.

Features
User Management:

User registration, login, and logout functionalities.
Ability to view and update profile information.
Reservation System:

Add, update, and delete safari reservations.
View a list of user reservations.
Package Management:

View safari packages (e.g., Madhu River, Negombo River, etc.).
Add, edit, or remove package details.
Feedback and Contact:

Update contact and feedback details.
Submit inquiries through a contact form.
File Structure
Key Directories
css/: Contains stylesheets for the web pages.
img/: Stores images used across the website.
js/: Contains JavaScript files for dynamic features.
Core Files
Dashboard.php: Main dashboard for the admin or user interface.
Homepage.php: Landing page of the system.
SignUp.php / SignUp_database_connection.php: User registration functionality.
Reservation.php / Reservation-*.php: Files related to reservation management.
Package*.php: Files for managing safari packages.
contactus*.php: Files for managing user inquiries and feedback.
Installation
Clone this repository:

git clone https://github.com/YourUsername/Boat-Safari-Management-System.git
Set up a local web server (e.g., XAMPP, WAMP, or MAMP) and place the project files in the web server's root directory (e.g., htdocs for XAMPP).

Create a database and import the provided SQL script (if available) to set up the required tables.

Update the database connection details in the PHP files to match your environment:

$servername = "localhost";
$username = "your_username";
$password = "your_password";
$dbname = "your_database";
Start the local server and access the project via your browser:

http://localhost/Boat-Safari-Management-System
Usage
Admin: Manage safari packages, view reservations, and handle user inquiries.
User: Explore available packages, make reservations, and manage personal profile.
