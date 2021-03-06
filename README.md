__FILMIK__ – приложение для ценителей кино

:mortar_board: Личный проект, созданный с пустой папки до публикации.

:eyes: Оценить приложение в сети можно [тут](https://filmik-dev.herokuapp.com) (возможно понадобится подождать 15-30 секунд пока запустится сервер, это особенность работы бесплатного хостинг-провайдера Heroku).

:construction: Репозиторий с кодом проекта приватный. Выдаётся по согласованию, персонально. Свяжитесь со мной через [![Telegram](https://img.shields.io/badge/-Telegram-090909?style=for-the-badge&logo=telegram&logoColor=27A0D9)](https://t.me/gasmg_dev)

<br />__Мною реализовано__:
- Разработка дизайна
- Вёрстка
- Программирование
- Подготовка ресурсов для работы с backend

<br />__Функционал приложения__:
- Реализован гибкий фильтр по жанрам, странам и годам с возможностью удобной частичной отмены выбранных параметров. При выборе параметров вы сразу видите результат выборки<br />
  
![](https://raw.githubusercontent.com/gasmg/filmik-desc/main/assets/filter.png)
- При работе с фильтром и пагинацией у пользователя есть возможность поделиться ссылкой с кем-либо в сети и получатель ссылки получит то, что он выбрал. Перезагрузка страницы не приводит к сбросу выбранных параметров
- Рекомендации схожих кинокартин при их наличии<br />
  
![](https://raw.githubusercontent.com/gasmg/filmik-desc/main/assets/similar-films.png)
- Пагинация
- Поиск по названию
- Возможность добавления кинокартин в избранное, а кинопремьер в список `Буду смотреть` с последующим раздельным просмотром<br />
  
![](https://raw.githubusercontent.com/gasmg/filmik-desc/main/assets/favourites.png)
- Подсчёт количества дней до кинопремьер
- Получение текущего рейтинга кинокартин
- При просмотре описания кинокартины предоставлена возможность перейти к списку желаемых жанров и стран, которые ей принадлежат<br />
  
![](https://raw.githubusercontent.com/gasmg/filmik-desc/main/assets/direct-transition.png)

<br />__Какая была мотивация сделать этот проект?__
-  Реализовать сложный фильтр, чтобы пользователь одновременно мог получить и гибкость и мгновенный результат выборки
-  Укрепление навыков при работе с React и понимания как правильно работать со стейт-менеджером useReducer в связке с useContext. Прекрасная альтернатива Redux, при условии если вам не нужны middlewares
- Практика вёрстки с неймингом классов по методологии BEM
- Реализация поиска
- Реализация пагинации
- Дополнительная практика в разрабатывании пользовательских интерфейсов