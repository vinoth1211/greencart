# GreenCart

A modern e-commerce platform built with React and Node.js, featuring a robust client-server architecture.

## 🚀 Features

- **User Authentication**

  - Secure login and registration
  - JWT-based authentication
  - Protected routes

- **Product Management**

  - Product listing and details
  - Image upload using Cloudinary
  - Search and filtering capabilities

- **Shopping Experience**

  - Shopping cart functionality
  - Secure payment processing with Stripe
  - Order tracking and management

- **Modern Tech Stack**
  - React 19 with Vite
  - Node.js/Express backend
  - MongoDB database
  - Tailwind CSS for styling

## 🛠️ Tech Stack

### Frontend

- React 19.1.0
- React Router 7.6.1
- Tailwind CSS 4.1.8
- React Hot Toast 2.5.2
- Vite 6.3.5

### Backend

- Node.js
- Express 5.1.0
- MongoDB with Mongoose 8.15.1
- JWT Authentication
- Stripe Payment Integration
- Cloudinary for Image Management

## 📋 Prerequisites

- Node.js (v18 or higher)
- MongoDB
- npm or yarn
- Stripe account (for payments)
- Cloudinary account (for image uploads)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/greencart.git
cd greencart
```

### 2. Environment Setup

#### Backend (.env)

Create a `.env` file in the server directory:

```env
PORT=4000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

#### Frontend (.env)

Create a `.env` file in the client directory:

```env
VITE_API_URL=http://localhost:4000
VITE_STRIPE_PUBLIC_KEY=your_stripe_public_key
```

### 3. Install Dependencies

#### Backend

```bash
cd server
npm install
```

#### Frontend

```bash
cd client
npm install
```

### 4. Run the Application

#### Development Mode

1. Start the backend server:

```bash
cd server
npm run server
```

2. Start the frontend development server:

```bash
cd client
npm run dev
```

The application will be available at:

- Frontend: http://localhost:5173
- Backend: http://localhost:4000

## 📁 Project Structure

```
greencart/
├── client/                 # Frontend React application
│   ├── src/               # Source files
│   ├── public/            # Static files
│   └── package.json       # Frontend dependencies
│
└── server/                # Backend Node.js application
    ├── configs/          # Configuration files
    ├── controllers/      # Route controllers
    ├── middlewares/      # Custom middlewares
    ├── models/           # Database models
    ├── routes/           # API routes
    └── server.js         # Entry point
```

## 🔒 Security Features

- JWT-based authentication
- Password hashing with bcrypt
- CORS protection
- Secure cookie management
- Environment variable configuration

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the ISC License.

## 👥 Authors

- Vinoth - Initial work

## 🙏 Acknowledgments

- React Team
- Express.js Team
- MongoDB Team
- All other open-source contributors
