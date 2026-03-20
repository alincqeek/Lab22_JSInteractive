### Лабораторная работа №22. Интерактивные веб-приложения на JavaScript
---
*Цель Разработать интерактивное веб-приложение (Калькулятор) используя HTML, CSS, JavaScript, а также закрепить навыки работы с Git и GitHub.*

1.Структура проекта
Создать директорию Lab22_JS_Interactive_FIO (где FIO — ваша фамилия).
```Lab22_JS_Interactive_FIO/
├── calculator/
│   ├── index.html
│   ├── style.css
│   ├── main.js
│   └── calculator.js (для рефакторинга)
├── img/ (для скриншотов)
└── README.md
```
2.Разработка Калькулятора
+ Контейнер: div с классом .calculator.
+ Поле вывода: input#display (атрибут readonly).
+ Кнопки:
  + Цифры.
  + Операции.
  + C (очистка).
  + = (равно).
3.  CSS
+ Body:
  + Flexbox (центрирование по центру экрана).
  + height: 100vh.
+ Calculator:
  + Grid-сетка для кнопок.
  + grid-template-columns: repeat(4, 1fr).
+ Кнопка "=":
  + grid-column: span 4.
  + Оранжевый фон.
4.JavaScript (База)
+ События: Обработчики click на кнопки.
+ Вычисление: Через функцию eval().
+ Ошибки: Обработка через конструкцию try...catch.