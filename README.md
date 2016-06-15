# Flask structure example

Это законченный пример к записи в моем блоге 
[правильной структуры flask приложения](https://the-bosha.ru/2016/06/03/python-flask-freimvork-pravilnaia-struktura-prilozheniia/).

## Setup

```
git clone https://github.com/bosha/flask-app-structure-example/
cd flask-structure-example
virtualenv -p python3 env
source env/bin/activate
pip install -r requipments/development.txt
export APP_SETTINGS="config.DevelopmentConfig"
export DATABASE_URL='postgresql://DBUSERNAME:DBPASSWORD@localhost/DBNAME'
python manage.py db init
python manage.py db migrate
python manage.py db update
python manage.py runserver
```
