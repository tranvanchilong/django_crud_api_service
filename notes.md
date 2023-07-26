
# chạy project 

docker-compose -f docker-compose-test.yml up

# host

http://127.0.0.1:5002/person





# vào thư mục web_mod apk chạy 2 câu lệnh dưới đẻ tạo môi trường doker

docker build -t api_django .
docker run --name docker_django_api -p 5001:8000 -it -v ${PWD}/app:/app:rw api_django /bin/bash

# vào thư mục app

cd /app

# chạy câu lệnh dưới để khởi động web

uvicorn app:app --reload --host 0.0.0.0 --port 8000
npm run serve --host 0.0.0.0 --port 8000

# truy cập vào web bằng đường dẫn

http://0.0.0.0:5001/

# lần khác cần vào docker đã tạo thì không càn tạo lại như bước 1

docker start docker_an12
docker attach docker_an12

buoi1 copy 
buoc2 requeiment
bươc3 docker 
buoc4 chay
buoc 5 xoa chat gpt
buoc 6 copy 


docker login registry.gitlab.com
docker build -t registry.gitlab.com/tranvanchilong/async_web_gia:v0.1 . 
docker run --name test -it -p 5002:8000 -v ${PWD}/app:/app:rw registry.gitlab.com/tranvanchilong/async_web_gia:v0.2 /bin/bash 
registry.gitlab.com/tranvanchilong/async_web_gia:v0.2
docker push registry.gitlab.com/tranvanchilong/async_web_gia:v0.1

ALLOWED_HOSTS = ['139.162.28.246', 'yourdomain.com', 'localhost', '*']

python manage.py runserver
python manage.py runserver 0.0.0.0:8000
long123
tranvanchilong@gmail.com
a0977293389
python manage.py makemigrations
python manage.py migrate 
python manage.py createsuperuser

docker-compose -f docker-compose-test.yml up

https://stackoverflow.com/questions/69665222/node-js-17-0-1-gatsby-error-digital-envelope-routinesunsupported-err-os
https://stackoverflow.com/questions/35760943/how-can-i-enable-cors-on-django-rest-framework


asgiref==3.5.2
Django==4.0
djangorestframework==3.14.0
gunicorn==20.1.0
pytz==2022.6
sqlparse==0.4.3
tzdata==2022.6


anyio==3.7.1
asgiref==3.5.2
click==8.1.5
Django==4.0
django-cors-headers==4.2.0
djangorestframework==3.14.0
gunicorn==20.1.0
h11==0.14.0
httptools==0.6.0
idna==3.4
python-dotenv==1.0.0
pytz==2022.6
PyYAML==6.0
sniffio==1.3.0
sqlparse==0.4.3
starlette==0.27.0
tzdata==2022.6
uvicorn==0.20.0
uvloop==0.17.0
watchfiles==0.19.0
websockets==11.0.3