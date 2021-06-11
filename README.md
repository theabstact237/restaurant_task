# restaurant_task
Company needs internal service for its’ employees which helps them to make a decision on lunch place. Each restaurant will be uploading menus using the system every day over API and employees will vote for the menu before leaving for lunch. The solution can be presented in the Docker environment, which will add additional Karma points.

1)download or clone the repository
2)To install the project in your workstation without docker:
    -pip install -r requirements.tx
    -cd virtualenv
    -. Scripts/env to activate the virtual environement
    -python manage.py makemigrations
    -python manage.py migrate
    -python manage.py runserver
3)To connect to the authentication Api endpoints
   -Visit http://127.0.0.1:8001/rest-auth/registration/ to register
   -Visit http://127.0.0.1:8001/rest-auth/login/
4)To connect to the restaurant Api endpoints
   -Visit http://127.0.0.1:8000/restaurants/
   -Visit http://127.0.0.1:8000/menus/
   -Visit http://127.0.0.1:8000/votes/
   
5)To connect to the API schema  which describes the operations of a RESTful API and the methods on how to interact with an API
  --Visit http://127.0.0.1:8000/docs/
  
6)To install the poject in your workstation with docker
  -docker run -t -p 80:8000  restaurant-tasks 
  -Now open up http://localhost
  -
