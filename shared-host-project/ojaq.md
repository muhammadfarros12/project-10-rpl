# List Library App
This web application is designed to allow users to list and view books in a library. It features a CRUD functionality for the admin role, allowing the admin to manage the books available in the library, and a login and registration system for users to access the library.

## Features
* Users can view all books available in the library  
* Admin can add new books to the library  
* Admin can edit existing books in the library  
* Admin can delete books from the library  
* Login and registration system for users to access the library  
* Logout functionality to end the user session  
## Technologies Used
This application is built with the following technologies:

* Laravel: A PHP web application framework  
* MySQL: A relational database management system  
* HTML: A markup language used for creating web pages  
* CSS: A stylesheet language used for styling web pages  
* Tailwind CSS: A utility-first CSS framework for quickly building custom designs  
## Documentation
##### Register View
![Register](/shared-host-project/images/register.png)  
##### Login View
![Login](/shared-host-project/images/login.png)  
##### View as User
![View as User](/shared-host-project/images/view%20user.png)  
##### View as Admin
![View as Admin](/shared-host-project/images/view%20admin.png)  
##### Add/Edit Book View
![Add/Edit Book View](/shared-host-project/images/add%3Aedit%20book.png)  

## Installation
1. Clone the repository  
2. Navigate to the root directory of the project in the terminal and run composer install to install the required packages  
3. Create a new database in MySQL and configure the **`.env`** file to use the database  
4. Run **`php artisan migrate`** to migrate the database tables  
5. Run **`php artisan db:seed`** to seed the database with sample data (optional)  
6. Start the server by running php artisan serve  
7. Open a web browser and navigate to **http://localhost:8000** to view the application  
## Credits
This project was developed by [**Abdurrazaq**].