# Flask Dash CRUD Application

## Features
- Create, Read, Update, Delete operations with MySQL

## Installation Instructions
```bash
pip install -r requirements.txt
```

## Usage Guide
To run the application, follow the steps below:
1. Ensure that you have MySQL installed and running.
2. Update the database configuration in the application settings.
3. Initialize the database using the schema provided below.

## Database Schema for Products Table
```sql
CREATE TABLE products (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    description TEXT,
    price DECIMAL(10, 2) NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

## Quick Start Instructions
1. Clone the repository: `git clone https://github.com/Webismagic/Dash-app.git`
2. Navigate into the project directory: `cd Dash-app`
3. Run the application: `python app.py`

Visit `http://127.0.0.1:8050` in your browser to access the application.