# RentMate - Roommate Chore & Expense Scheduler

A modern web application to help roommates manage chores, expenses, and household responsibilities efficiently.

## 🌟 Features

- **Household Management**
  - Create or join households via invite codes
  - Member role management (Owner vs Member)
  - Secure authentication system

- **Chore Management**
  - Rotating chore assignments
  - Customizable chore frequencies
  - Chore completion tracking
  - Automated rotation system

- **Expense Tracking**
  - Shared expense logging
  - Equal or custom split options
  - Balance calculation
  - Settlement suggestions

- **Calendar Integration**
  - Combined view of chores and expenses
  - Color-coded events
  - Monthly calendar view

- **Reporting & Export**
  - Historical logs
  - CSV export functionality
  - Balance reports

## 🚀 Tech Stack

- **Frontend**
  - React.js
  - Material-UI
  - Redux Toolkit
  - React Router
  - Axios

- **Backend**
  - Node.js
  - Express.js
  - MongoDB
  - JWT Authentication
  - Mongoose ODM

## 🛠️ Setup & Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/dheerajbirlaji/Rentmate.git
   cd rentmate
   ```

2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd server
   npm install

   # Install frontend dependencies
   cd ../client
   npm install
   ```

3. Environment Setup:
   - Create `.env` file in server directory
   - Add required environment variables (see .env.example)

4. Start the development servers:
   ```bash
   # Start backend server (from server directory)
   npm run dev

   # Start frontend server (from client directory)
   npm start
   ```

## 📝 Environment Variables

Create a `.env` file in the server directory with the following variables:

```
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
NODE_ENV=development
```

## 🔐 API Documentation

API documentation is available at `/api-docs` when running the server.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Dheeraj Birlaji - Initial work

## 🙏 Acknowledgments

- Thanks to all contributors
- Inspired by real-world roommate challenges
