# mobilerecharge-task
For setting up:

 git clone https://github.com/Jayati15/mobilerecharge-task.git
 
 cd recharge_task
 
 Activate the virtual environment:
 
 for macos:
 
   virtualenv env -p python
   
   source env/bin/activate
   
 Install the dependencies
 
 pip install -r requirements.txt
 
python manage.py makemigrations

python manage.py migrate

python manage.py runserver

The server is up on localhost:8000
 

