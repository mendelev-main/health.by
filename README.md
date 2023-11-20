# <span style="color:#3498db">health.by - Веб-сервис о твоем здоровье</span>

## Цель проекта 

Целью создания health.by служит хранение всех медецинских данных
в одном сервисе, создавая тем самым безграничные удобства 
использования сервиса как для пользователя, так и для медицинского работника.


### В проекте реализованы:
  - Регистрация и авторизация пользователей.
  - Создание собственного профиля пользователя.
  - Поиск врача [со стороны пользователя]
  - Поиск пациента  [со стороны медицинского работника]
  - Возможность создавать обращение в медицинские учреждение [со стороны медицинского работника]
  - Возможность просматривать обращения в медицинские учреждения [как со стороны мед работника, так и со стороны владельца профиля]
  - Возможность бронирования талона к необходимому медицинскому работнику
  - Также реализована новостная страница 

### FUTURE:
  - Получение уведомлений о новой информации связанной с профилем пользователя
  - Возможность отправки личных сообщений 
  - Возможность изменение формы обращения в зависимости от профиля медицинского работника 
  - Разработка API 
  - Создание Telegram bot на базе собственного API

### Работа с проектом:
Для работы с проектом вам понадобятся следующие зависимости:
  - python 3.11
  - django 4.2.6
  - django-registration 3.4
  - psycopg2-binary 2.9.9
  - pillow 10.1.0


### Установка:
1. Склонируйте репозиторий проекта на свой локальный компьютер:
  - git clone https://github.com/mendelev-main/health.by.git
2. Создайте и активируйте виртуальное окружение:
  - poetry shell
3. Установите необходимые зависимости из файла pyproject.toml:
  - poetry install
4. Примените миграции базы данных:
  - python manage.py migrate
5. Запустите сервер разработки:
  - python manage.py runserver

### Использование
1. Откройте браузер и перейдите на страницу http://127.0.0.1:8000/ для просмотра сайта.
2. Для создания нового профиля, необходимо зарегистрироваться на сайте или пройти авторизацию, если у вас уже есть аккаунт.
3. После авторизации, нажмите на кнопку "Statr using" в правой части навигационной панели и заполните необходимую информацию о себе.
4. В поиске вы можете найти врача по ФИО, ID или его лечащему профилю.
5. В профиле врача вы можете воспользоваться кнопкой Записаться и выбрать подходящую для вас дату
6. В личном профиле вы можете просматривать свои обращения 

### Контакты
Gmail: [mendelev.main@gmail.com](mailto:mendelev.main@gmail.com)




