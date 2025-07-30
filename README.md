# 💬 QuickTalk - Real-Time Chat Application

![App Preview](https://via.placeholder.com/1200x600?text=QuickTalk+Demo+GIF/Screenshot)

A full-stack real-time messaging platform built with modern web technologies.

## 🌟 Key Features

### Real-Time Communication
- Instant message delivery with Socket.IO
- Typing indicators
- Online status tracking
- Read receipts

### User Experience
- Light/dark mode toggle
- Responsive design (mobile/tablet/desktop)
- Notification system
- Clean, intuitive interface

### Security & Authentication
- JWT-based authentication
- Password encryption
- Protected routes
- Session management

## 🛠 Technology Stack

| Area        | Technologies Used |
|-------------|-------------------|
| **Frontend** | React, Socket.IO Client, Context API, Chakra UI, Axios |
| **Backend**  | Node.js, Express, Socket.IO Server, MongoDB, Mongoose |
| **DevOps**   | JWT, bcrypt, dotenv, CORS |

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+)
- MongoDB Atlas account or local MongoDB
- Git

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Nirmalspatel/Chat-App.git
cd Chat-App
```


3. **Install dependencies**
```bash
# Backend setup
cd backend && npm install

# Frontend setup
cd ../frontend && npm install
```

### 🏃 Running the Application

Start development servers:

**Backend Server (port 5000)**
```bash
cd backend
npm run dev
```

**Frontend Server (port 3000)**
```bash
cd frontend
npm start
```

Access the app at: http://localhost:3000

## 📂 Project Structure

```
quicktalk/
├── backend/
│   ├── config/         # Configuration files
│   ├── controllers/    # Business logic
│   ├── middleware/     # Auth & validation
│   ├── models/         # MongoDB schemas
│   ├── routes/         # API endpoints
│   ├── utils/          # Helper functions
│   └── server.js       # Entry point
├── frontend/
│   ├── public/         # Static assets
│   └── src/
│       ├── assets/     # Images, styles
│       ├── components/ # Reusable UI
│       ├── context/    # State management
│       ├── hooks/      # Custom hooks
│       ├── pages/      # View components
│       ├── services/   # API calls
│       └── App.js      # Main component
├── .gitignore
└── README.md
```

## 📬 Contact
For support or questions:

- **Email:** nirmalspatel3003@gmail.com
- **GitHub:** [@Nirmal](https://github.com/Nirmalspatel)
