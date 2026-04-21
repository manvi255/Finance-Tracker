# Personal Finance Tracker

A modern, responsive personal finance management application built with React. This tool helps users track their income and expenses, manage monthly budgets, and visualize their financial health through interactive analytics.

## 🚀 Features

- **Interactive Dashboard**: Get a quick overview of total income, total expenses, and your current net balance.
- **Advanced Analytics**: Visualize spending patterns with Pie charts for category distribution, Bar charts for income vs. expense comparison, and Line charts for monthly trends.
- **Transaction Management**: Easily add, edit, and delete transactions. Includes support for notes, categories, and recurring transaction markers.
- **Smart Budgeting**: Set a monthly budget goal and track your spending progress with a visual status bar that changes color based on your limit.
- **Currency Converter**: Real-time currency conversion from INR to major global currencies (USD, EUR, GBP, etc.) using an external API.
- **Filtering & Search**: Search through your transaction history by title or notes, and filter by transaction type.

## 🛠️ Tech Stack

- **Frontend**: React.js
- **State Management**: React Context API
- **Form Handling**: React Hook Form
- **Validation**: Yup
- **Routing**: React Router DOM
- **Charts**: Recharts
- **Styling**: Modern CSS (Custom Properties & Flexbox/Grid)

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or higher)
- npm (comes with Node.js)

## ⚙️ Setup & Installation

1. **Clone the repository**:
   ```bash
   git clone <your-repository-url>
   cd finance-tracker
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Environment Configuration**:
   Create a `.env` file in the root directory and add your API key for exchange rates:
   ```env
   REACT_APP_EXCHANGE_RATE_API_KEY=your_api_key_here
   ```

4. **Run the application**:
   ```bash
   npm start
   ```
   The app will be available at `http://localhost:3000`.
