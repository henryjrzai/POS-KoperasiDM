# Laravel 8 - Point of Sale Application (Koperasi Deli Murni)

## Run Locally

Clone the project

```bash
  git clone https://github.com/henryjrzai/POS-KoperasiDM.git project-name
```

Go to the project directory

```bash
  cd project-name
```

-   Copy .env.example file to .env and edit database credentials there

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan migrate:fresh --seed
```

```bash
    php artisan storage:link
```

#### Login

-   email = admin@example.com
-   password = 123
