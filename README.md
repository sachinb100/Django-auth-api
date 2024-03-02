# Django-auth-api
API developed using Django Rest Framework.


 • User can signup, login, get profile data, change password through a RESTful API.

## Run Locally

Clone the project

```bash
  git clone https://github.com/sachinb100/Django-auth-api.git
```

Go to the project directory

```bash
  cd <app-name>
```

Create a virtual environments
```bash
python -m venv env
```


Activate the virtual environment
```bash
On Windows
env\Scripts\activate


On macOS and Linux:
source venv/bin/activate

```

Install requirements
```bash 
    pip install -r requirements.txt
```

Make migrations in database
 ```bash
python manage.py makemigrations
```

Migrate to database

```bash
python manage.py migrate
```

Run the project(in terminal)

```bash
python manage.py runserver
```
API access
```bash
Access the API at http://127.0.0.1:8000/api/
```
For testing:

<b>You can use Postman API to  test this API.</b>


