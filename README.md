# POS System (Store Billing System)

## Overview
This project is a Point of Sale (POS) system developed using the Model-View-Controller (MVC) architecture in Java. It allows users to manage customers, items, and orders.

## Project Structure
- **pos.mvc**: Main package containing the application entry point.
  - `PosMvc.java`: The main class to run the application.
- **pos.mvc.controller**: Contains the controllers for managing customer, item, and order operations.
  - `CustomerController.java`: Manages customer-related actions.
  - `ItemController.java`: Manages item-related actions.
  - `OrderController.java`: Manages order-related actions.
- **pos.mvc.db**: Database connection management.
  - `DbConnection.java`: Manages the connection to the MySQL database.
- **pos.mvc.lib**: Contains external libraries.
  - `mysql-connector-java-8.0.25.jar`: MySQL connector library.
- **pos.mvc.model**: Data models representing the business entities.
  - `Customer.java`: Represents a customer entity.
  - `Item.java`: Represents an item entity.
  - `Order.java`: Represents an order entity.
  - `OrderDetail.java`: Represents order details.
- **pos.mvc.view**: User interface components.
  - `CustomerView.java`: Manages the customer view.
  - `ItemView.java`: Manages the item view.
  - `OrderView.java`: Manages the order view.

## Requirements
- JDK 17
- MySQL database
- MySQL Connector/J 8.0.25

## Setup
1. Ensure JDK 17 is installed.
2. Set up a MySQL database and update the connection details in `DbConnection.java`.
3. Add the MySQL Connector/J library to the project.
4. Run `PosMvc.java` to start the application.

## Usage
- Manage customers, items, and orders through the respective views.
- Controllers handle the logic and interact with the database to perform CRUD operations.

## License
This project is licensed under the MIT License.
