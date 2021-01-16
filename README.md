# livewire-skilly-poc

A proof of concept built using Livewire Laravel for an application affectionately named Skilly.

## Set up project environment for development

Install project dependencies via composer.

```bash
composer install
```

When setting up for the first time:

1. Create a .env file in the project root folder (refer to .env.local)

2. Set up your local database and update the .env file

3. Generate a new application key `php artisan key:generate`

4. The easiest way to serve the application is via `php artisan serve`

## Contribution guidelines

Before making any changes it is always a good idea to get the latest version of the main trunk via rebasing.

```git
git pull --rebase origin main
```

Please do not push changes directly into the main branch. To make changes always raise a Pull Request and write tests for your changes.

Let us build something great together!