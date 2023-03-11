# Restful-Restaurant
Restful Restaurant is a full-stack application that allows users to add, star, and delete restaurants. The application is divided into two parts: the frontend and the backend.

## Requirements
To run this application, you need to have Node.js installed on your machine, as well as a [Supabase](https://www.supabase.com) account for the database.

## Installation
1. Clone this repository on your machine
git clone https://github.com/7Jay-Lee7/restful-restaurant.git

2. Navigate to the backend folder using the following command:
cd c:\restful-restaurant\backend

3. Install the project dependencies by running the following command:
npm install

4. Set up the .env file with your Supabase credentials:

DB_URL=<your_supabase_url>
DB_KEY=<your_supabase_key>

5. Create a Supabase database and run the following SQL script to create the restaurants table:
CREATE TABLE restaurants (
  id SERIAL PRIMARY KEY,
  name TEXT,
  description TEXT,
  stars INTEGER
);

6. Navigate to the frontend folder using the following command:
cd c:\restful-restaurant\frontend

7.Install the project dependencies by running the following command:
npm install

## Usage
1. Start the backend server by running the following command in the backend folder:
npm run start
The server will start running on http://localhost:3000.

2. Start the frontend server by running the following command in the frontend folder:
npm start
The server will start running on http://localhost:3000.

3. When prompted, type Y and hit Enter to allow the frontend server to run on 3001.

4. Use the web application to perform CRUD operations on restaurants:

5. To create a new restaurant, click on the Add Restaurant button and fill out the form.
6. To view the list of restaurants, click on the View Restaurants button.
7. To star a restaurant, click on the star icon next to the restaurant's name.
8. To delete a restaurant, click on the trash can icon next to the restaurant's name.

## Credits
This project was created by Jay Lee.

License
This project is licensed under the MIT License.
