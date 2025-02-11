# Inventory Management System

## Overview
This is a simple **Inventory Management System** built using **Node.js, Express, Sequelize, and PostgreSQL** (hosted on Neon.tech). The system provides an easy way to manage inventory items with basic CRUD operations.

## Features
✅ View all inventory items  
✅ Add new inventory items  
✅ Edit existing inventory items  
✅ Delete inventory items  
✅ Data validation and error handling  
✅ Styled with Bootstrap for a professional look  

## Tech Stack
- **Backend:** Node.js, Express, Sequelize  
- **Database:** PostgreSQL (Neon.tech)  
- **Frontend:** EJS, Bootstrap, HTML, CSS  
- **Tools & Packages:**  
  - `express` (for server handling)  
  - `sequelize` (ORM for PostgreSQL)  
  - `pg` & `pg-hstore` (PostgreSQL client)  
  - `ejs` (Template engine)  
  - `body-parser` (Handling form data)  
  - `cors` (Handling cross-origin requests)  

## Setup Instructions

## 1. Install packages:
    It will be done autonatically just run "npm init -y"
## 2. Open the console in VS code and type :

    "npm start"


## The app will be running at:
🔗 http://localhost:3870

Folder Structure

/inventory-app
│── public/              # Static files (CSS, images)
│── views/               # EJS templates
│   ├── header.ejs       # Header for all pages (Navigation bar)
|   ├── footer.ejs       # Footer for all pages (Name and Student Number)
│   ├── index.ejs        # All items available in inventory
│   ├── add.ejs          # Add new item page
│   ├── edit.ejs         # Edit excisting item page
│── models/              # Sequelize models
│── routes/              # API routes
│── server.js            # Main server file
│── README.md            # Project documentation


# The system corrects the following errors before storing data (As mentioned in instructions):

## Negative Quantity: Changed to 0 if negative.
## Invalid Price Format: Ensures the price is a valid number.
## Duplicate Entries: Prevents adding identical items.
Author
👤 Guragampreet Singh
🎓 Student Number: 8913870
📅 Submission Date: 10/02/2025