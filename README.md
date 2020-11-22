[DEMO LINK](https://KirillLutsenko.github.io/Digits/)

### Техническое задание
1. В проекте присутствуют два попапа (`Вход` и `Заказ обратного звонка`).
   Данные попап окна вызывают соответствующие кнопки `Вход` и `Перезвонить мне`
2. `Все категории`, `Select 1, Select 2` и т.д. кастомные select.
3. Все формы должны иметь клиентскую JS валидацию:
   * `Ваш email` - проверка на корректный email.
   * `Пароль` - минимум 4 символа.
   * `Поиск по сайту` - минимум 2 символа.
   * `Цена` - валидация на положительные цифры.
4. `Номер телефона` - ввод цифр по маске.
5. При клике на кнопку `Очистить фильтр` - все значения input && select - должны сброситься в дефолтное состояние.
6. После успешной валидации поля `Укажите свой email для подписки` - должен появиться попап с текстом "Вы успешно подписаны на рассылку".
8. При клике на кнопки `Сравнить товар` и `В избранное` сменить текст кнопок `В сравнении` и `В избранном` соответственно + инкрементировать количество добавленных в блоках `Сравнение` и `Избранное`, в шапке страницы.
7. Используется кастомный шрифт Roboto доступен в Google Fonts - [Roboto](https://fonts.google.com/specimen/Roboto).

### Требования
* Написание JS с использованием стандарта ES6;
* Без использования CSS фреймворков (Bootstrap, Foundation etc.);
* RWD;
* Верстка приближенная к Pixel Perfect;
* Кроссбраузерная верстка (`Chrome latest`, `Firefox latest`, `Safari 10+`, `Edge 15+`);
* Верстка по сетке;
* Отсутствие средств отладки кода `console.log`, `alert`, `debugger`;
* Отсутствие закомментированных частей кода;
* Отсутствие не используемых функций, переменных и методов;