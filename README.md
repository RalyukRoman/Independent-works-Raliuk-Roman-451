<p align="center">
  <img src="https://img.icons8.com/?size=100&id=12599&format=png&color=000000" width="120">
</p>

<h1 align="center">Проєкт для самостійних робіт</h1>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/RalyukRoman/Independent-works-Raliuk-Roman-451">
  <img src="https://img.shields.io/github/languages/top/RalyukRoman/Independent-works-Raliuk-Roman-451">
  <img src="https://img.shields.io/github/v/tag/RalyukRoman/Independent-works-Raliuk-Roman-451">
</p>


## Швидкий старт

Для початку роботи переконайтеся, що у вас встановлено **Node.js** версії 18+.

1. **Клонуйте репозиторій стартапу:**
   `git clone https://github.com`
2. **Перейдіть у директорію проєкту:**
   `cd Independent-works-Raliuk-Roman-451`
3. **Встановіть залежності:**
   `npm install`

> **Важливо:** Недійсні токени авторизації призведуть до помилок синхронізації з сервером. Обов'язково налаштуйте файл `.env`.


## Приклад використання API

Ось як виглядає ініціалізація нашого основного модуля у вашому коді:

```javascript
const { Task } = require('task-cli');

const taskManager = new Task({
  apiKey: process.env.TASK_TOKEN,
  syncInterval: 5000
});

taskManager.on('ready', () => {
  console.log('Успішно запущено!');
});
```


## Порівняння тарифних планів

| Можливість                     | План "Indie"  | План "Startup"   | План "Enterprise"         |
| :----------------------------- | :------------ | :--------------- | :------------------------ |
| **Кількість проєктів**         | До 3 проєктів | Безліч           | Безліч + виділений сервер |
| **Швидкість обробки**          | Стандартна    | Збільшена в 5х   | Максимальна (Realtime)    |
| **Підтримка 24/7**             | Відсутня      | Електронна пошта | Персональний менеджер     |
| **Доступ до CLI інструментів** | Обмежений     | Повний доступ    | Індивідуальні плагіни     |


## Демонстрація роботи продукту

Розгорніть блок нижче, щоб побачити інтерфейс у дії:

<details>
<summary><b>Переглянути GIF-анімацію роботи CLI</b></summary>
<br>
<img src="https://media.tenor.com/LPOZd_ELgvcAAAAm/cat-dance-c.webp" width="100">
</details>
