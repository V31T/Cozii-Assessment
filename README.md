#Cozii technologies Application!!

1. clone the repo
```bash
git clone https://github.com/V31T/Cozii-Assessment.git
```

2. navigate into the project directory 
``` cd Users/../Cozii-Assessment```

3. install pipenv (I use pipenv install of venv)
```pip install pipenv```

4. run pipenv shell
```pipenv shell```

5. install dependencies into the virtual environment
```pipenv install -r requirements.txt```

6. navigate to directory that contains manage.py
```cd marsProject```

7. migrate changes just in case (django is silly sometimes)
```python manage.py migrate```

8. run the server
``` python manage.py runserver ```

9. click the link within the console, should be running on port 8000

10. apply to go to mars!!

