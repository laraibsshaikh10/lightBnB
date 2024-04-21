# LightBnB
Welcome to LightBnB - a revolutionizing platform in the travel industry allowing homeowners to rent out their properties to vacationers!

## Introduction
LightBnB is an innovative platform that allows travellers to find accomodations alternative to the traditional accomodations such as hotels, motels and breakfasts. It allows homeowners to list their properties for short-term rentals and connects travelers with unique and personalized lodging options.

## Getting Started
To get started with LightBnB, follow these steps:

### 1. Clone the repository: 

```javascript
mkdir lightBnB
cd lightBnB
mkdir LightBnB_WebApp
cd LightBnB_WebApp
touch database.js

npm init -y
npm install pg
```
```
git clone https://github.com/laraibsshaikh10/lightBnB/tree/master/LightBnB_WebApp 

```

### 2. Database Setup: 
Set up the database by executing the SQL scripts provided in the database directory. Make sure to create the necessary tables and relationships according to the ERD.
```
startpostgres
psql
CREATE DATABASE lightbnb
\c lightbnb
```
### 3. Create Tables based on ERD
Create tables called users, properties, reservations and property_reviews 

### 4. Adding Fake Data: 
Populate the database with fake data for testing purposes. Run each file within the data folders against the lightbnb database in the psql terminal.

### 5. Testing Queries: 
Start writing and testing queries to ensure that the application functions as expected. Test various scenarios to validate the functionality of different features.

### 6. Add Javascript functionality
To add functionality into the webpage, add routes and modify functions with SQL queries to have the website running. To see the webpage, run the following command:

```
npm run local
```

## Features

### 1. Property Listings: 
Homeowners can list their properties with detailed descriptions, photos, and pricing information.

### 2. Booking Management: 
Travelers can search for available properties based on location and dates, read reviews, see photos of the property and book their stay directly through the platform.

### 3. User Authentication: 
Secure user authentication and authorization mechanisms to ensure data privacy and security.

### 4. Review System: 
Guests can leave reviews and ratings for properties they have stayed in, providing valuable feedback for both homeowners and future guests.

### 5. Contributing
Contributions to LightBnB are welcome! If you have any ideas for new features, improvements, or bug fixes, please submit a pull request or open an issue on GitHub.

## License
This project is licensed under the MIT License.

## Author
Laraib Shaikh

## Acknowledgements
LightBnB is inspired by the growing trend of peer-to-peer accommodation platforms and aims to provide a user-friendly and reliable solution for both homeowners and travelers.


