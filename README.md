# KindExchange
Student timebank application


# Инструкция для фронтенд-разработчиков

# Клонирование репозитория
git clone https://github.com/ancstwi/KindExchange.git
cd KindExchange

# Настройка фронтенда (если React Native)
cd frontend
npm install

# Запуск
npx expo start

# Настройка фронтендаа (если веб)
npx create-react-app frontend-web
ИЛИ
npm create vite@latest frontend-web -- --template react

# Запуск
cd frontend-web
npm install
npm run dev


# Доступные API эндпоинты

GET /users - получить всех пользователей
GET /users/:id - пользователь по айди
POST /users - создать пользователя

# Надо добавить
Регистрация, чат, лента обновлений(?)


# Полезные команды

# Посмотреть базу данных
cd backend
npx prisma studio

# Получить изменения с бэка
git pull origin main

# Проверить что бэк работает
curl http://localhost:3000/users


