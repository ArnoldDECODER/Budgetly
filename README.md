# Budgetly - Financial Management Web Application

## Overview
Budgetly is a modern web application designed to empower users in managing their personal finances effectively. Whether you're tracking income and expenses, setting financial goals, or analyzing spending patterns, Budgetly provides an intuitive interface to help you stay on top of your financial health. Built with advanced technologies, this application offers a seamless experience for both individual users and developers looking to explore its codebase.

## What Does Budgetly Do?
- **Income and Expense Tracking**: Record and categorize transactions to monitor your cash flow in real-time.
- **Financial Goal Setting**: Set and track progress toward savings goals like an emergency fund or a major purchase (e.g., a car down payment).
- **Analytics Dashboard**: Visualize your financial data with interactive charts, including income vs. expenses and goal progress, to gain insights into your spending habits.
- **Offline Support**: Access dummy data when offline, ensuring usability during network disruptions.
- **User Authentication**: Secure login system to protect your financial data, with a test profile available for exploration.

## Live Links
- **Frontend**: The live version of the Budgetly frontend is hosted at [https://budgetly-finance-app.netlify.app/](https://budgetly-finance-app.netlify.app/). Visit this link to explore the application in action.
- **Backend API**: The live backend API is accessible at [https://budgetlybackend.netlify.app/](https://budgetlybackend.netlify.app/). This RESTful API powers the frontend with financial data and authentication services.

## Repositories
The source code for Budgetly is open-source and available on GitHub:
- **Frontend Repository**: [https://github.com/ArnoldDECODER/BudgetlyFrontEnd.git](https://github.com/ArnoldDECODER/BudgetlyFrontEnd.git) - Contains the React-based frontend with advanced features like Hooks, Redux, and React Router.
- **Backend Repository**: [https://github.com/ArnoldDECODER/Budgetlybackend.git](https://github.com/ArnoldDECODER/Budgetlybackend.git) - Houses the RESTful API backend, designed for efficient data management and authentication.

## Getting Started
### Prerequisites
- Node.js and npm installed on your machine.
- Git for cloning the repositories.

### Installation
1. **Clone the Repositories**:
   - Frontend: `git clone https://github.com/ArnoldDECODER/BudgetlyFrontEnd.git`
   - Backend: `git clone https://github.com/ArnoldDECODER/Budgetlybackend.git`
2. **Navigate to Each Directory**:
   - `cd BudgetlyFrontEnd`
   - `cd Budgetlybackend`
3. **Install Dependencies**:
   - Run `npm install` in both the frontend and backend directories.
4. **Start the Backend**:
   - In the `Budgetlybackend` directory, run `npm start` to launch the API (default port may vary; check `package.json`).
5. **Start the Frontend**:
   - In the `BudgetlyFrontEnd` directory, run `npm start` to launch the app at `http://localhost:3000` (or as configured).
6. **Test the Application**:
   - Use the test profile (email: `arnold.mabope@gmail.com`, password: `12345678`) to log in and explore the features.

## Features and Technologies
- **Frontend**: Built with React, utilizing Hooks (`useState`, `useEffect`), Redux for state management, and React Router for navigation. The UI includes dynamic charts powered by Chart.js.
- **Backend**: Implements a RESTful API with endpoints for transactions, goals, and authentication, ensuring efficient data handling.
- **Offline Capability**: Dummy data is stored in `localStorage` and displayed when the API is unavailable, enhancing resilience.
- **Styling**: Custom CSS with a dark theme, complemented by MUI icons for a polished look.

## Testing
- Log in with the test profile: `arnold.mabope@gmail.com` / `12345678` to access the homepage and explore all features.
- Disconnect from the internet to test offline dummy data display.

## Contributing
Contributions are welcome! Please fork the repositories, create a branch for your changes, and submit a pull request. For major changes, open an issue first to discuss.

## License
This project is open-source under the MIT License (details in the repository).

## Contact
For questions or support, reach out to Arnold at [arnold.mabope@gmail.com](mailto:arnold.mabope@gmail.com).

