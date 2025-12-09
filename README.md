# 🔒 LockBoostAI

### *AI-powered content idea generator for creators & marketers.*

LockBoostAI is a lightweight yet powerful tool designed to generate **content ideas**, **hooks**, **captions**, and **hashtags** optimized for platforms like Instagram, TikTok, and LinkedIn.

Initially built for **gaming, marketing & NFT audiences**, but easily adaptable to any niche.

---

## 🚀 MVP Features

* Generates **5 fully structured content ideas**:

  * Title
  * Hook / intro
  * Optimized caption
  * Relevant hashtags
* Inputs: **topic**, **audience**, **tone**, **platform**
* Simple, fast interface built with **Streamlit**
* Optimized for **creators**, **social media managers**, **brands**, and **agencies**

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone git@github.com:YOUR_USERNAME/lockboost-ai.git
cd lockboost-ai
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add your OpenAI API key

Create a `.env` file at the project root:

```env
OPENAI_API_KEY=your_api_key_here
```

### 5. Run the app

```bash
streamlit run app.py
```

---

## ⚡ Optional — Startup Script (Unix)

Create a file named `run.sh`:

```bash
#!/bin/bash

source .venv/bin/activate

pip install --upgrade pip
pip install -r requirements.txt

streamlit run app.py
```

Run it:

```bash
chmod +x run.sh
./run.sh
```

---

## 📝 How to Use

1. Enter a **topic** or prompt
2. Select your **target audience**
3. Choose the **tone** (friendly, formal, hype, etc.)
4. Pick a **platform** (Instagram, TikTok, LinkedIn…)
5. Hit **Generate**

You’ll instantly receive **5 curated content ideas** ready to post.

---

## 📁 Project Structure

```plaintext
lockboost-ai/
├─ app.py             # Streamlit UI
├─ utils.py           # Prompt and formatting helpers
├─ requirements.txt   # Python dependencies
├─ .env.example       # Example environment file
├─ README.md          # Project documentation
└─ .gitignore         # Files to exclude from versioning
```

---

## 🤝 Contributing

We welcome contributions from everyone.
Follow the standard GitHub workflow:

### 1. Fork the project

GitHub → **Fork**

### 2. Clone your fork

```bash
git clone git@github.com:YOUR_USERNAME/lockboost-ai.git
cd lockboost-ai
```

### 3. Create a new branch

```bash
git checkout -b feature/my-feature
```

### 4. Commit your changes

```bash
git add .
git commit -m "feat: add new feature"
```

### 5. Push your branch

```bash
git push origin feature/my-feature
```

### 6. Open a Pull Request

→ Keep PRs focused on one feature or fix
→ Add clear descriptions
→ The maintainer reviews, discusses, and merges

---

## 🛡️ Recommended Branch Protection

To protect the `main` branch:

* Disable direct pushes
* Require Pull Requests
* Require at least 1 approval
* Prevent forced pushes
* Prevent deletion of `main`

You can enable all this in:
**Settings → Branches → Branch Protection Rules**

---

## 🔗 Useful Links

* Issues → [https://github.com/YOUR_USERNAME/lockboost-ai/issues](https://github.com/YOUR_USERNAME/lockboost-ai/issues)
* Pull Requests → [https://github.com/YOUR_USERNAME/lockboost-ai/pulls](https://github.com/YOUR_USERNAME/lockboost-ai/pulls)
* Streamlit Docs → [https://docs.streamlit.io](https://docs.streamlit.io)

---

## 📜 License

This project is licensed under the **MIT License**.
See the `LICENSE` file for full details.

---
