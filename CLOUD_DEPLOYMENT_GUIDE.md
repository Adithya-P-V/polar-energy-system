# 🌐 24/7 Cloud Deployment Guide (Access Anywhere, Even When Laptop is Turned OFF)

To make your website (**Polar Energy Intelligence System**) accessible from **any device** (phone, tablet, laptop, smart TV) at **any time**—even when your laptop is completely turned **OFF**—you need to host it on a **Cloud Server**.

Below are the 2 fastest, 100% **FREE** methods to get a permanent public link (e.g., `https://polar-energy-system.streamlit.app`).

---

## ⚡ Option 1: Streamlit Community Cloud (Recommended - 100% Free 24/7)

Streamlit provides free 24/7 cloud hosting for Streamlit applications directly from GitHub.

### Step-by-Step Instructions:

1. **Create a GitHub Repository**:
   - Go to [GitHub.com](https://github.com) and log in (or sign up).
   - Click **New Repository**, name it `polar-energy-system`, and click **Create Repository**.

2. **Upload Your Project Files to GitHub**:
   - Upload the files inside `polar_energy_system` folder (`app.py`, `pages/`, `src/`, `models/`, `data/`, `requirements.txt`, `.streamlit/`).

3. **Deploy on Streamlit Cloud**:
   - Go to [share.streamlit.io](https://share.streamlit.io) and log in with your GitHub account.
   - Click **New app**.
   - Select your repository (`polar-energy-system`) and main file path (`app.py`).
   - Click **Deploy!**

4. **Your Permanent 24/7 Public Link**:
   - Streamlit will generate a permanent link like:  
     `https://polar-energy-system.streamlit.app`
   - **You can copy this link and open it on ANY phone, tablet, or PC in the world, even when your laptop is completely powered OFF!**

---

## 🚀 Option 2: Render.com Cloud Hosting (Free 24/7 Web Service)

Render allows you to host web applications using Git or Docker containers for free.

1. Go to [Render.com](https://render.com) and create a free account.
2. Click **New +** -> **Web Service**.
3. Connect your GitHub repository.
4. Render will automatically detect `render.yaml` and `Dockerfile` created in this project.
5. Click **Create Web Service**.
6. Render will give you a permanent HTTPS URL like `https://polar-energy-system.onrender.com`.

---

## 📡 Option 3: Wi-Fi Local Network Access (Laptop Turned ON)

If your laptop is turned **ON** and connected to Wi-Fi, you can access the website on your phone or tablet on the same Wi-Fi using your laptop's local IP:

1. Look at your local network IP (e.g. `http://192.168.1.15:8080`).
2. Open that URL in your phone browser while connected to the same Wi-Fi.

---

### 📦 Files Included for Deployment
- `Dockerfile` — Container configuration for Docker / Render / Cloud Run
- `render.yaml` — 1-click Render web service specification
- `requirements.txt` — Python dependencies
- `.streamlit/config.toml` — Cloud production server settings
