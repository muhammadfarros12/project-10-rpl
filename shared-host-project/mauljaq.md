# TahfidzMonitoring
TahfidzMonitoring is a website designed to input the tahfidz data of the students of IDN Boarding School. It comes with CRUD feature (for user with admin role only) and full authentication feature including login, register, etc. You can register to the TahfidzMonitoring website and access the tahfidz data. Admin user is gained with add, edit, and delete the data which non-admin user can't. TahfidzMonitoring built with Laravel v9 for the back end and TailwindCSS with daisyUI Components for the front end (UI). 
## Access The App
- [TahfidzMonitoring](https://tahfidzmonitoring.maulzzaqi.my.id)
- [Task](https://taskmaul.maulzzaqi.my.id)
## Features
- Users can read the tahfidz database
- Admin users can edit, delete, and edit tahfidz database
- Register or Login with an account (Authentication)
- Password reset
- Total of the tahfidz Data
## Built with
- PHP
- Laravel
- HTML
- TailwindCSS & daisyUI
- MySQL
## Documentation
#### Register View
![Register](/shared-host-project/images/maul-register.png)
#### Login View
![Login](/shared-host-project/images/maul-login.png)  
#### Homepage View
![Homepage View](/shared-host-project/images/maul-homepage.png)
#### Database Index View as Admin
![Database Index View as Admin](/shared-host-project/images/maul-indexadmin.png)
#### Database Index View as non-admin User
![Database Index View as non-admin User](/shared-host-project/images/maul-indexnotadmin.png)
#### Add Data (limited to Admin users only)
![Add Data](/shared-host-project/images/maul-adddata.png)
#### Edit Data (limited to Admin users only)
![Edit Data](/shared-host-project/images/maul-editdata.png)

## Getting Started
1. Clone this project
2. Navigate to the root directory of the project in terminal and run `composer install`
3. Run `cp .env.example .env`
4. Configure the database settings in the .env file
5. Run `php artisan migrate` to create and migrate the database
6. Start the localhost by running `php artisan serve` in the terminal
7. Open a browser and navigate to http://localhost:8000

## Poster
Coming soon!!

## Credit
Made by [maulzzaqi](https://instagram.com/maulzzaqi)