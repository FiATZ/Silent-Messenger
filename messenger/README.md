messenger/
│
├── app/
│   ├── __init__.py        # инициализация Flask-приложения
│   │
│   ├── routes/
│   │   ├── auth.py        # регистрация, вход, выход
│   │   ├── chat.py        # чат и сообщения
│   │   └── main.py        # главные страницы
│   │
│   ├── models/
│   │   ├── user.py        # модель пользователя
│   │   └── message.py    # модель сообщения
│   │
│   ├── templates/
│   │   ├── auth/
│   │   │   ├── login.html
│   │   │   └── register.html
│   │   │
│   │   ├── chat/
│   │   │   └── chat.html
│   │   │
│   │   └── base.html     # общий шаблон
│   │
│   ├── static/
│   │   ├── css/
│   │   └── js/
│   │
│   ├── extensions.py     # БД, login manager и т.д.
│   └── config.py         # настройки
│
├── migrations/           # миграции БД
│
├── run.py                # точка входа
├── requirements.txt
└── README.md