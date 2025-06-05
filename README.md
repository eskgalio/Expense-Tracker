# 💸 Expense Tracker - MERN Stack

A **full-stack expense management application** built using the **MERN** stack (MongoDB, Express, React, Node.js). This project empowers users to manage personal or business expenses in real-time with a modern and responsive UI.

---

## 🚀 Features

- ✅ **User-Friendly Interface** built with React & Context API
- 📊 **Real-Time Expense Tracking**
- 💾 **MongoDB Integration** for persistent data storage
- 🔐 **Secure API with Express & Node.js**
- ⚙️ Environment-based configuration (`config.env`)
- 🔄 **Dual Environment Support**: Development and Production modes
- 🎯 RESTful API for transaction operations (CRUD)
- 📦 Modular Codebase (controllers, models, routes)
- ⚡ Fast local development with `concurrently`

---

## 🌟 Unique Selling Points (USP)

- 🧠 **Minimal Learning Curve**: Simple yet powerful structure for beginner-to-intermediate full-stack developers
- 🔄 **Auto Reload in Dev Mode**: Uses `concurrently` to run backend and frontend seamlessly
- 🔐 **Scalable Backend**: Built with modular controller-model-route architecture
- 💡 **Ready for Production**: Includes `npm run build` and `npm start` for deployment
- 🛠️ **Portfolio-Ready**: Clean code, well-documented, and deployable—perfect to showcase full-stack skills

---

## 📦 Tech Stack

- **Frontend**: React, Context API, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Dev Tools**: Nodemon, Concurrently

---

## 📁 Folder Structure

expense-tracker-mern/
├── client/         # React frontend
├── config/         # Environment config
├── controllers/    # Express controllers
├── models/         # Mongoose schemas
├── routes/         # Express routes
├── server.js       # Entry point (Node.js backend)
├── package.json

---

## 🛠️ Installation & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/expense-tracker-mern.git
cd expense-tracker-mern
````

### 2. Set Environment Variables

Create a `.env` or modify `config/config.env`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
NODE_ENV=development
```

### 3. Install Dependencies

```bash
npm install
cd client
npm install
cd ..
```

### 4. Run the App

#### Development Mode (both frontend & backend)

```bash
npm run dev
```

#### Run Backend Only

```bash
npm run server
```

#### Run Frontend Only

```bash
npm run client
```

### 5. Build for Production

```bash
cd client
npm run build
cd ..
npm start
```

---

## ✨ Showcase Tips

* Deploy using platforms like **Render**, **Vercel (for frontend)**, or **Heroku**
* Mention this project during interviews to demonstrate:

  * REST API design
  * Full-stack integration
  * Clean React state management

---
