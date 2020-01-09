## [Курс ReactJS](https://webup.dex-it.ru/reactjs.pdf)

Dex разработал [приложение](https://apps.apple.com/ru/app/big3/id1378562978) для баскетольной лиги BIG3, куда приходят доигрывать легенды баскетбола. Давайте попробуем переплюнуть успех этого приложения сделав сервис для просмотра статистики игр NBA.

На протяжении всех видеоуроков и вебинаров мы будем поэтапно строить приложение, используя все техники разработки на фронтенде, которыми пользуются наши разработчики. [Ссылка на дизайн](https://www.figma.com/file/awoXaWSO2PRjZIUCmVaf3J/NBA?node-id=0%3A1)

### Домашние задания:

_Первая неделя:_
- Сделать индикатор выбранной игры. Взглянув на индикаторы, пользователь должен понять, сколько всего игр и на какой позиции находится выбранная игра.

_Второая неделя:_
- Сделать адаптивную вёрстку для планшетов и смартфонов. Придётся почитать, как использовать медиа выражения в CSS и про позиционирование элементов, потому что индикаторы должны быть позиционированными;
- Сделать автоматическое перелистование. Здесь вам нужно будет найти в JS какой-то метод, который позволит с какой-то переодичностью вызывать функцию;
- Сделать карусель перетаскиваемой. На маленьких устройствах, да даже на десктопе, не всегда удобно листать нажимая на кнопочки. Поэтому пользователю надо дать возможность листать с помощью пальца.

_Четвёртая неделя:_
- Вынести меню, которое используется для навигации по сайту ("Новости", "Команды", "Игроки") в общий компонент;
- Добавить компонент со списком новостей. Для самих новостей создайте тестовые данные, как это было сделано [тут](https://youtu.be/EjM2lfKrJLc?t=1635)
- Добавить [React Router](https://reacttraining.com/react-router/web/guides/quick-start), так, чтобы боковое меню оставалось всегда, а остальной контент рендерился в зависимости от секции.