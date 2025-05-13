# 🚀 Dockerized NGINX Static Website

This is a production-ready Docker project that serves a static HTML page using NGINX.  
It is part of my DevOps project portfolio, focused on mastering containerization, clean project structure, and real-world deployment readiness.

---

## 📦 Tech Stack

- Docker
- NGINX (Alpine)
- HTML/CSS (basic)

---

## 🛠️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/rahul-aws/docker-nginx-static-site.git
cd docker-nginx-static-site
```

### 2. Build the Docker Image
```bash
docker build -t rahul0526/docker-nginx-static-site .
```

### 3. Run the Container
```bash
docker run -d -p 8080:80 rahul0526/docker-nginx-static-site
```

🔗 Open your browser: [http://localhost:8080](http://localhost:8080)

---

## 🐳 Docker Hub

Pull the image directly from Docker Hub:

```bash
docker pull rahul0526/docker-nginx-static-site
```

👉 [View on Docker Hub](https://hub.docker.com/repository/docker/rahul0526/docker-nginx-static-site/general)

---

## 📁 Project Structure

```
docker-nginx-static-site/
├── Dockerfile
├── src/
│   └── index.html
├── assets/
│   └── screenshot.png  # Optional preview
├── .gitignore
└── README.md
```

---

## 🎯 Project Goals

- Solidify Docker fundamentals with real deployment practice
- Practice modular and clean project structure
- Prepare for Kubernetes + Helm deployments
- Reuse for YouTube content and DevOps case studies

---

## 🎥 YouTube Integration (Coming Soon)

This project will be featured in my YouTube series:  
**"DevOps Projects from Scratch – Learn by Doing"**

Stay tuned for the video breakdown, CI/CD extension, and cloud deployment guide.

---

## 📬 Connect With Me

- 💼 [LinkedIn](https://www.linkedin.com/in/rahul-kumar-84518b186/)
- 🐙 [GitHub](https://github.com/rahul-aws)
- 📺 YouTube: *Coming soon*

---

## 📌 License

MIT License — Use it, fork it, and grow with it.
