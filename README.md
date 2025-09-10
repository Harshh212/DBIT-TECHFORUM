📘 DBIT TechForum
A Q&A web application built with Django, Bootstrap, and jQuery.
Students can post queries, answer others' queries, and interact through features like leaderboards, search, and ratings.

✨ Features
🔑 User Authentication (Signup, Login, Logout with session management).

❓ Ask a Query – Users can post new queries under different categories.

💬 Answer Queries – Other users can provide answers (users cannot answer their own queries).

⭐ Rating System – Users can rate answers, leaderboard highlights top contributors.

🔍 Search Queries – Full-text search across posted queries.

📌 Categories – Queries organized into Attendance, Exams, Mini-projects, etc.

📊 Leaderboard – Shows top-rated users.

🛠 Tech Stack
Backend: Django 4.x (Python)

Frontend: Bootstrap 4/5, jQuery, HTML5, CSS3

Database: SQLite (default, easily swappable to MySQL/Postgres)

Authentication: Django's built-in user auth + sessions

Deployment: Works locally, easily deployable to any Django-compatible server

📂 Project Structure
CollegeTechForum/
│
├── Home/                 # Main Django app
│   ├── migrations/
│   ├── static/           # CSS, JS, images
│   ├── templates/        # HTML templates
│   │   ├── base.html     # Common layout (navbar, footer)
│   │   ├── Home.html     # Homepage with queries & leaderboard
│   │   ├── AllAnswer.html # Displays answers for a query
│   │   ├── AllQueries.html
│   │   ├── Answer.html
│   │   ├── AskQuery.html
│   │   ├── Login.html
│   │   ├── SignUp.html
│   │   └── ... etc.
│   ├── views.py          # All app views
│   ├── models.py         # Query, Answers, Rating models
│   ├── urls.py           # App-specific URLs
│   └── ...
│
├── CollegeTechForum/     # Project root
│   ├── settings.py
│   ├── urls.py
│   └── middleware.py     # Custom NoCacheMiddleware
│
├── manage.py
└── README.md


🚀 Getting Started
Prerequisites
Python 3.8+

Django 4.x

pip (Python package manager)

Installation
Clone the repository

Run migrations: python manage.py migrate

Start the server: python manage.py runserver

Open http://localhost:8000 in your browser

Default Admin Access
Username: admin

Password: admin123

📸 Screenshots
<img src="./DbitTechForum/TechForum%20Images/1.jpg" alt="User login page." width="600">
<img src="./DbitTechForum/TechForum%20Images/2.jpg" alt="User sign-up page." width="600">
<img src="./DbitTechForum/TechForum%20Images/3.jpg" alt="Homepage with Trending queries🔥and leaderboard🏅." width="600">
<img src="./DbitTechForum/TechForum%20Images/4.jpg" alt="Post your query" width="600">
<img src="./DbitTechForum/TechForum%20Images/5.jpg" alt="Unanswered Query" width="600">
<img src="./DbitTechForum/TechForum%20Images/6.jpg" alt="Contact Us" width="600">
<img src="./DbitTechForum/TechForum%20Images/7.jpg" alt="About Us" width="600">
<img src="./DbitTechForum/TechForum%20Images/8.jpg" alt="Category Based Filtering" width="600">
<img src="./DbitTechForum/TechForum%20Images/9.jpg" alt="Using the search bar to find specific queries." width="600">
<img src="./DbitTechForum/TechForum%20Images/10.jpg" alt="Detailed view of a single query." width="600">
<img src="./DbitTechForum/TechForum%20Images/11.jpg" alt="Rating an answer to score its helpfulness." width="600">
<img src="./DbitTechForum/TechForum%20Images/12.jpg" alt="Interface for submitting an answer to a query." width="600">

🤝 Contributing
Fork the repository

Create a feature branch

Make your changes

Test thoroughly

Submit a pull request
