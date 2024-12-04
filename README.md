# Cloning Laravel Project

To clone a Laravel project, follow these steps:

1. Open your terminal.
2. Navigate to the directory where you want to clone the project.
3. Run the following command:

```bash
git clone <repository-url>
```

Replace `<repository-url>` with the URL of the Laravel project's repository.

4. Navigate into the cloned project directory:

```bash
cd <project-directory>
```

Replace `<project-directory>` with the name of the cloned project directory.

5. Install the project dependencies:

```bash
composer install
```

6. Copy the `.env.example` file to `.env`:

```bash
cp .env.example .env
```

7. Generate the application key:

```bash
php artisan key:generate
```

8. Run the migrations to set up the database:

```bash
php artisan migrate
```

Your Laravel project should now be set up and ready to use.