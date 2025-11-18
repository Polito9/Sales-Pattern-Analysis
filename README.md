# 📦 Project Setup Instructions

Follow these steps to set up the project locally and run the code.

---

## 🚀 1. Clone the Repository
```bash
git clone https://github.com/Polito9/Sales-Pattern-Analysis.git
cd Sales-Pattern-Analysis
```

## 🐍 2. Create a Virtual Environment (recommended)

Create a local virtual environment inside the project folder.

Windows:
```bash
py -m venv .venv
```

macOS / Linux
```bash
python3 -m venv .venv
```

## ▶️ 3. Activate the Virtual Environment

Windows
```bash
.\.venv\Scripts\activate
```

macOS / Linux
```bash
source .venv/bin/activate
```

You should now see (.venv) before your terminal prompt.

## 📥 4. Install Project Dependencies
All required packages are listed in requirements.txt.

```bash
pip install -r requirements.txt
```

Now you can run the file main.ipynb



## 🔄 Updating Dependencies (for contributors)

If you install or update packages, regenerate requirements.txt:

```bash
pip freeze > requirements.txt
```
