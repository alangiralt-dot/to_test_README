# mysql-structure
This repository contains the design, relational data modeling, and strict structural optimization for two complete management systems:

*   **Cul d'Ampolla Optician**: Design and data modeling of the relational database to manage clients, suppliers, employees, and custom-made prescription glasses sales for the "Cul d'Ampolla" optician shop.
*   **Pizzeria**: Design, normalisation, and scalable lookup table architecture for an e-commerce platform managing customer address details, multi-store employee task allocation (cooks and drivers), dynamic pizza profiling with categories, and strict one-to-one home delivery tracking.


## Built With
- Database: MySQL (v8.0+)
- Character Set: utf8mb4
- Design Tool: PlantUML

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ander-luro/task1-sprint2.git
2. Press the button Start to initialize MySQL:
   <div><img src="docs/xampp_mysql_start.png" alt="start button" width="500"></div>
3. Open the Shell:
   <div><img src="docs/xampp_shell.png" alt="shell button" width="500"></div>
4. Open MariaDB terminal via XAMPP:
   ```bash
   mysql -u root -p
   ```
5. Execute the SQL script:
   ```sql
   SOURCE C:\xampp\htdocs\task1-sprint2\Level1\exercise1\optica.sql
   ```
   ```sql
   SOURCE C:\xampp\htdocs\task1-sprint2\Level1\exercise2\pizzeria.sql
   ```
