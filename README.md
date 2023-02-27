# Form-Validator-JS-PHP-HTML


Signup Form with PHP and JavaScript Validation
This repository contains a simple signup form implemented using HTML, PHP, and JavaScript. The form collects user input for forename, surname, username, password, age, email, and message.

Files
index.html: The HTML file containing the signup form.
adduser.php: The PHP script that processes the form data and stores it in a database.
script.js: The JavaScript file containing form validation functions.
Form Validation
The form includes basic validation using JavaScript to ensure that the user inputs are valid before submission. The JavaScript functions include the following validations:

Forename and surname: Only letters are allowed.
Username: Only letters and numbers are allowed.
Password: Must contain at least one uppercase letter, one lowercase letter, one number, and one special character.
Age: Must be a number between 18 and 99.
Email: Must be a valid email address.
Message: No special validation is applied.
PHP Processing
The adduser.php file processes the form data and stores it in a database. The PHP function fix_string() is used to ensure that user input is properly formatted to prevent SQL injection attacks.

Security
This code is intended as an example only and is not suitable for production use. It should not be used to handle real user data without further modification to ensure security and data privacy.
Sources: 
Learning PHP,  Mysql & JavaScript
https://www.w3schools.com/default.asp
https://www.php.net/
