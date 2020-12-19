# Test Python Flask

In this three-part tutorial, we’ll build a CRUD (Create, Read, Update, Delete) employee management web app using Flask, a microframework for Python. I’ve named the app Project Dream Team, and it will have the following features:

Users will be able to register and login as employees
The administrator will be able to create, update, and delete departments and roles
The administrator will be able to assign employees to a department and assign them roles
The administrator will be able to view all employees and their details
 

 
### Installing (for linux)

open the terminal and follow the white rabbit.


```
git clone https://github.com/osiastossou/example-flask-crud.git
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

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
