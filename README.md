# Laravel and Vue E-commerce Website
E-commerce application built with Laravel, Vue.js, Tailwind.css and Alpine.js.

## Installation 
You will need MySQL, PHP8.1, Node.js and composer.

### Install Laravel Website + API
1. Download the project (or clone using GIT)
2. Copy `.env.example` into `.env` and configure database credentials
3. Navigate to the project's root directory using terminal
4. Run `composer install`
5. Set the encryption key by executing `php artisan key:generate --ansi`
6. Run migrations `php artisan migrate --seed`
7. Start local server by executing `php artisan serve`
8. Open new terminal and navigate to the project root directory
9. Run `npm install`
10. Run `npm run dev` to start vite server for Laravel frontend

### Install Vue.js Admin Panel
1. Navigate to `backend` folder
2. Run `npm install`
3. Copy `backend/.env.example` into `backend/.env`
4. Run `npm run dev`
5. Open Vue.js Admin Panel in browser and login with created , existing credentials in the database.

## Setting up the database

1. Navigate to the `database/backup` folder in the repository.
2. Download the SQL dump from the `database/backup` folder in the repository.
3. Create a new MySQL database on your local machine.
4. Import the SQL dump into the database using the following command:
`mysql -u username -p database_name < path/to/sql/dump.sql`
5. Replace `username` with your MySQL username, `database_name` with the name of the database you created, and `path/to/sql/dump.sql` with the path to the downloaded SQL dump file.
6. When prompted, enter your MySQL password.
7. The SQL dump should be imported into your local database. You can now use the application with the local database.

