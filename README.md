# ⚡ EV-Charge-Stations

**EV-Charge-Stations** is a full-stack web application for managing EV charging stations. It features authentication, station listings, a map view, and CRUD operations—all packaged in a modern responsive UI.

---

## 🌐 Live Demo

- 🔗 [Frontend (Vercel)](https://ev-charge-stations.vercel.app/)
- 🔗 [Backend API (Render)]([https://ev-charge-stations.onrender.com](https://ev-charge-stations-lcte.onrender.com))


---

## 🛠 Tech Stack & Documentation

### 🔧 Backend

| Tech | Purpose |
|------|---------|
| **Node.js** | JavaScript runtime for backend server. |
| **Express.js** | Web framework to define APIs and route handling. |
| **PostgreSQL** | Relational database to store charging station and user data. |
| **Sequelize ORM** | Manages PostgreSQL database with models, migrations, and easy queries. |
| **JWT (JSON Web Token)** | Handles secure user authentication. |
| **dotenv** | Loads sensitive configuration like DB credentials from `.env` file. |
| **bcryptjs** | Used for hashing and comparing user passwords securely. |

### 🖼 Frontend

| Tech | Purpose |
|------|---------|
| **Vue.js 3** | Main frontend framework for building UI components and SPA. |
| **Vue Router** | Manages page routing (e.g., `/login`, `/register`, `/dashboard`). |
| **Tailwind CSS** | Provides utility-first CSS classes for fast and responsive styling. |
| **Leaflet.js** | Used to display EV charging station locations on an interactive map. |
| **Axios** | For making API calls from frontend to backend. |
| **Font Awesome** | Icons used across forms, navigation, and map controls. |

---

## 📋 Features

- 🔐 User registration and login
- 🧭 List and map view of charging stations
- 🧱 Add, edit, and delete stations (CRUD)
- 📱 Responsive layout for mobile and desktop
- 💾 Data persistence using PostgreSQL + Sequelize
- 🗂 Organized API structure with MVC pattern

---

## 📂 Folder Structure

```
EA-Charge-Stations/
├── frontend/         # Vue.js frontend with Tailwind and Leaflet
├── backend/          # Express backend with Sequelize
├── migrations/       # DB schema migrations
├── models/           # Sequelize models (User, Station)
├── routes/           # API endpoints
├── controllers/      # Logic for handling requests
└── README.md
```

---

## 🧑‍💻 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Ameykadwe19/EA-Charge-Stations.git
cd EA-Charge-Stations
```

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file:

```env
DB_HOST=localhost
DB_PORT=5432
DB_NAME=ea_charge
DB_USER=postgres
DB_PASSWORD=your_password
JWT_SECRET=your_secret
```

Run migrations:

```bash
npx sequelize-cli db:migrate
```

Start server:

```bash
npm start
```

### 3. Setup Frontend

```bash
cd ../frontend
npm install
npm run dev
```

---

## 🔄 CRUD Operations

- **Create** – Add station using form
- **Read** – View stations in list and map view
- **Update** – Edit station info via modal
- **Delete** – Remove station via UI

---

## 🧭 Navigation

| Route | Purpose |
|-------|---------|
| `/login` | User login |
| `/register` | Create account |
| `/stations` | Station list view |
| `/stations/map` | Map view with markers |

---

## 👨‍💻 Author

**Amey Kadwe**  
GitHub: [@Ameykadwe19](https://github.com/Ameykadwe19)

---

### Made with 💡 and ⚡ by @Ameykadwe19
