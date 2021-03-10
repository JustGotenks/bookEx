# **BookEx project** #

### **Updating Pycharm** ###
Run one line at a time, from top to bottom
```python
cd /PythonSpace/bookEx
python manage.py check
python manage.py makemigrations
python manage.py migrate
```
.

### **Latest Changes** ###

#### *03/09/20* ####

- created [**forms.py**](https://github.com/iGotenks/bookEx/blob/main/bookMng/forms.py) file
- added [**`postbook()`**](https://github.com/iGotenks/bookEx/blob/main/bookMng/views.py#L20-L37) function to views.py
- created [**postbook.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/postbook.html) file
- added [**postbook**](https://github.com/iGotenks/bookEx/blob/main/bookMng/urls.py#L6) path to urls.py
