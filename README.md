## 🔹 README.md

# 🚀 PHP: The Right Way – Starter Project This is a **basic PHP project** created step by step by following the guidelines from *PHP: The Right Way*.  
It’s designed to be a **clean, minimal, and didactic example** of how to start a PHP project from scratch, using modern best practices.

--- ## 📂 Project Structure` 

project/  
│── public/ # Public files (index.php is the entry point)  
│── src/ # Application logic (classes, database, models)  
│── views/ # Templates (presentation layer)  
│── tests/ # Unit tests  
│── vendor/ # Composer dependencies  
│── composer.json # Dependency manager config

 ## ⚡ Features 
 - ✅  **PSR-4  Autoloading**  with  Composer  -  
 - ✅  **Clean  project  structure**  based on PHP:  The  Right  Way  -  
  - ✅  **PDO  database  connection**  with  safe  queries  -  
 - ✅  **Basic  MVC  separation**  (Model  +  View  +  Controller  approach)  
 -  ✅  **Ready  for  expansion**  with  routing,  templating,  and  testing  
-  ✅  **Lightweight  &  beginner-friendly** --- ## 🔧 Getting Started  
### 1. Clone the Repository  
`git  clone  https://github.com/tiago-prog/php-do-jeito-certo.git  `

*And*

`cd  php-do-jeito-certo`

### 2. Install Dependencies

`composer install` 

### 3. Run the PHP Built-in Server

`php -S localhost:8000 -t public` 

Visit 👉 `http://localhost:8000`

----------

## 🗄 Database Example (PDO)

By default, the project uses **PDO** to safely connect to a MySQL database.  
Edit the credentials in `src/Database.php` before running queries.

`$pdo = new  PDO('mysql:host=localhost;dbname=mydb;charset=utf8mb4', 'user', 'password');` 

----------

## 🌱 How to Grow This Project

-   Add a **router** (Slim, FastRoute, or Symfony Routing)
    
-   Use **Twig** for advanced templating
    
-   Write **tests with PHPUnit**
    
-   Containerize with **Docker** for easier deployment
    

----------

## 📖 Resources

-   [PHP: The Right Way](https://phptherightway.com/)
    
-   [Composer](https://getcomposer.org/)
    
-   [PSR Standards](https://www.php-fig.org/psr/)
    
-   [Clean Code PHP](https://github.com/jupeter/clean-code-php)
    

----------

## 🤝 Contributing

Feel free to fork this project, open issues, or submit pull requests.  
This project is meant for **learning, experimenting, and growing** together with the PHP community.

----------
