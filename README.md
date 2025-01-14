# Laravel ElectricSQL Example

![Capture-2024-11-22-151032](https://github.com/user-attachments/assets/91f94c4a-aaf5-42d1-971d-af2b51fac477)

This project is an example of how to use ElectricSQL with Laravel. It is a simple todo list application that allows you to add, edit, and delete todos with a React frontend connected to a Laravel backend with InertiaJS.

This project uses DDEV for local development environment setup.

## Prerequisites

### DDEV Installation

DDEV is required to run this project. To install DDEV:

1. First, install Docker for your operating system (on macOS, I recommend using [OrbStack](https://docs.orbstack.dev/)).
2. Install DDEV by following the instructions for your OS:

-   **macOS (with Homebrew):**
    ```bash
    brew install ddev/ddev/ddev
    ```
-   **Windows and other systems:**
    Visit the [official DDEV installation guide](https://ddev.readthedocs.io/en/stable/users/install/) for detailed instructions.

## Project Setup

1. Clone this repository:

```bash
git clone https://github.com/braedencrankd/electric-laravel-example.git
```

2. Run `ddev start` to start the development environment.

3. Run `ddev composer install` to install the dependencies.

4. Run `ddev npm install` to install the dependencies.

5. Run `cp .env.example .env` to copy the environment variables.

6. Run `ddev artisan key:generate` to generate the application key.

7. Run `ddev artisan migrate:fresh --seed` to run the migrations.
