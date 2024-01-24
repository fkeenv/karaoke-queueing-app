# Karaoke Queueing Application

A web application built with Laravel and Nuxt.js that allows users to request songs like karaoke.

## Technologies Used

- Laravel - Backend framework for building the API.
- Nuxt.js - Frontend framework for building the user interface.
- MySQL - Database system for storing movie and request data.

## Requirements

- PHP 8.1 or higher
- Bun 1.0.19 or higher
- MySQL 8 or higher

## Installation

1. Clone the repository:

```
git clone https://github.com/fkeenv/movie-request-app.git
```

2. Install the backend dependencies:

```
cd movie-request-app/server
composer install
```

3. Set up the database:

- Create a new MySQL database for the application.
- Update the `.env` file with your database credentials:

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password
```

4. Run database migrations:

```
php artisan migrate
```

5. Install the frontend dependencies:

```
cd ../frontend
yarn install
```

6. Start the application:

```
yarn dev
```

7. Access the application in your browser at `http://localhost:3000`.

## Contributing

Contributions are welcome! If you find any issues or want to add new features, please submit an issue or a pull request.
