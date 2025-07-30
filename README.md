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
git clone https://github.com/yourusername/quicktalk.git
cd quicktalk
```

2. **Set up environment variables**

Create `.env` in `/backend`:
```
PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/quicktalk
JWT_SECRET=your_strong_secret_here
JWT_EXPIRE=24h
```

Create `.env` in `/frontend`:
```
REACT_APP_API_URL=http://localhost:5000
REACT_APP_SOCKET_URL=http://localhost:5000
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

## 🚀 Deployment

**Option 1: Full Stack Deployment**
- Frontend: Vercel/Netlify
- Backend: Render/Railway
- Database: MongoDB Atlas

**Option 2: Docker Deployment**
```bash
docker-compose up --build
```

## 🛡 Security Best Practices
- Always use HTTPS in production
- Store secrets in environment variables
- Implement rate limiting
- Sanitize user input
- Use CSRF protection

## 🤝 How to Contribute
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## 📄 License
MIT License - see LICENSE file for details.

## 📬 Contact
For support or questions:

- **Email:** your.email@example.com
- **GitHub:** [@yourusername](https://github.com/yourusername)
- **Twitter:** [@yourhandle](https://twitter.com/yourhandle)
