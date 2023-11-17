# A Full-stack web application in React and Laravel REST API.

This is a repository for my personal portfolio built using Laravel as the backend and React as the frontend.

## Installation

1. Clone this repository to your local system:

    ```bash
    git clone https://github.com/ChristopherIndraBhagaskara/laravel-react-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd laravel-react-app
    ```

3. Install dependencies using Composer for the backend and npm (or yarn) for the frontend:

    ```bash
    composer install
    npm install
    ```

4. Copy the `.env.example` file to `.env` and configure the database and other settings:

    ```bash
    cp .env.example .env
    ```

5. Generate the application key and run migrations:

    ```bash
    php artisan key:generate
    php artisan migrate
    ```

6. Run the Laravel and React servers:

    ```bash
    php artisan serve
    npm run dev
    ```

    The application can be accessed at [http://localhost:8000](http://localhost:8000).

## What I Learned

Throughout the development of this portfolio, I gained valuable experience and learned the following:

### React

-   Worked extensively with Context API to manage global state.
-   Implemented functional components and used React Hooks for state management.
-   Utilized React Router for navigation and created protected routes.
-   Implemented multiple layouts for different sections of the application.
-   Connected to external APIs to fetch and display data.
-   Implemented authentication mechanisms to handle user login/logout.

### Laravel

-   Created secure Login and Registration API endpoints.
-   Implemented basic CRUD API endpoints for data manipulation.
-   Utilized Form Requests for validating and handling incoming data.
-   Created API Resources for transforming data before sending responses.
-   Deployed the application in a production environment.
-   Used SSH for remote server access and deployment.
-   Managed version control with Git, including cloning repositories.
-   Configured and connected to a MySQL database for data storage.

## Project Structure

-   `/`: Directory containing Laravel backend code.
-   `/react`: Directory containing React frontend code.

## Technologies Used

-   **Backend**: Laravel version 10.32.1
-   **Frontend**: React version 18.2.0
-   **Database**: MySQL
