# Quant-Tech: future of AI driven finance

A full-stack fintech payment application built with React, Node.js, Express, MongoDB, and Google Gemini AI. This project demonstrates a modern payment platform with wallet management, secure transactions, and an AI-powered financial assistant.

## 🚀 Features

- **User Authentication**: Secure registration and login with JWT tokens
- **Wallet Management**: Add funds and manage wallet balance
- **Money Transfer**: Send money to other users via phone or email
- **Transaction History**: View all incoming and outgoing transactions
- **AI Financial Assistant**: Chat with Google Gemini-powered assistant for financial queries
- **Modern UI**: Glassmorphism design with dark theme and smooth animations
- **Secure Transactions**: Atomic transactions using MongoDB sessions
- **Protected Routes**: JWT-based authentication middleware

## 🛠️ Tech Stack

### Frontend
- **React 19**: UI library
- **Vite**: Fast build tool and dev server
- **React Router DOM**: Client-side routing
- **Axios**: HTTP client
- **CSS3**: Custom glassmorphism styling

### Backend
- **Node.js**: JavaScript runtime
- **Express.js**: Web framework
- **MongoDB**: NoSQL database
- **Mongoose**: MongoDB ODM
- **JWT**: Authentication
- **bcryptjs**: Password hashing
- **dotenv**: Environment configuration
- **CORS**: Cross-origin request handling

### AI Integration
- **Google Gemini API**: LLM for financial assistant chatbot

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB (local or cloud instance)
- Google Gemini API key

## 🔧 Installation

### 1. Clone the repository
```bash
git clone https://github.com/Codingammature/quant-tech.git
cd quant-tech

cd backend
npm install
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/phonepe-clone
JWT_SECRET=your_jwt_secret_key
GEMINI_API_KEY=your_gemini_api_key

cd ../frontend
npm install

cd frontend
npm run dev

cd frontend
npm run build
```

 **API Endpoints:**
 
Authentication
POST /api/auth/register - Register a new user
POST /api/auth/login - Login user
GET /api/auth/me - Get current user (protected)
Transactions
POST /api/transactions/add-funds - Add funds to wallet (protected)
POST /api/transactions/transfer - Transfer money to another user (protected)
GET /api/transactions/history - Get transaction history (protected)
Chat
POST /api/chat - Send message to AI assistant (protected)



**🔐 Security Features**
Password hashing with bcryptjs
JWT-based authentication
Protected API routes with middleware
Atomic transactions to prevent data inconsistency
CORS enabled for safe cross-origin requests


**🎨 UI Design**
The application features a modern glassmorphism design with:

Dark theme with purple/blue gradients
Smooth animations and transitions
Responsive layout
Floating action chatbot widget
Real-time transaction status indicators
