# YUVA R&D — National Youth Innovation Pipeline

> Empowering India's youth to innovate, collaborate, and commercialize breakthrough ideas.

---

##  About the Project

**YUVA R&D** is a centralized platform designed to bridge the gap between students, researchers, and industries, enabling collaborative innovation at a national scale. The platform streamlines the entire journey of an idea — from initial submission and mentorship to patent filing and commercialization — making the innovation pipeline accessible and efficient for all stakeholders.

---

##  Features

- **Idea Submission** — Students and researchers can submit innovations across domains including agriculture, health, manufacturing, education, energy, and environment.
- **Mentorship Portal** — Connects innovators with domain experts and industry mentors for guided development.
- **Project Collaboration** — Facilitates team formation and collaborative project management across institutions.
- **Patent Guidance** — Automated patent classification system that maps innovations to relevant IPC (International Patent Classification) codes.
- **Commercialization Pathways** — Supports two routes: Industry Adoption and Startup Creation, with dedicated resources for each.
- **MySQL-Backed Data Management** — Robust and scalable database layer for managing users, submissions, mentorships, and project data.
- **Responsive UI** — User-friendly interface designed for accessibility and engagement across all devices.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Framework | React.js |
| Backend | Node.js |
| Database | MySQL |

---

##  Key Highlights

- Built a centralized platform connecting students, researchers, and industries to enable collaborative innovation.
- Developed features for idea submission, mentorship, and project collaboration with MySQL-backed data management.
- Designed a scalable and user-friendly interface to streamline interaction between stakeholders, improving accessibility and engagement across the platform.

---

##  Project Structure

```
yuvar-rd/
├── index.html          # Main frontend entry point
├── src/
│   ├── components/     # React components
│   ├── pages/          # Page-level views
│   └── styles/         # CSS stylesheets
├── server/
│   ├── index.js        # Node.js server entry
│   ├── routes/         # API route handlers
│   └── db/             # MySQL connection & queries
├── public/             # Static assets
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v16+
- [MySQL](https://www.mysql.com/) 8.0+
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/yuvar-rd.git
   cd yuvar-rd
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure the database**

   Create a `.env` file in the root directory:
   ```env
   DB_HOST=localhost
   DB_USER=your_mysql_username
   DB_PASSWORD=your_mysql_password
   DB_NAME=yuvar_db
   PORT=5000
   ```

4. **Set up the MySQL database**
   ```bash
   mysql -u root -p < server/db/schema.sql
   ```

5. **Start the development server**
   ```bash
   # Start backend
   npm run server

   # Start frontend (in a new terminal)
   npm start
   ```

6. **Open in browser**
   ```
   http://localhost:3000
   ```

---

## Deployment (GitHub Pages — Static Version)

For the static HTML version:

1. Rename `yuvar_d.html` to `index.html`
2. Push to GitHub
3. Go to **Settings → Pages → Source: main branch**
4. Your site will be live at:
   ```
   https://YOUR_USERNAME.github.io/yuvar-rd/
   ```

---

## Screenshots

> *(Add screenshots of your platform here)*

---

##  Contributing

Contributions are welcome! Please open an issue first to discuss what you'd like to change.

---

##  License

This project is licensed under the [MIT License](LICENSE).

---

##  Author

**Yuva R&D Team**  
Built with  for India's youth innovators.

