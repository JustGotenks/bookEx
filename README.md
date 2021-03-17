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

#### *03/16/20* ####

- added [**`displaybooks()`**](https://github.com/iGotenks/bookEx/blob/main/bookMng/views.py#L42-L51) function to views.py
- updated [**displaybooks.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/displaybooks.html#L17-L35)
- added [**displaybooks**](https://github.com/iGotenks/bookEx/blob/main/bookMng/urls.py#L7) path to urls.py
- created [**index.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/index.html#L1-L18) file
- added django title blocks to [**index.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/index.html#L4-L6), [**displaybooks.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/displaybooks.html#L4-L6), and [**postbook.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/postbook.html#L4-L6)

#### *03/09/20* ####

- created [**forms.py**](https://github.com/iGotenks/bookEx/blob/main/bookMng/forms.py) file
- added [**`postbook()`**](https://github.com/iGotenks/bookEx/blob/main/bookMng/views.py#L20-L37) function to views.py
- created [**postbook.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/postbook.html) file
- added [**postbook**](https://github.com/iGotenks/bookEx/blob/main/bookMng/urls.py#L6) path to urls.py
