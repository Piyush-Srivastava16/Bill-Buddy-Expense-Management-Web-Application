# 🎨 Bill Buddy - React Frontend

A modern and responsive frontend application for managing bills and user authentication, built using **React.js**. This project serves as the client-side interface for the Bill Buddy system, providing a clean UI and seamless interaction with the backend APIs.

---

## 🚀 Features

* 🔐 **User Authentication UI**

  * Login & Registration pages
  * Session handling (with backend integration)
* 📊 **User-Friendly Interface**

  * Clean and responsive design
  * Intuitive navigation
* 🔗 **API Integration**

  * Communicates with Spring Boot backend services
* ⚡ **Fast Development Setup**

  * Modular and component-based architecture

---

## 🛠️ Tech Stack

* **Frontend Library:** React.js
* **Language:** JavaScript
* **Styling:** CSS / Bootstrap (or your styling choice)
* **HTTP Client:** Axios / Fetch API
* **Build Tool:** npm / Vite / Create React App

---

## 📁 Project Structure

```
bill-buddy-react-frontend/
│── src/
│   ├── components/        # Reusable UI components
│   ├── pages/             # Application pages (Login, Register, etc.)
│   ├── services/          # API calls and business logic
│   ├── App.js             # Root component
│   └── index.js           # Entry point
│── public/                # Static assets
│── package.json           # Dependencies and scripts
```

---

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Piyush-Srivastava16/bill-buddy-react-frontend.git
cd bill-buddy-react-frontend
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Backend API URL

Update API base URL in your project (example):

```javascript
const BASE_URL = "http://localhost:8080";
```

---

### 4. Run the Application

```bash
npm start
```

The app will run at:

```
http://localhost:3000
```

---

## 🔌 Application Flow

1. User registers or logs in
2. Frontend sends API requests to backend
3. Backend validates and returns response
4. UI updates dynamically based on response

---

## 🧪 Testing

You can test the frontend by:

* Connecting it with the backend server
* Performing authentication flows (login/register)
* Checking API responses in browser dev tools

---

## 🔮 Future Enhancements

* 🎯 Dashboard for bill tracking
* 📱 Mobile responsiveness improvements
* 🔐 JWT-based authentication handling
* 🌐 Deployment (Netlify / Vercel)
* 📊 Data visualization for expenses

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📧 Contact

**Piyush Srivastava**
GitHub: https://github.com/Piyush-Srivastava16

---

## ⭐ Acknowledgements

* React Documentation
* Open Source Community

```
```

 
 
 
 React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
