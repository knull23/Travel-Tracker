# Visited Countries Tracker

This Node.js application is a simple web-based tracker that allows users to keep track of the countries they have visited. Users can add countries they have visited and view a list of their visited countries.

## Features

- Allows users to add and track countries they have visited.
- Supports multiple users, each with their own list of visited countries.
- Uses PostgreSQL to store user and country data.
- Uses Express.js for handling HTTP requests and routing.
- Uses EJS (Embedded JavaScript) as the view engine for rendering dynamic content.

## Setup

1. **Clone the repository:**
```bash
   https://github.com/knull23/Travel-Tracker.git
```
2. **Install dependencies:**
```bash
   install npm init -y
   install express ejs body-parser
   node index.js
```
3. **Set up PostgreSQL:**

- Make sure you have PostgreSQL installed and running on your machine.
- Create a database named `world`.
- Create the required tables by executing the SQL commands in the `database.sql` file.

4. **Configure database connection:**

- Open `index.js` and modify the database connection parameters (`user`, `host`, `database`, `password`, `port`) in the `db` object to match your PostgreSQL configuration.

5. **Run the application:**
```bash
npm start
```
6. **Access the Application:**

Open your web browser and go to `http://localhost:3000` to access the application.

## Usage

- On the homepage, you'll see a list of countries you have visited (if any).
- To add a country you have visited, enter the country name in the input field and click "Add".
- To switch between users or create a new user, use the dropdown menu at the top of the page.

## Contributions
Contributions are welcome! If you find any bugs or want to add new features, feel free to open an issue or submit a pull request.

