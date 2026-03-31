# 🎓 Scholar Connect

> A modern academic platform built to connect students, researchers, and educators — enabling collaboration, resource sharing, and academic scheduling in one place.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue?style=for-the-badge)](https://mxs2247.uta.cloud/)
[![React](https://img.shields.io/badge/React-18.3.1-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.4.8-646CFF?style=for-the-badge&logo=vite)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind-3.4.13-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)

---

## 📖 About the Project

**Scholar Connect** is a frontend web application designed to serve the academic community. It provides a centralized hub where scholars can discover peers, manage schedules, receive notifications, and access academic resources — all through a clean, responsive interface.

The project was developed as part of a university course at **The University of Texas at Arlington (UTA)** and is hosted on the UTA cloud infrastructure.

---

## ✨ Features

- 🔐 **User Authentication** — Login and registration flows for students and educators
- 🗓️ **Academic Calendar** — Interactive calendar for tracking events, deadlines, and meetings
- 🔔 **Toast Notifications** — Real-time feedback using `react-hot-toast`
- 🧭 **Multi-page Navigation** — Smooth client-side routing via React Router DOM
- 🎨 **Responsive UI** — Mobile-first design using Tailwind CSS and DaisyUI component library
- 🖼️ **Icon-rich Interface** — Consistent iconography throughout with React Icons

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | React 18 |
| Build Tool | Vite |
| Styling | Tailwind CSS + DaisyUI |
| Routing | React Router DOM v6 |
| Notifications | React Hot Toast |
| Calendar | React Calendar |
| Icons | React Icons |
| Containerization | Docker + Docker Compose |
| Linting | ESLint |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/)

### Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/Saiteja661/Scholar-connect-Project.git

# 2. Navigate into the project folder
cd Scholar-connect-Project

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
```

Once running, open the localhost URL shown in your terminal (typically `http://localhost:5173`) in your browser.

---

## 🐳 Run with Docker

> **Note:** Ensure you have a `Dockerfile` in the root directory before running Docker Compose.

```bash
# Build and start the container
docker-compose up --build

# App will be available at:
# http://localhost:5173
```

The `docker-compose.yaml` maps port `5173` on your host to the container.

---

## ☁️ Live Deployment

The application is hosted on the UTA cloud:

🔗 **[https://mxs2247.uta.cloud/](https://mxs2247.uta.cloud/)**

---

## 📁 Project Structure

```
Scholar-connect-Project/
├── public/              # Static assets
├── src/                 # Application source code
│   ├── components/      # Reusable UI components
│   ├── pages/           # Route-level page components
│   └── main.jsx         # App entry point
├── index.html           # HTML entry point
├── package.json         # Project metadata and dependencies
├── tailwind.config.js   # Tailwind CSS configuration
├── vite.config.js       # Vite build configuration
├── docker-compose.yaml  # Docker Compose configuration
└── eslint.config.js     # ESLint rules
```

---

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint checks |

---

## 🔮 Future Improvements

- [ ] Add a backend API (Node.js / Express or Supabase)
- [ ] Implement real user authentication with JWT or OAuth
- [ ] Add a Dockerfile to complete the Docker setup
- [ ] Add unit and integration tests with Vitest
- [ ] Implement a messaging/chat feature between scholars
- [ ] Add search functionality for users and resources

---

## 👤 Author

**Saiteja** — [@Saiteja661](https://github.com/Saiteja661)

---

## 📄 License

This project was created for academic purposes at the University of Texas at Arlington.
