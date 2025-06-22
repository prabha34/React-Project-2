**FOODY ZONE**
![Screenshot 2025-06-22 181653](https://github.com/user-attachments/assets/51f29825-abbd-4acb-b150-b9afd501326c)
![Screenshot 2025-06-22 181731](https://github.com/user-attachments/assets/0423e485-b2be-40c8-8273-0da7d3cecb11)

**🍔 Foody-Zone — React + Express** 

Welcome to **Foody-Zone**, a dynamic full-stack food web application built with:

- ⚛️ React + Vite (frontend)
- 🌐 Express + Node.js (backend)
- 💅 Styled for responsiveness and clean UI

---
 🚀 Live Demo (Frontend Only)

👉 [View Live on GitHub Pages](https://prabha34.github.io/React-Project-2)

> ⚠️ Note: This demo only includes the **frontend** (React) because GitHub Pages does **not support backend hosting** (Node.js/Express). Backend code is included in this repo for reference or local use.

---

## 🗂️ Project Structure

```

project-2/
│
├── app/              # React + Vite frontend (deployed)
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── server/           # Node.js + Express backend (code only)
│   ├── src/
│   ├── dist/
│   └── tsconfig.json
│
└── README.md         # You are here!

````

---

 ⚙️ Local Development Setup
 1️⃣ Clone the Repository

```bash
git clone https://github.com/prabha34/React-Project-2.git
cd React-Project-2
````

---

2️⃣ Start Backend (Node + Express)

```bash
cd server
npm install
npm run dev   # or use: npx ts-node src/index.ts if using TypeScript
```

Backend runs at: `http://localhost:9000`
 3️⃣ Start Frontend (React + Vite)

```bash
cd ../app
npm install
npm run dev
```

Frontend runs at: `http://localhost:5173`

🔗 API Integration

The frontend makes API requests to the backend using:

```js
fetch('http://localhost:5000/api/...')
```

For deployment, you can mock the data or use static JSON if backend hosting isn’t available.

---
📦 Deployment Commands

### Deploy Frontend to GitHub Pages

```bash
cd app
npm run deploY 
![Screenshot 2025-06-22 181731](https://github.com/user-attachments/assets/0423e485-b2be-40c8-8273-0da7d3cecb11

**Tech Stack**

| Tech         | Used For         |
| ------------ | ---------------- |
| React        | Frontend UI      |
| Vite         | Build Tool       |
| Node.js      | Backend runtime  |
| Express.js   | API Server       |
| TypeScript   | Backend logic    |
| GitHub Pages | Frontend hosting |


Made with ❤️ by [@prabha34](https://github.com/prabha34)

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
