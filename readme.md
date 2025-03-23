# Trading Platform

This is a trading platform built with a backend and frontend that allows users to perform various trading-related tasks. It integrates payment gateways like Stripe and Razorpay, and uses APIs like CoinGecko and Gemini for real-time market data.

## Backend Setup

### Prerequisites
- MySQL
- Java
- Stripe API Key
- Razorpay API Key and Secret
- CoinGecko API Key
- Gemini API Key

### Steps to Run the Backend

1. **Create Database**
    - Run the following command to create the database:
    ```sql
    CREATE DATABASE treading;
    ```
    
2. **MySQL Configuration**
    - Make sure you have your MySQL password configured properly for connecting the backend to the database.
    
3. **Java Mail Sender Configuration**
    - You need to provide your **email** and **app password** to send mails.
    - If you don't have an app password for Gmail, you can create one. Search for "how to create app password for Gmail" on YouTube if you need guidance.

4. **Payment Gateway Configuration**
    - **Stripe**: Provide your **API key** for Stripe payment gateway to handle transactions.
    - **Razorpay**: Provide your **API key** and **API secret** for Razorpay integration.

5. **API Configuration**
    - **CoinGecko API**: Provide your **CoinGecko API key** for retrieving market data.
    - **Gemini API**: Provide your **Gemini API key** for handling cryptocurrency trading.

---

## Frontend Setup

### Prerequisites
- Node.js (version 14 or later)

### Steps to Run the Frontend

1. **Install Dependencies**
    - Run the following command to install the required dependencies:
    ```bash
    npm install
    ```

2. **Start Development Server**
    - Run the following command to start the development server:
    ```bash
    npm run dev
    ```

---

## Contributing

Feel free to fork the repository, create a branch, and submit pull requests. Contributions are welcome!

---

## License

This project is licensed under the MIT License.

---

For further instructions or questions, feel free to contact the developer team.
