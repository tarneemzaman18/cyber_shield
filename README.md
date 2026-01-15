# Cyber Shield 🛡️

A comprehensive cybersecurity monitoring and threat detection system with Django backend, React frontend, and MySQL database. 

## Project Structure

```
cyber_shield/
├── 📂 backend/              # Django Project Folder
│   ├── 📂 core/             # Project settings (where settings.py is)
│   ├── 📂 api/              # App for handling your SQL logic/endpoints
│   ├── manage.py
│   └── requirements.txt     # List of python libraries (Django, mysqlclient)
├── 📂 frontend/             # Frontend files (React, Vue, or static HTML/CSS)
│   ├── 📂 src/
│   └── package.json
├── 📂 database/             # Store your SQL scripts here
│   ├── schema.sql           # The table structures
│   ├── seeds.sql            # Your mock data
│   └── queries.sql          # Your optimized analytical queries
├── 📂 docs/                 # ER Diagrams, documentation, or API specs
├── .env                     # IMPORTANT: Store your DB password/secrets here
├── docker-compose.yml       # Docker configuration
└── README.md
```

## Getting Started

### Prerequisites
- Python 3.9+
- Node.js 16+
- MySQL 8.0+
- Docker & Docker Compose (optional)

### Installation

#### Backend Setup
```bash
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

#### Frontend Setup
```bash
cd frontend
npm install
npm start
```

#### Database Setup
```bash
mysql -u root -p < database/schema.sql
mysql -u root -p < database/seeds.sql
```

## Features
- Real-time threat detection
- Security monitoring dashboard
- User authentication & authorization
- Incident reporting & management
- Analytics and insights

## License
MIT License