# Hotel Management System

## Overview

The **Hotel Management System** is a web-based application built using **ASP.NET Core MVC**. It leverages **Entity Framework (Database-First Approach)** and **LINQ** to interact with a SQL database. The system enables customers to place orders, generate bills, and manage menu items dynamically.

## Features

1. **Order Management**: Customers can place orders with multiple menu items.
2. **Billing System**: Automatically generates a bill based on the ordered items.
3. **Menu Report Page**: Displays predefined menus for reference.
4. **Daily Menu Management**: Admin can define and update the menu daily.
5. **User-Friendly UI**: Enhanced with HTML, CSS, and JavaScript for a better user experience.
6. **Menu Management**: You can create menus from the application. Additionally, a Web API (HotelManagementSystem.API) has been created to allow adding, deleting, and editing menus programmatically.

## Core and MVC Architecture

The project follows a **Core and MVC** architecture, ensuring a clean separation of concerns:

1. **Model (M)**

   - Represents the data and business logic of the application.
   - Uses **Entity Framework (Database-First Approach)** for data access.

2. **View (V)**

   - Provides the user interface.
   - Uses **Razor Views** with HTML, CSS, and JavaScript.

3. **Controller (C)**
   - Handles user requests and interactions.
   - Processes data using the **Business Logic Layer (BLL)** and communicates with the database through the **Data Access Layer (DAL)**.

## Implementation Details

- **Multiple Items per Order**: Customers can select multiple menu items in a single order.
- **Quantity Management**: Allows specifying the quantity for each item.
- **Total Bill Calculation**: Computes the total amount dynamically.
- **Database Persistence**: Orders and bills are stored securely in the database.
- **Menu Management via Web API**: The HotelManagementSystem.API allows external applications to add, delete, and edit menus.

## Setup Instructions

### Prerequisites

- Visual Studio (latest version recommended)
- .NET Core SDK
- SQL Server

## 📸 Project Snapshots

### 🏠 Homepage

![Homepage](https://raw.githubusercontent.com/SarveshSS45/HotelManagement/main/HotelManagementSystem/wwwroot/asset/Homepage.png "Homepage")

### 🧾 Customer Page

![Customer Page](https://raw.githubusercontent.com/SarveshSS45/HotelManagement/main/HotelManagementSystem/wwwroot/asset/customer_page.png "Customer Page")

### 🍽️ Menu Page

![Menu](https://raw.githubusercontent.com/SarveshSS45/HotelManagement/main/HotelManagementSystem/wwwroot/asset/menu.png "Menu")

### 📋 Order Page

![Order](https://raw.githubusercontent.com/SarveshSS45/HotelManagement/main/HotelManagementSystem/wwwroot/asset/order.png "Order")

### 📊 Menu Report

![Menu Report](https://raw.githubusercontent.com/SarveshSS45/HotelManagement/main/HotelManagementSystem/wwwroot/asset/menu_report.png "Menu Report")

### 💵 Daily Sales Report

![Sales Report](https://raw.githubusercontent.com/SarveshSS45/HotelManagement/main/HotelManagementSystem/wwwroot/asset/daily_sales_report.png "Sales Report")

## Usage

- Navigate to the **Order Page** to place an order.
- Access the **Menu Report Page** to see predefined menus.
- Admins can **update the menu** on a daily basis.
- Use the **Web API (HotelManagementSystem.API)** to manage menus programmatically.

## Technologies Used

- **ASP.NET Core MVC**
- **Entity Framework (Database-First)**
- **SQL Server**
- **HTML, CSS, JavaScript, jQuery**
- **ASP.NET Core Web API**

## Contact

For any issues or contributions, please reach out via [GitHub Issues](https://github.com/your-repo/issues).
