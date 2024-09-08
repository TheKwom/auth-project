# Secrets - An Authentication Project

A simple application that allows users to register, log in, and store secrets securely.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The "Secrets" project is designed as a practical example to demonstrate authentication mechanisms. It leverages technologies such as OAuth, Passport.js, and password hashing to ensure secure user authentication and secret management.

## Features

- **User Registration and Login:** Securely register and log in users using hashed passwords and OAuth.
- **Secret Storage:** Users can store, view, and manage their secrets in a secure manner.
- **OAuth Integration:** Supports OAuth for authentication with third-party services.
- **Password Hashing:** Utilizes bcrypt or a similar library to hash passwords for security.
- **Session Management:** Manages user sessions to keep track of authenticated users.

## Installation

To get started with the "Secrets" project, follow these steps:

### Prerequisites

- [Node.js](https://nodejs.org/) (v14.x or higher)
- [npm](https://www.npmjs.com/) (Node package manager)

### Installation Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/TheKwom/auth-project.git

2. **Navigate to the project directory:**

   ```bash
   cd auth-project
   
3. **Install dependencies:**

   ```bash
   npm i
   
4.  **Set up environment variables:**

   ```bash
   GOOGLE_CLIENT_ID="your_google_client_id"
   GOOGLE_CLIENT_SECRET="your_google_client_secret"
   SESSION_SECRET="session_secret"
   PG_USER="postgres"
   PG_HOST="localhost"
   PG_DATABASE="secrets"
   PG_PASSWORD="password"
   PG_PORT="5432"
   ```
   Create a .env file in the root of the project and add the following variables:

6. **Run the application:**

   ```bash
   nodemon index.js
The application should now be running on http://localhost:3000

## Usage

1. **Register a new account:**
Navigate to http://localhost:3000/register and fill out the registration form.

2. **Log in:**
Go to http://localhost:3000/login to log in with your credentials.

3. **Store a secret:**
After logging in, navigate to http://localhost:3000/secrets to add and view your secrets.

4. **Log out:**
Click the log-out button available in the user interface.
