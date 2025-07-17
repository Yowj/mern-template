MERN - TEMPLATE WITH AUTHENTICATION, TAILWIND, ZUSTAND, AND TANSTACK.

A modern web application built with the MERN stack (MongoDB, Express.js, React, Node.js)

## 🌟 Features

- **Authentication System**
  - User signup and login
  - Secure session management with JWT
  - Protected routes

- **Theme System**
  - 30+ built-in themes using DaisyUI
  - Persistent theme preferences
  - Dynamic theme switching

- **Social Features**
  - Friend system
  - User discovery
  - Profile customization

## 🚀 Tech Stack

### Frontend
- React with Vite
- [TailwindCSS](https://tailwindcss.com/) with [DaisyUI](https://daisyui.com/)
- [React Query](https://tanstack.com/query) for data fetching
- [Zustand](https://github.com/pmndrs/zustand) for state management
- [React Router](https://reactrouter.com/) for navigation

### Backend
- Node.js with Express
- MongoDB with Mongoose
- JWT for authentication
- bcrypt for password hashing

## 🛠️ Installation

1. Clone the repository:
git clone <repository-url>
cd template_mern

2. Install dependencies:
# Install root dependencies
npm install

# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install

3. Environment Setup:
Create .env files:

Frontend .env: VITE_BASE_URL=http://localhost:5001

Backend .env:MONGO_URI=your_mongodb_uri
JWT_SECRET_KEY=your_jwt_secret

4. Start the development servers:

# From root directory
npm run dev


Workspace
(rerun without)
Collecting workspace information

I'll create a comprehensive README for your MERN stack application. Here's a well-structured documentation:

Install dependencies:
Environment Setup:
Create .env files:

Frontend .env:

Backend .env:

Start the development servers:
This will start both frontend and backend servers concurrently:

Frontend: http://localhost:5173
Backend: http://localhost:5001
📁 Project Structure
.
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── hooks/
│   │   ├── lib/
│   │   ├── pages/
│   │   └── store/
│   └── public/
└── backend/
    ├── src/
    │   ├── controllers/
    │   ├── models/
    │   ├── routes/
    │   ├── lib/
    │   └── middlewares/

🔒 API Routes
Authentication
POST /api/auth/signup - Create new user account
POST /api/auth/login - User login
POST /api/auth/logout - User logout
GET /api/auth/me - Get authenticated user data
🎨 Available Themes
The application includes 30+ built-in themes from DaisyUI, including:

Light
Dark
Cupcake
Forest
Coffee
Nord
And many more!
📱 Responsive Design
The application is fully responsive and optimized for:

Mobile devices
Tablets
Desktop screens
🤝 Contributing
Contributions are welcome! Please read our contributing guidelines before making a pull request.

📄 License
This project is licensed under the ISC License.
