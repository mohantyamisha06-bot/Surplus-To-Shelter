# 🍱 Surplus-To-Shelter

> **Turning surplus food into someone's next meal.**

Surplus-To-Shelter is an AI-powered food rescue platform connecting restaurants and grocery stores with nearby shelters through smart matching, AI-assisted donation parsing, and real-time routing. The platform aims to reduce food waste and deliver surplus meals to communities in need.

## ✨ Features

- 🥘 **Food Donation Management** — Create and manage surplus food listings.
- 📍 **Location-Based Matching** — Connect available food with nearby recipients.
- 🏠 **Shelter & NGO Management** — Help recipient organizations manage their requirements.
- 🚗 **Pickup Coordination** — Coordinate collection and delivery between donors, recipients, and volunteers.
- ⚡ **Real-Time Updates** — Support real-time communication using Socket.IO.
- 🗺️ **Interactive Maps** — Location and map functionality using Leaflet.
- 📊 **Impact Dashboard** — Visualize food rescue and impact-related data.
- 🔐 **Authentication** — User authentication using JWT and password hashing.
- 📧 **Email Notifications** — Email communication using Nodemailer.
- 🤖 **AI-Assisted Donation Parsing** — Help process donation information using Gemini AI, if configured.

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- React Router
- Tailwind CSS
- Axios
- Socket.IO Client
- Leaflet & React-Leaflet
- Recharts

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.IO
- JWT
- bcrypt
- Zod
- Nodemailer
- node-cron

## 🏗️ Project Structure

```text
Surplus-To-Shelter/
├── client/             # React frontend
├── server/             # Node.js + Express backend
├── .env.example        # Example environment configuration
├── package.json
├── package-lock.json
└── AmiHacks_Problem_Statement-1.md
```

*Note: The actual files and folders may vary depending on your project.*

## 🔄 How It Works

```text
       👨‍🍳 Food Donor
             |
             v
      Post Surplus Food
             |
             v
    📍 Location Matching
             |
             v
      🏠 Recipient / NGO
             |
             v
    🚗 Pickup Coordination
             |
             v
       🍱 Food Delivered
             |
             v
       📊 Impact Tracked
```

The platform aims to make surplus food redistribution easier to manage through a single system.

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:
- Node.js
- npm
- MongoDB
- Git

### Clone the repository

```bash
git clone https://github.com/mohantyamisha06-bot/Surplus-To-Shelter.git
cd Surplus-To-Shelter
```

### Install dependencies

Install the root dependencies:

```bash
npm install
```

Install frontend dependencies:

```bash
cd client
npm install
```

Install backend dependencies:

```bash
cd ../server
npm install
```

Return to the root directory before running root-level scripts:

```bash
cd ..
```

### Environment Variables

Configure the environment variables required by the application using the provided `.env.example` file, if available.

Add the required database connection details, authentication settings, email configuration, and AI API key where applicable.

> ⚠️ Never commit API keys, passwords, access tokens, or other secrets to GitHub.

### Run the Project

Check the scripts in the root, client, and server `package.json` files to determine the correct development commands. For example, if the root package defines a `dev` script:

```bash
npm run dev
```

## 🎯 Project Goals

- ♻️ Reduce avoidable food waste.
- 🤝 Connect food donors with NGOs and shelters.
- ⚡ Make food redistribution faster.
- 📍 Improve location-based coordination.
- 🚗 Simplify pickup and delivery.
- 📊 Track the social impact of rescued food.

## 🔮 Future Improvements

- 🤖 AI-powered donor-recipient matching.
- 🗺️ Advanced route optimization.
- 📱 A dedicated mobile application.
- 🔔 Push and SMS notifications.
- 📸 Food image recognition.
- 📈 Advanced analytics and reporting.
- 🌱 Detailed environmental impact tracking.

## 🏆 Hackathon

This project was developed around the **AmiHacks – Surplus-to-Shelter: Real-Time Food Rescue Routing** problem statement.

It explores how technology can help address food waste, food redistribution, and real-time coordination challenges.

## 👩‍💻 Author

### Amisha Mohanty

Computer Science Engineering Student

🔗 GitHub: [@mohantyamisha06-bot](https://github.com/mohantyamisha06-bot)

---

## ⭐ Support

If you find this project interesting, consider giving it a ⭐ on GitHub!

<p align="center">
  🍱 <b>Save Food • Connect Communities • Create Impact</b> 🌱
</p>
