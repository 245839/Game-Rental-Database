# Game-Rental-Database
This project features an object-oriented ORACLE database designed for an online game rental system. The database includes structures representing customers, their rental history, and details about available games. The implementation contains triggers, procedures, and functions ensuring the system's proper operation.  

# Features  
-  **User Account Management** – Create, edit, and delete user accounts.  
-  **Game Inventory Management** – Add, edit, and remove game copies from the rental offer.  
-  **Rental History Tracking** – Store and manage user rental history using collections.  
-  **Game Statistics Handling** – Support for online game statistics, including:  
  -- Player profile and game history.  
  -- Player ranking based on performance (tier list).  
-  **Data Browsing with Views** – Simplified data retrieval using predefined views.  
-  **Procedures for Data Management** – Use stored procedures to manage key database operations.  

# Technologies Used
- ORACLE Database (Object-Oriented Features)
- PL/SQL (Procedures, Functions, and Triggers)

# Database Setup
### 1. Requirements  
To run this project, you need:  
- An ORACLE database instance  
- SQL Developer, or any other SQL client supporting ORACLE databases

### 2. Database Initialization  
To set up the database, execute the provided SQL code inside the code:  

```sql
game_rental_database.sql
```
This code will:
- Create necessary database objects (tables, views, procedures, and triggers).
- Populate the database with sample test data.

### 3. How to Use
Once the database is set up, you can:
- Query data using predefined views for easy data browsing.
- Execute procedures to manage users, rentals, and game copies.
- Track player statistics for games that support online rankings.
