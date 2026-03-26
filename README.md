# Python Newsfeed

"Just Tech News" — a full-stack tech news aggregation app built with Python and Flask for educational purposes.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000?style=flat&logo=flask&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## About

A tech news platform where users can post links to articles, upvote stories, and leave comments. Built as a full-stack Python exercise using Flask with server-rendered templates, database seeding, and session-based authentication.

## Features

- User registration and login with sessions
- Post, upvote, and comment on tech news articles
- Server-rendered HTML templates with Jinja2
- Database seeding for demo data
- MVC-style project structure

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Python, Flask |
| Frontend | HTML, CSS, JavaScript |
| Templating | Jinja2 |
| Database | SQL (via seeds.py) |

## Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation

```bash
git clone https://github.com/coleyrockin/python-newsfeed.git
cd python-newsfeed
pip install -r requirements.txt
```

### Seed the Database

```bash
python seeds.py
```

### Run

```bash
python -m flask run
```

## Project Structure

```
├── app/        # Flask application (routes, models, templates)
├── seeds.py    # Database seed script
└── .gitignore
```

---

Built by [Boyd Roberts](https://github.com/coleyrockin)
