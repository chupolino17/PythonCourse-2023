## DevOps

___Обязательная часть:___
- вы должны создать и залить свой проект на github
- ваш проект должен подниматься с помощью docker-compose
- в корне проекта должен быть скрипт build.sh, который поднимает сервис, проводит миграции, если необходмио и т.д. Результатом его работы должно быть поднятие полностью работоспособного сервиса
- в проекте обязателен README, в котором указаны тонкости вашего проекта, как его использвовать, и что он делает. (Если есть фронт, должен быть туториал по работе с сервисом со скринами)

## Скрапинг

___Ограничения:___
- у сервиса, который вы скрапите, не должно быть открытого API (если вы заплатили/договорились за доступ к API, так тоже нельзя)
- сервис должен быть доступен для всех пользователей
- у каждого должен быть свой ресурс, который вы скрапите

___Обязательная часть:___
- вы должны уметь вычленять какую-нибудь полезную информацию и как-то ее обрабатывать
>Например: у вас есть сайт https://aeroflot.ru, и вы научились с него получать данные о стоимости билетов по одному направлению, на выделенную дату. Тогда вы можете составить и обновлять таблицу, в которой будут актуальные сведения по всем направлениям и датам. И по запросу возвращать лучшую дату или самые выгодное направление на выбранные числа

___Необязательная (бонусная) часть:___
- использовать краулинг роботов, по типу scrapy

## Сервис

___Обязательная часть:___
- должен быть реализован бэкенд на питоне. Пожалуйста, не изобратайте велосипед, и используйте доступные в opensource фреймворки (flask, fastapi, django и т.д.)

___Необязательная часть:___
- будет здорово, если будет реализован фронт, который поднимается в отдельном контейнере

## Хранение данных

___Минимальная часть:___
- предлагается хранить ваши данные в sqllite, но при пересборке сервиса, данные должны оставаться

___Необязательная часть:___
- использовать любую базу данных, которая поднимается в отдельном контейнере, но при пересборке проекта, данные тоже должны оставаться на своем месте

После того, как вы прочитали все условия, необходимо заполнить форму https://forms.yandex.ru/u/65448ad35056908723cb026f/