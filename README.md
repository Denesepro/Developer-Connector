# Developer-Connector

## 🌐 Project Overview

**Developer-Connector** is a full-featured social networking platform designed specifically for developers. It allows users to create professional profiles, share content, engage in discussions, and connect with other developers.

This repository primarily contains the **backend** implementation, built using the robust **Django** framework.

---

## ✨ Key Features (Backend)

The core functionality of the application, managed by the Django backend, includes:

* **User Authentication:** Secure registration and login system.
* **Developer Profiles:** Users can create, view, and edit detailed professional profiles.
    * Add skills, current status, company, website, and location.
    * Include educational history and experience.
* **Social Interaction:**
    * Create, view, and delete **posts**.
    * **Comment** on posts.
    * Like/Unlike posts.
* **Data Structure:** Structured models for accounts, profiles, posts, and comments.

---

## 🛠️ Technology Stack

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Backend Framework** | **Django** | Python web framework for robust backend development. |
| **Language** | **Python** | Primary language for server-side logic. |
| **Database** | (Requires setup) | Uses Django's ORM, typically configured with SQLite (local) or PostgreSQL (production). |
| **Frontend** | HTML (Templates) | Basic structure for rendering views. |

---

## 🚀 Getting Started

Follow these steps to set up the project locally for development:

### 1. Clone the Repository

```bash
git clone [https://github.com/Denesepro/Developer-Connector.git](https://github.com/Denesepro/Developer-Connector.git)
cd Developer-Connector

### 2. Install Dependencies

The necessary packages are listed in `requirements.txt`.

```bash
# Make sure you are in the project root directory
pip install -r requirements.txt

### 3. Database Setup

Apply migrations to create the necessary database schema:

```bash
python manage.py makemigrations
python manage.py migrate

### 4. Run the Server

Start the Django development server:

```bash
python manage.py runserver
The application will be accessible at http://127.0.0.1:8000/.
