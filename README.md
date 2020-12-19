# Test Python Flask

This is the simple project called witch I made to test flask a microframework for Python. In the project I made a CRUD (Create, Read, Update, Delete) employee management web app.

 
### Installing (for linux)

open the terminal.


```
git clone https://github.com/osiastossou/testflask.git
```
```
cd testflask/
```
```
python3 -m venv venv
```
```
source venv/bin/activate
```
```
pip install --upgrade pip
```
```
pip install -r requirements.txt
```
```
export FLASK_CONFIG=development
export FLASK_APP=run.py
```
```

Create mysql DataBase with name : flask_test
Set the file instance/config.py with the database conf.
```
```

flask db init
```
```
flask db migrate
```
```
flask db upgrade
```
```
flask run
```