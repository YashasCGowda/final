Features
User Authentication: Secure login and registration with JWT-based authentication.
Wallet Management: Add money to the wallet, check balance, and manage transactions.
Money Transfer: Transfer money to other users within the platform.
Transaction History: View past transactions with detailed information.

Tech Stack
Frontend: React.js with Redux for state management and Material-UI for UI components.
Backend: Node.js and Express.js for server-side logic.
Database: MongoDB for data persistence.
Authentication: JSON Web Tokens (JWT) for secure user authentication.

Steps
Clone the Repository
git clone https://github.com/your-username/digital-payment-wallet.git
cd digital-payment-wallet

Backend Setup
Navigate to the backend directory
cd backend
Install dependencies:
npm install
Create a .env file and configure the following variables:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
Start the server:

npm startFrontend Setup
Navigate to the frontend directory:
cd ../frontend
Install dependencies:
npm install
Create a .env file and configure the following variables:
REACT_APP_BACKEND_URL=http://localhost:5000
Start the development server:
npm start
Access the Application
Open your browser and navigate to:
http://localhost:3000
