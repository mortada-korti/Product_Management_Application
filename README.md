# Scandiweb Junior Developer Test

This is a product management web application developed as part of the Scandiweb Junior Developer recruitment process.

## 📋 Project Overview

The application allows users to:
- View a list of products
- Add new products of different types (DVD, Book, Furniture)
- Mass delete selected products

Each product type includes specific attributes:
- **DVD**: Size (MB)
- **Book**: Weight (KG)
- **Furniture**: Dimensions (HxWxL)

## 🚀 Technologies Used

- **PHP** (Object-Oriented Programming)
- **MySQL**
- **React.js**
- **HTML/CSS**
- **JavaScript**

## 🎯 Features

- Dynamic form rendering based on selected product type
- Data validation for all fields before submission
- Unique SKU enforcement
- Mass deletion of selected products
- Fully responsive and user-friendly interface

## 📁 Project Structure
```
/
├── backend/ │
├── classes/ # PHP OOP classes │
├── config/ # DB connection │ └── index.php # Entry point
├── frontend/ │
├── public/ # React build output │ └── src/ # React components │ └── ...
├── database/ │ └── schema.sql # MySQL schema └── README.md
```
## 🛠 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/mortada-korti/ScandiWeb_Junior_Test.git
   ```
2. **Configure the backend**

Import the SQL schema from `database/schema.sql` into your MySQL database.

Update your DB credentials in `backend/config/db.php`.

3. **Run the frontend**
   ```bash
   cd frontend
   npm install
   npm start
   ```
   
4. **Access the App**

Product List: `http://localhost:3000/`

Add Product: `http://localhost:3000/add-product`

✅ Auto QA Testing
Before submission, the project was tested using the official Scandiweb AutoQA tool and passed all tests.

📄 License
This project is developed for recruitment testing purposes only.
