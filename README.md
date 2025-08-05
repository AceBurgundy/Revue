# 📝 Revue – Exam Review Made Social

**Revue** is a collaborative review platform where users can browse, share, and rate exam review materials. Whether you're prepping for an upcoming test or contributing your own notes, Revue turns studying into a community-driven experience.

> 🚧 *Note: This app is currently in its **beta phase**, featuring a foundational server template and database models. UI and feature implementations are in progress.*

## 🌟 Key Features (Planned)

* 📚 Browse curated review materials by subject
* 🧪 Take sample tests and practice exams
* 👥 Login system for personalized access
* 🗃️ Users can upload and share their own review materials
* 👍 Vote on materials to highlight quality contributions
* 🔍 Search and filter past exams and materials
* 🧠 Track test performance and attempt history (upcoming)
* 🔄 Real-time updates using **SocketIO**

## 🖥️ Tech Stack

* **Flask** – Web application framework
* **Flask-SocketIO** – Real-time server push
* **SQLite3** – Lightweight database backend
* **HTML, CSS, JavaScript** – Frontend interface
* **Jinja2** – Server-side rendering for dynamic content

## ⚙️ Installation & Setup

### 🧰 Prerequisites

* Python 3.8+
* (Optional) Virtual Environment

### 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/revue.git
   cd revue
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Initialize the database:

   ```bash
   python create_database.py
   ```

4. Start the development server:

   ```bash
   python app.py
   ```

5. Open in your browser:

   ```
   http://localhost:8080
   ```

## 📌 Current Status

* ✅ Basic boilerplate server template
* ✅ Database model structure
* 🔄 Auth system (in development)
* 🔄 Upload/review flow (in design)
* 🔄 User dashboard & test interface (TBD)

## 📈 Future Improvements

* Allow users to **create categories** and organize materials
* Enable **commenting and discussion** under materials
* Add **test analytics** and result breakdowns
* Improve file upload and preview support (PDF, images, etc.)
* Introduce **admin panel** for moderation
* Add **notifications** and follower system
* Improve mobile responsiveness

## 🧠 Why Revue?

Studying doesn't need to be solitary. Revue encourages collaboration and community-driven content by allowing users to share and rank study materials. It brings together students who want to help each other succeed — one review at a time.

## 🛡️ License

This project uses the **AGPL License**. See the [LICENSE](LICENSE) file for full details.
