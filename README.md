# Bookstore Project

This is a Laravel-based Bookstore web application. The project provides a platform to manage books and users, supporting CRUD operations, authentication, and a modern frontend powered by Vite.

## Features

- User registration and authentication
- Book management (create, read, update, delete)
- Database migrations and seeders for easy setup
- RESTful controllers for clean code structure
- Blade templating for dynamic views
- Modern asset bundling with Vite
- Pest for testing

## Project Structure

- `app/Models/` - Eloquent models for Book and User
- `app/Http/Controllers/` - Controllers for handling requests
- `database/migrations/` - Database schema migrations
- `database/seeders/` - Seeders for populating the database
- `resources/views/` - Blade templates for UI
- `routes/web.php` - Web routes
- `public/` - Publicly accessible files and entry point

## Getting Started

### Prerequisites
- PHP >= 8.1
- Composer
- Node.js & npm

### Installation
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd bookstore_project
   ```
2. Install PHP dependencies:
   ```sh
   composer install
   ```
3. Install Node.js dependencies:
   ```sh
   npm install
   ```
4. Copy the example environment file and set your configuration:
   ```sh
   cp .env.example .env
   ```
5. Generate application key:
   ```sh
   php artisan key:generate
   ```
6. Run migrations and seeders:
   ```sh
   php artisan migrate --seed
   ```
7. Start the development server:
   ```sh
   php artisan serve
   ```
8. In a separate terminal, start Vite:
   ```sh
   npm run dev
   ```

## Running Tests

Run the test suite using Pest:
```sh
./vendor/bin/pest
```

## License

This project is open-source and available under the [MIT license](LICENSE).
