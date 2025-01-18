
# 🏥 Hospital Food Delivery Management System

## 📋 Overview
A full-stack application for managing hospital patient meals, diet charts, and meal deliveries. The system streamlines communication between hospital managers, pantry staff, and delivery personnel for efficient meal delivery management.

## ⚡ Key Features
- 🔐 Role-based authentication and authorization
- 👥 Multi-user support with different access levels
- 📱 Responsive design for all devices
- 🔄 Real-time updates using WebSocket
- 📊 Interactive dashboards for each role
- 🎯 Efficient meal delivery tracking
- 🔔 Toast notifications for user feedback
- 🛡️ Protected routes and secure session management

## 🛠️ Tech Stack

### Frontend
- ⚛️ React.js
- 🎨 Tailwind CSS
- 🔄 Socket.IO client
- 🎯 React Router DOM
- 💅 Lucide React Icons
- 🔔 React Toastify
- 📡 Axios

### Backend
- 📦 Node.js
- 🚀 Express.js
- 🗄️ MongoDB with Mongoose
- 🔄 Socket.IO
- 🔑 JWT Authentication
- 🔒 bcryptjs

## 💻 User Interface Components

### 🧭 Navigation
- Responsive navbar with role-based navigation
- Dynamic user profile dropdown
- Mobile-friendly menu
- Seamless authentication flow

### 📊 Role-Based Dashboards


## 🔑 Login Credentials

For testing purposes, use the following credentials for different roles:

### 👨‍💼 Hospital Manager Dashboard
- **Email:** hospital_manager@xyz.com
- **Password:** Password@2025

- Patient management
- Diet chart creation
- Overview statistics
- System monitoring

### 👨‍🍳 Pantry Staff Dashboard
- **Email:** hospital_pantry@xyz.com
- **Password:** Password@2025
- View and manage diet charts
- Create delivery orders
- Update meal preparation status
- Real-time order tracking

### 🚚 Delivery Personnel Dashboard
- **Email:** hospital_delivery@xyz.com
- **Password:** Password@2025
- View assigned deliveries
- Update delivery status
- Real-time delivery tracking
- Route optimization

> **Note:** These credentials are for testing purposes only and should be changed in a production environment.


## 🔐 Authentication System
- JWT-based secure authentication
- Role-based access control
- Protected routes
- Automatic token management
- Secure session handling

## 🔄 Real-time Features
- WebSocket integration
- Live delivery status updates
- Instant notifications
- Real-time dashboard updates

## 🎨 UI/UX Features
- Modern, clean interface
- Responsive design
- Interactive components
- Toast notifications
- Loading states
- Error handling
- Form validation

## 📦 Installation

1. Clone the repository
```bash
git clone https://github.com/NalagamdinniRaju/Hospital-Food-Management.git
```

2. Install dependencies for both frontend and backend
```bash
# Frontend
cd frontend
npm install

# Backend
cd backend
npm install
```

3. Configure environment variables
```bash
# Frontend (.env)
REACT_APP_API_URL=your_backend_url

# Backend (.env)
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=5000
```

4. Start the application
```bash
# Frontend
npm start

# Backend
npm start
```

## 🔒 Security Features
- Secure password hashing
- JWT token validation
- Protected API endpoints
- Role-based access control
- CORS configuration
- Input validation

