# Docker_Nginx-Vue-Nginx-Django
Веб сервис на Docker с Frontend и Backend
Проект состоит из двух частей fronend и backend.
Frontend состоит из nginx, Vuejs. Backend состоит из nginx, gunicorn, docker, postgres, pgadmin.
1. Скопируйте ваш backend проект django в папку "Project/FBackend/"
2. Скопируйте backup postgress в папку "Docker/backend/Postgres/pgadmin
3. Скопируйте ваш проект frontend в папку Project/Frontend/
    Если у вас уже собраный броект для публикации после команды "yarn run Build" то поместите папку dist в Project/Frontend/. 
    Если у вас не собран то скопируйте весь проект в Project/Frontend/. Откройте командную строку и выполните docker-compose up из папке Project/Frontend/. Проект будет собран
4. Выполните docker-compose up из основной папке  "Docker_Nginx-Vue-Nginx-Django". 
5. В браузере откройте http://127.0.0.1:8001 и в окне PGadmin подключитесь к postgres серверу. Создайте подклчение к ip 172.16.0.7 порт по умолчанию. Востановите базу данныйх которую использует Django
6. Выполните команду "Docker-compose down" из основной папке "Docker_Nginx-Vue-Nginx-Django"
7. Выполните команду "Docker-compose up" из основной папке "Docker_Nginx-Vue-Nginx-Django" 

Сервер запущен.