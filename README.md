# Redux Bank

This is a simple Redux-based banking application that allows users to create customers and perform banking operations such as depositing money, withdrawing money, requesting loans, and paying off loans.

## Features

The application includes the following features:

- Customer Management: Users can create new customers by providing their full name and national ID.
- Account Management: Users can perform banking operations on customer accounts, including depositing money, withdrawing money, requesting loans, and paying off loans.
- Currency Conversion: When depositing money in a non-USD currency, the application automatically converts the amount to USD using the current exchange rate.

## Technologies Used

The application is built using the following technologies:

- Redux: For state management and maintaining the application's global state.
- React: For building the user interface and components.
- React Redux: For connecting React components with the Redux store.
- Redux Toolkit: A package that simplifies common Redux tasks and provides utility functions.
- JavaScript: The programming language used for implementing the application logic.
- HTML/CSS: For structuring and styling the user interface.

## Setup and Usage

To run the application, follow these steps:

1. Install the required dependencies by running `npm install`.
2. Start the development server using `npm start`.
3. Open your web browser and navigate to `http://localhost:3000` to access the application.

## Code Structure

The codebase is organized as follows:

- `src/features/accounts`: Contains the Redux slice for managing account-related state and actions.
- `src/features/customers`: Contains the Redux slice for managing customer-related state and actions.
- `src/App.js`: The main component that renders the application.
- `src/customerSlice.js`: Defines the Redux slice for the customer state and actions.
- `src/accountSlice.js`: Defines the Redux slice for the account state and actions.
- `src/Customer.js`: A React component that handles customer creation.
- `src/store.js`: Configures the Redux store and combines the reducers.

Feel free to explore the code to understand how the application works and customize it according to your requirements.

**Note:** This README assumes you have a basic understanding of Redux and React. If you're new to these technologies, it's recommended to refer to the official documentation for detailed explanations.

Enjoy using the Redux Banking App!
