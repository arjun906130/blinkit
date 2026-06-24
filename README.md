# 🛒 Blinkit Sales Dashboard

An interactive web application built with **Django** that embeds a premium **Power BI Analytics Dashboard** to track, visualize, and analyze Blinkit's sales, performance, and key business metrics in real-time.

---

## 📊 Project Overview

This project serves as a centralized analytics portal for **Blinkit** sales analysis. It leverages the robust backend framework **Django** to serve a highly responsive, clean front-end container. This container embeds a live, interactive **Power BI** dashboard, allowing stakeholders, managers, or analysts to easily explore key performance indicators (KPIs), sales trends, outlet performances, and item sales distributions.

---

## 🚀 Key Features

* **Live Power BI Embedding:** Seamless integration of an interactive Power BI report showcasing real-time data visualizations.
* **Modern & Clean UI/UX:** Designed with a vibrant, Blinkit-themed header and a neat, glassmorphic layout.
* **Fully Responsive Design:** The dashboard automatically scales to fit various screen sizes (desktop, tablet, mobile devices) with optimized CSS media queries.
* **Django Backend Integration:** Served via Django’s generic `TemplateView` for fast and lightweight rendering with clean routing structures.

---

## 🛠️ Tech Stack

* **Backend:** Python 3.x, Django 5.2+
* **Frontend:** HTML5, CSS3 (Vanilla, custom responsive grids)
* **Analytics Engine:** Microsoft Power BI (embedded via iframe)

---

## 📂 Project Structure

```text
blinkit/
│
├── blinkit/                  # Main Project Directory
│   ├── __init__.py           
│   ├── asgi.py               # ASGI configuration for deployment
│   ├── settings.py           # Django settings and configuration
│   ├── urls.py               # Django URL routing
│   ├── wsgi.py               # WSGI configuration for deployment
│   │
│   └── templates/            # Django template files
│       └── index.html        # Main dashboard UI containing the Power BI embed
│
├── db.sqlite3                # SQLite database (default)
├── manage.py                 # Django command-line utility
└── .gitignore                # Git ignore rules
```

---

## 💻 Getting Started

Follow these steps to set up and run the project locally.

### 📋 Prerequisites

Make sure you have **Python** installed on your system. You can verify this by running:
```bash
python --version
```

### 🔧 Installation Steps

1. **Clone or Navigate to the Directory:**
   ```bash
   cd d:\intership\blinkit
   ```

2. **Create a Virtual Environment (Optional but Recommended):**
   ```bash
   python -m venv venv
   # Activate it on Windows:
   .\venv\Scripts\activate
   ```

3. **Install Django:**
   Since this project uses Django, install it using pip:
   ```bash
   pip install django
   ```

4. **Verify Database Migrations:**
   Ensure database setups are configured (optional as the project currently acts as a portal):
   ```bash
   python manage.py migrate
   ```

5. **Start the Development Server:**
   Run the following command to start Django's local server:
   ```bash
   python manage.py runserver
   ```

6. **Access the Application:**
   Open your browser and navigate to:
   [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 📈 Future Enhancements

* **User Authentication:** Add login/signup systems to restrict dashboard access to authorized team members.
* **Role-Based Access Control (RBAC):** Render different dashboards depending on user roles (e.g., Regional Manager vs. Executive).
* **Database Logs:** Integrate local sqlite/postgresql logs to track user interactions and dashboard views.
* **Additional Dashboards:** Add navigation links to toggle between sales, inventory, and logistics dashboards.

---

## 👤 Author

* **Arjun** - *Initial Work & Integration* - [GitHub Portfolio](https://github.com/)

## Deployment
This project is configured for deployment on Railway/Render.
