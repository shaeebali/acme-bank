# Acme Bank

Acme Bank is a simple web application simulating a banking system, built with Node.js, Express, and SQLite for the backend and EJS for rendering the frontend views.

## Features

- **User Authentication**: Secure login and registration system.
- **Account Management**: Users can view account balances, make deposits, and withdrawals.
- **Transaction History**: Displays detailed transaction logs for users.
- **Database**: SQLite is used to store user and transaction data.

## Tech Stack

- **Backend**: Node.js, Express
- **Frontend**: EJS, HTML, CSS
- **Database**: SQLite
- **Templating**: EJS

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/shaeebali/acme-bank.git
cd acme-bank
```

### 2. Install dependencies
```bash
npm install
```

### 3. Set up the database
An example SQLite database (`bank_sample.db`) is provided. If creating a new database, run the necessary migration scripts.

### 4. Run the application
```bash
node app.js
```

Visit `http://localhost:3000` to access the application.

## Project Structure

- **`app.js`**: Main application file for initializing routes and server.
- **`views/`**: Contains EJS templates for the frontend.
- **`public/`**: CSS and client-side assets.

## Future Enhancements

- Add advanced security with two-factor authentication.
- Implement account transfer functionality.

## License

This project is licensed under the MIT License.
