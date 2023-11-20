# Django-React Directory

This project is a web application for an online business directory built using Django as the backend framework and React as the frontend library.

## Table of Contents

- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
- [Project Structure](#project-structure)
- [Running the Application](#running-the-application)
- [Contributing](#contributing)

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- [Python](https://www.python.org/) (>=3.9)
- [Node.js](https://nodejs.org/) (>=10.0)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/adiela/django-react-directory.git
    ```

2. Change to the project directory:

    ```bash
    cd django-react-directory
    ```

3. Create virtual environment and activate it
    
    ```bash
    python3.9 -m venv .venv
    source .venv/bin/activate
    ```
5. Install backend dependencies:

    ```bash
    pip install -r backend/requirements.txt
    ```

6. Install frontend dependencies:

    ```bash
    cd frontend
    npm install
    ```

## Project Structure

- The Django backend code is located in the `backend` directory.
- The React frontend code is located in the `frontend` directory.

## Running the Application

1. Start the Django development server:

    ```bash
    python backend/manage.py runserver
    ```

   The backend will be accessible at `http://localhost:8000/`.

2. Start the React development server:

    ```bash
    cd frontend
    npm start
    ```

   The frontend will be accessible at `http://localhost:3000/`.


## Contributing

Feel free to contribute to this project. Kindly maintain the existing code style.

