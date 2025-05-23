# ☁️ Cloud Portfolio Setup – DevOps from Scratch to 🚀

Welcome to my **Cloud DevOps Journey**!  
In this project, I built and deployed a **full-stack portfolio** using:

- **Docker**
- **GitHub Actions**
- **DockerHub**
- **Render**
- ... and a sprinkle of grit and good vibes!

---

## 🚀 Live Preview

- **Frontend:** [Visit Live Website](https://myportfolio-uena.onrender.com)
- **Backend API:** [View Render Backend](https://myportfoliobackend-0rkm.onrender.com)

---

## 📁 Folder Structure

cloud-setup/ ├── backend/               # Node.js backend API (Dockerized) │   ├── Dockerfile │   ├── server.js │   └── ... │ ├── frontend/              # Frontend (React, Vue, etc.) │   ├── Dockerfile │   ├── public/ │   └── src/ │ ├── .github/ │   └── workflows/ │       ├── backend.yml    # CI/CD pipeline for backend │       └── frontend.yml   # CI/CD pipeline for frontend │ └── README.md              # You're reading it!

---

## 🛠️ What I Did

### 1. **Dockerized Everything**
Built `Dockerfile`s for both frontend and backend so they can run in containers anywhere.

### 2. **GitHub Actions Magic**
CI/CD pipelines that:
- Build Docker images
- Push to **DockerHub**
- Auto-deploy to **Render**

### 3. **Used Render for Live Deploy**
- Zero downtime deploys
- Free tier used smartly
- Auto-redeploys when you push

---

## 🔧 Tech Stack

| Part       | Tech Used            |
|------------|----------------------|
| Frontend   | React + vite |
| Backend    | Node.js & Express    |
| CI/CD      | GitHub Actions       |
| Hosting    | Render.com           |
| Container  | Docker + DockerHub   |

---

## 📦 CI/CD Workflow (GitHub Actions)

- **Trigger:** On push to `main`
- **Builds:** Docker image
- **Pushes:** To DockerHub
- **Deploys:** Render auto-detects changes and redeploys

> Automated. Reliable. Sleek.

---

## ✨ Screenshots of Success

![Render Deploy Screenshot](./assets/render-success-1.png)  
![CI/CD Pipeline Screenshot](./assets/render-success-2.png)

---

## 💡 Lessons I Learned

- How to build containerized apps from scratch
- Setting up CI/CD pipelines like a boss
- Troubleshooting permission issues (yes, lots of them!)
- Making production-ready cloud deployments

---

## 👨‍💻 Wanna Try It Yourself?

1. Clone the repo:
   ```bash
   git clone https://github.com/James-oss796/cloud-setup.git

2. Create .env files in backend/ and frontend/


3. Build and run Docker containers:

docker-compose up --build




---

☁️ My DevOps Journey Has Just Begun...

Follow me on LinkedIn to see how I keep pushing boundaries in cloud, DevOps, and software engineering!


---

> "Automate the boring, deploy the awesome." – Me



---

Would you like me to generate the **screenshots section with placeholders** (or embed the real ones if you send them), or help write your next **LinkedIn update** to match this style?
