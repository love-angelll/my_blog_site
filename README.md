# Сайт Ивана Фрунзы

<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

> [!WARNING]
> Проект находится ещё в разработке !

## Описание проекта
Этот проект представляет собой платформу для блога с возможностями регистрации, авторизации и управлением контентом. 

### Основные возможности:
- **Регистрация и вход:** пользователи могут создать аккаунт и войти в систему.
- **Управление постами:** администраторы могут создавать, редактировать и удалять посты.
- **Комментарии и лайки:** пользователи могут оставлять комментарии к постам и ставить лайки.
- **Адаптивный дизайн:** сайт автоматически подстраивается под устройства пользователей (мобильные, планшеты, десктопы).

---

## Структура проекта
```
project/
├── app/                            # Основное приложение
│   ├── __init__.py                 # Инициализация приложения
│   ├── routes.py                   # Основные маршруты
│   ├── models.py                   # Модели базы данных
│   ├── forms.py                    # Веб-формы (регистрация, вход, комментарии)
│   ├── templates/                  # HTML-шаблоны
│   │   ├── base.html               # Общий шаблон
│   │   ├── index.html              # Главная страница
│   │   ├── login.html              # Страница входа
│   │   ├── register.html           # Страница регистрации
│   │   ├── profile.html            # Профиль пользователя
│   │   ├── create_post.html        # Создание поста (доступно только админам)
│   │   ├── post_detail.html        # Детальная страница поста (комментарии, лайки)
│   │   └── posts.html              # Список всех постов
│   ├── static/                     # Статические файлы (CSS, JS, изображения)
│   │   ├── css/
│   │   │   └── styles.css          # Основной стиль сайта
│   │   ├── js/
│   │   │   └── scripts.js          # Дополнительные скрипты (лайки, AJAX)
│   │   └── images/                 # Аватары и изображения
│   └── utils.py                    # Вспомогательные функции (например, проверка на администратора)
├── migrations/                     # Миграции базы данных
├── tests/                          # Тесты
│   ├── test_routes.py              # Тесты маршрутов
│   ├── test_models.py              # Тесты моделей
│   ├── test_forms.py               # Тесты форм
│   └── test_permissions.py         # Проверка прав доступа
├── config.py                       # Конфигурация приложения (база данных, ключи)
├── requirements.txt                # Список зависимостей Python
├── Procfile                        # Для деплоя на Heroku
├── run.py                          # Точка входа для запуска приложения
└── README.md                       # Документация
```

## Основные функции

**1. Для пользователей:**
- Создание аккаунта.
- Просмотр постов.
- Лайки и комментарии.

**2. Для администраторов:**
- Управление постами (создание, редактирование, удаление).

## Технологии

- Python (Flask)

- SQLAlchemy

- Bootstrap

- HTML, CSS, JavaScript

- SQLite/PostgreSQL


## Содействие

Не стесняйтесь отправлять проблемы или запросы на исправление, если у вас есть какие-либо вопросы то пишите в соц. сетях.

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/iv_frunza)
[![VK Основной](https://img.shields.io/badge/VK%20Основной-4A76A8?style=for-the-badge&logo=vk&logoColor=white)](https://vk.com/iv.frunza) [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/iv.frunza)
