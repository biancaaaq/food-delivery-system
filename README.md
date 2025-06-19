
# Food Delivery System

A simple Java console application that simulates a food delivery platform, using object-oriented principles and JDBC for database persistence.

##  Features

- User, Driver, and Restaurant management
- Product and menu system
- Placing and tracking orders
- Delivery assignment and status updates
- JDBC-based CRUD operations with PostgreSQL
- Audit service that logs actions in CSV
- Interactive console menu for testing

##  Technologies

- Java 17
- JDBC (Database connectivity)
- PostgreSQL
- CSV file handling
- Singleton pattern, interfaces, collections

##  Project Structure

- `models/`: Domain classes (User, Driver, Product, Restaurant, Order etc.)
- `crud/`: JDBC CRUD implementations for each entity
- `service/`: Core business logic (DeliveryService, AuditService)
- `Main.java`: Entry point with an interactive console menu

##  How to Run

1. Create your database and tables (see `schema.sql`).
2. Configure your DB connection in `DatabaseConnection.java`.
3. Run `Main.java` and navigate the console menu.

