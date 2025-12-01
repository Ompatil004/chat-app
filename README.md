# Chat Application

A real-time chat application built with a modern tech stack.

## 👤 Author

**Om Patil**


## 🛠️ Tech Stack

- **Frontend**:
- **Backend**:
- **Database**: MongoDB
- **Authentication**: JWT

## 📋 Features

- Real-time messaging
- User authentication
- Chat rooms/privileges
- Message history

## 🚀 Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd chat-app
   ```

3. Install dependencies for both frontend and backend:
   ```bash
   # Install backend dependencies
   cd Backend
   npm install
   ```

   ```bash
   # Install frontend dependencies
   cd ../Frontend
   npm install
   ```

4. Set up environment variables:
   - Create a `.env` file in the `Backend` directory
   - Add your environment variables (as seen in your `.env` file)

5. Run the application:
   ```bash
   # Start backend
   cd Backend
   npm start
   ```

   ```bash
   # Start frontend (in a separate terminal)
   cd Frontend
   npm run dev
   ```

## 🔧 Environment Variables

In the `Backend/.env` file, you need to set:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
NODE_ENV=development
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.