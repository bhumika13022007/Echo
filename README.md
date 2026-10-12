📂 Project Structure
Echo/
│
├── frontend/
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── app.js
│   └── assets/
│
├── backend/
│   ├── manage.py
│   ├── config/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   │
│   ├── assistant/
│   │   ├── views.py
│   │   ├── urls.py
│   │   ├── models.py
│   │   └── services/
│   │       ├── llm.py
│   │       ├── rag.py
│   │       └── voice.py
│   │
│   └── requirements.txt
│
├── knowledge_base/
│   └── documents/
│
├── .env.example
├── .gitignore
└── README.md
