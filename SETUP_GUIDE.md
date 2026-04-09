# Setup Guide for AI Patent Drafting Tool Platform

Welcome to the AI Patent Drafting Tool platform! This guide will help you set up the environment and run the application step by step.

## Prerequisites
Before you begin, ensure that you have the following installed:
- **Node.js** (Latest LTS version)
- **npm** (Node Package Manager, comes with Node.js)
- **Git**

You can check if you have these installed by running the following commands:

```bash
node -v
npm -v
git --version
```

## Step 1: Clone the Repository
First, clone the repository to your local machine. Open your terminal and run:

```bash
git clone https://github.com/digitalamit1995-a11y/IPworld.git
```

Change to the repository directory:

```bash
cd IPworld
```

## Step 2: Install Dependencies
Install the necessary dependencies for the project by running:

```bash
npm install
```

## Step 3: Environment Variables
Create a `.env` file in the root of the project directory. You can duplicate the `.env.example` file and update the variables accordingly. Make sure to include:

- `API_KEY` : Your API key for accessing external services
- `DB_CONNECTION_STRING` : Connection string for your database

## Step 4: Build the Project
Build the project using the following command:

```bash
npm run build
```

## Step 5: Running the Application
You can now run the application locally using:

```bash
npm start
```

The application should be accessible at `http://localhost:3000`.

## Step 6: Testing
To run tests, use:

```bash
npm test
```

## Troubleshooting
If you encounter issues, please refer to the common errors section in the documentation or raise an issue on GitHub.

## Conclusion
You are now ready to use the AI Patent Drafting Tool platform! For further assistance, please consult the documentation or community forums.