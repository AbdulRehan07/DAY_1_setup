# 📘 Day 1 Setup – Python Environment + GitHub Repository

This guide explains how to:

- Create a project folder using terminal
- Create a virtual environment
- Activate the environment
- Create a `requirements.txt`
- Install dependencies using pip
- Create `main.py`
- Push the project to GitHub

---

# 📁 Step 1: Create Project Folder (Terminal)

Open Terminal / PowerShell and run:

```bash
mkdir data-engineering-practice
cd data-engineering-practice
```

Create a setup folder for Day 1:

```bash
mkdir day_1_setup
cd day_1_setup
```

---

# 🐍 Step 2: Create Virtual Environment

Run:

```bash
python -m venv venv
```

This creates an isolated Python environment inside your project.

---

# ▶️ Step 3: Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

### Mac / Linux

```bash
source venv/bin/activate
```

After activation, terminal will show:

```
(venv)
```

This confirms the environment is active ✅

---

# 📦 Step 4: Create requirements.txt

Create the dependency file:

```bash
type nul > requirements.txt
```

Or manually create:

```
requirements.txt
```

Example dependencies:

```
pandas
numpy
requests
```

---

# 📥 Step 5: Install Dependencies

Run:

```bash
pip install pandas numpy requests
```

Save installed packages:

```bash
pip freeze > requirements.txt
```

---

# 📝 Step 6: Create main.py

Create a Python file:

```
main.py
```

Example content:

```python
print("Environment setup successful 🚀")
```

Run the script:

```bash
python main.py
```

---

# 🌐 Step 7: Initialize Git Repository

Run:

```bash
git init
```

Add files:

```bash
git add .
```

Commit changes:

```bash
git commit -m "Initial project setup"
```

---

# ☁️ Step 8: Push Project to GitHub

Create a repository on GitHub first, then connect it:

```bash
git remote add origin https://github.com/yourusername/day_1_setup.git
git branch -M main
git push -u origin main
```

---

# 📂 Final Project Structure

```
day_1_setup/
│
├── venv/
├── main.py
├── requirements.txt
└── README.md
```
