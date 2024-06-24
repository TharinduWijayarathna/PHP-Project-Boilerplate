# PHP Project Boilerplate

This project is a PHP application boilerplate using Laravel components and Phinx for database migrations.

## Features

- Uses Laravel's Illuminate Collections.
- Phinx for database migrations.
- dotenv-php for environment variables.

## Requirements

- PHP >= 7.4
- Composer

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/php-project-boilerplate.git
   ```

2. **Navigate into the project directory:**

   ```bash
   cd php-project-boilerplate
   ```

3. **Install dependencies:**

   ```bash
   composer install
   ```

## Usage

### Running Migrations

```bash
vendor/bin/phinx migrate
```

### Rolling Back Migrations

```bash
vendor/bin/phinx rollback
```

### Viewing Migration Status

```bash
vendor/bin/phinx status
```

### Creating a New Migration

```bash
vendor/bin/phinx create MyNewMigration
```

### Creating a New Seeder

```bash
vendor/bin/phinx seed:create MyNewSeeder
```

### Running Seeders

```bash
vendor/bin/phinx seed:run
```

### Running Tests

```bash
composer test
```

## Configuration

- Adjust database settings in `phinx.php` and `.env`.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

## License

MIT License. See [LICENSE](LICENSE) for details.

