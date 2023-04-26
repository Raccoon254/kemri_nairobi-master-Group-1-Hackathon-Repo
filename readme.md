# EID/VL Dashboard Notification Integration - Group 1
## Introduction
This project is an embedded module for the EID/VL system (https://eiddash.nascop.org/login) that enables users to send notifications directly from the EID/VL Dashboard to the SPICEWORKS helpdesk. The module is built using the Laravel PHP framework and requires PHP 7.2 or 7.3.

Our custom module code can be found between comments that start with @start hackathon edit and @end hackathon edit. This makes it easy for developers to identify and maintain the module code within the larger EID/VL system.

## Features
1-Automatically captures the currently logged-in user's username
2-Allows users to enter their email address
3-Sends notifications to the SPICEWORKS helpdesk
##Setup and Configuration
--Ensure your server is running PHP 7.2 or 7.3
--Clone the repository
--Run composer install to install required dependencies
--Generate a new application key with php artisan key:generate
--Join the project Slack group to get access to the database configuration details. You can join the group using this link: [Slack Group](https://join.slack.com/t/healthithq/shared_invite/zt-1tsw1361v-jESqdUTCAO2X56xLYaopgw)
--Update the .env file with the appropriate database settings and email SMTP configuration
--Locate the module code between the comments @start hackathon edit and @end hackathon edit and customize it [Optional]
--Configure the integration with the SPICEWORKS helpdesk using the provided API keys and documentation
--Create a test dashboard in the SPICEWORKS site
--Run php artisan migrate to set up the database tables
--Run php artisan serve to start the Laravel development server
## Usage
Once the module is set up and configured, Open your localhost server:

1.Access the Login Page and Login
2.Access the Laravel application homepage
3.In the navigation bar, find and click the "Help Desk" tab
4.In the Help Desk dropdown menu, click the "Complaints/Reports" link
5.Fill in the form with the necessary information and submit it
6.Check your SPICEWORKS dashboard to confirm the notification was sent
7.Support and Feedback
8.For any issues, questions, or suggestions, please feel free to contact our support team.

We appreciate your feedback and will work diligently to ensure the continued improvement and success of this module.
