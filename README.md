Car-Rental Website is a platform designed for renting vehicles, focused on suppliers. It includes a backend system for managing car fleets and bookings, along with a frontend interface for users to browse and rent cars.

This platform supports multiple suppliers, allowing each one to handle their own fleet and bookings through the backend. However, it can also be configured for a single supplier or function as a car rental aggregator.

From the backend, administrators can create and manage:

Suppliers

Cars

Locations

Customers

Bookings

When a new supplier is added, an email invitation is automatically sent, prompting them to create their account so they can access the backend and manage their listings.



Table of Content
Requirements

Installation

Database

Table

Car Listing Page

Demo

Requirements
XAMPP must be installed to run this project.

The project is designed to work on a localhost server.

Installation
Install XAMPP on your machine.

Launch XAMPP and start both Apache and MySQL services.

Clone or move the project files into the htdocs folder (XAMPP root directory).

Open the project in your browser via XAMPP.

Import the SQL file from the database folder into your local MySQL using phpMyAdmin.

Open your browser and go to localhost:8080.

That's it! The project should now be up and running.

Database
The database folder is named carrental.

The SQL file is named carrental.sql.

It's stored in the root directory of your XAMPP server.

The database needs to be imported using phpMyAdmin or another MySQL client.

This project uses MySQL as its database.

Table
The database contains a table named carrental with the following structure:

id: INTEGER PRIMARY KEY AUTO_INCREMENT

user_email: VARCHAR(100)

vechile_id: int(11)

FromDate: varchar(20)

ToDate: varchar(20)

message: varchar(255)

Status: int(11)

Car Listing Page
The car listing page includes a search bar and a listing table.

The search bar comes with a button to trigger searches.

Users can search for cars using this input.

Only available cars will be displayed on the listing page.

