# 🔍 Catalog Search Service

### Опис
Це багатосторінковий веб-додаток для пошуку товарів у каталозі з можливістю додавання в кошик і оформлення замовлення. Проєкт включає:
- **3 види пошуку** (налаштовуються через меню);
- **Авторизацію користувачів**;
- **Збереження історії пошуку**;
- **Замовлення товарів**.

### Стек технологій
#### **Фронтенд:**
- [Next.js](https://nextjs.org/) – фреймворк для React;
- [Material-UI](https://mui.com/) – UI-компоненти;
- [Zustand](https://zustand-demo.pmnd.rs/) – менеджер стану.

#### **Бекенд:**
- [Flask](https://flask.palletsprojects.com/) – легкий веб-фреймворк;
- [Redis](https://redis.io/) – кешування;
- [SQLAlchemy](https://www.sqlalchemy.org/) – ORM для роботи з базою даних;
- [Marshmallow](https://marshmallow.readthedocs.io/) – серіалізація/валідація даних;
- [Alembic](https://alembic.sqlalchemy.org/) – міграції бази даних;
- [PostgreSQL](https://www.postgresql.org/) – реляційна база даних.

#### **Інфраструктура:**
- [Nginx](https://nginx.org/) – реверс-проксі сервер із підтримкою SSL;
- [Docker](https://www.docker.com/) – контейнеризація та деплой.

---

## 🚀 Запуск проєкту

### 🔧 Локальний запуск
1. **Запустити Redis:**  
   *(Windows)*: `redis-server.exe`  
   *(Linux/Mac)*: `redis-server`

2. **Запустити бекенд:**  
   ```bash
   python app.py
   ```

3. **Запустити фронтенд:**  
   ```bash
   npm run dev
   ```
   Проєкт буде доступний на [`http://localhost:3000`](http://localhost:3000).

### 🐳 Запуск через Docker
```bash
docker compose up -d --build
```
Проєкт буде доступний на порту **9433**.

### 🌍 Доступ із зовнішніх пристроїв
Якщо потрібно зробити проєкт доступним для інших пристроїв:
```bash
ngrok http https://localhost:9433
```

---

## 📜 Ліцензія
Цей проєкт розповсюджується під MIT ліцензією.

## 📩 Контакти
Якщо у вас є питання або пропозиції – пишіть тут (або вкажіть email/контакти).

