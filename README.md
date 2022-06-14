<h1 align="center">BEUTIFULFILM</h1>

<h4>Многостраничное приложение для поиска фильмов, с возможностью добавления в избранное и фильтрацией. Реализован функционал регистрации, авторизации, редактирования профиля.</h4>

<img align="center" width="100%" src="https://github.com/VladimirZaigraev/movies-explorer-full/blob/main/screenshot/home.jpg">
  
Ссылка на сайт: [https://zaigraev.movie.nomoredomains.work](https://zaigraev.movie.nomoredomains.work)

Публинчый ip: 51.250.99.206


<h3 align="center">Технологии</h3>

- HTML5 - cемантическая вёрстка
- SASS (Flexbox) - Наименования элементов и структура по методологии БЭМ Nested. Анимация элементов. Интерфейс адаптирован под различные устройства ( от 320 до 1280 и более пикселей по ширине).
- JavaScript ES6 - функциональный подход, async/await, fetch API.
- React - функциональные компоненты.
  - Функции Context, Ref, Redirect, Route, Switch.
  - Хуки useState, useEffect, useContext, useRef, useCallback, useNavigate.
  - Кастомные хуки useInput, useValidation, useLocalStorage
  - Авторизация, валидация, защита роутов.
  - LocalStorage - хранения данных между сессиями.
- Node.js/Express.js.
  - API реализован по принципам REST для работы с базой данных, аутентификации/авторизации.
  - MongoDB(schema) - хранение и работа с данными.
  - Mongoose - для взаимодействия Node с MongoDB.
  - validator, joi/celebrate - валидация поступающих данных.
  - JWT - авторизация с помощью серверного куки с зашифрованным токен.
  - winston - логирование ошибок.
  - Реализована централизованная обработка ошибок с отправкой корректных статусов и сообщений о ошибках на запросы.
  - nginx - перенаправление запросов с 80 порта на порт, который слушает Node
  - Сервер создан на виртуальной машине Yandex.Cloud
ESLint(airbnb-base) - стандартизация кода

<h3 align="center">Ограничения</h3>
  "react-router-dom": ^6.3.0"

<h3 align="center">Инструкция по развёртыванию</h3>

npm i - установка модулей

npm run start - запуск frontend
  

<div>
  <img align="left" width="45%" src="https://github.com/VladimirZaigraev/movies-explorer-full/blob/main/screenshot/movies.jpg">
  <img align="right" width="45%" src="https://github.com/VladimirZaigraev/movies-explorer-full/blob/main/screenshot/save-movies.jpg">
</div>
