# 🍲 BhojanSeva - Zero Waste Food Redistribution Platform

## 📌 Overview

BhojanSeva is a smart food redistribution platform designed to reduce food waste by connecting canteens, NGOs, and students through a centralized system.

The platform enables organizations to list surplus food, track food safety, coordinate pickups, and receive real-time notifications, ensuring that edible food reaches people in need instead of being wasted.

---

## 🚀 Features

### 🍛 Smart Food Listing
- Add surplus food items
- Quantity and expiry tracking
- Food safety status monitoring
- Freshness indicators

### 🔔 Real-Time Notification System
- Instant updates using Socket.io
- Pickup notifications
- Food availability alerts
- Event-based communication

### 🤝 NGO & Student Coordination
- Food request management
- Pickup scheduling
- Distribution tracking

### 📊 Admin Dashboard
- Monitor food donations
- User management
- Analytics and reporting
- Event management

### 📅 Event Integration
- Community food drives
- Awareness campaigns
- Donation events

### 🛡 Food Safety Monitoring
- Expiry tracking
- Status updates
- Safety verification system

---

## 🏗 System Architecture

Frontend:
- Next.js
- React
- TypeScript
- Tailwind CSS
- Radix UI

Backend:
- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.io

Authentication:
- JWT Authentication
- Bcrypt Password Hashing

---

## 📂 Project Structure

```
zero-waste-main/
│
├── frontend/
│   ├── app/
│   ├── components/
│   ├── hooks/
│   └── lib/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## 🛠 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/bhojanseva.git
cd bhojanseva
```

### Backend Setup

```bash
cd backend
npm install
npm start
```

Server runs on:

```bash
http://localhost:5000
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```bash
http://localhost:3000
```

---

## 🔑 Environment Variables

Create a `.env` file inside the backend folder.

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## 📸 Screenshots

### Landing Page
- Home interface
- User authentication

### Admin Dashboard
- Food tracking
- User management
- Analytics

### NGO Dashboard
- Food request system
- Pickup coordination

### Canteen Dashboard
- Surplus food listing
- Inventory management

---

## 🎯 Use Cases

- College Canteens
- Restaurants
- NGOs
- Community Food Banks
- Social Welfare Organizations

---

## 💡 Future Enhancements

- Mobile Application
- AI-Based Food Demand Prediction
- QR-Based Pickup Verification
- GPS Tracking
- Cloud Deployment
- Advanced Analytics Dashboard

---

## 👨‍💻 Tech Stack

| Technology | Purpose |
|------------|----------|
| Next.js | Frontend |
| React | UI Development |
| TypeScript | Type Safety |
| Tailwind CSS | Styling |
| Node.js | Backend |
| Express.js | API Development |
| MongoDB | Database |
| Mongoose | ODM |
| Socket.io | Real-Time Communication |
| JWT | Authentication |
| Bcrypt | Password Security |

---

## 🌱 Impact

BhojanSeva contributes towards:

- Reducing food wastage
- Supporting communities in need
- Promoting sustainable food distribution
- Encouraging social responsibility

---

## 👥 Contributors

Developed during a Hackathon Project focused on sustainable food redistribution and community welfare.

---

## 📜 License

This project is developed for educational, research, and social impact purposes.
