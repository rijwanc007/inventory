
# Features
  - Stock Adding
  - Stock Manage / Edit / Add stock to old invoice
  - PDF Generate
  - Supplier Management
  - Supplier Payment Module
  - Settings for brand and style/Product Category Manage
  - Payment method Module

## Run
  Copy .env.example to .env and setup your Database information.

  ``` bash
  # Composer install
  composer install

  # Laravel init
  php artisan key:generate
  php artisan migrate
  php artisan db:seed

  # serve at localhost:8000
  php artisan serve

  # serve with hot reload at localhost:3000
  npm run watch

  ```
