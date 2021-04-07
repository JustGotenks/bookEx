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

## **Latest Changes** ##

#### *04/06/21* ####
- added [**`Register()`**](https://github.com/iGotenks/bookEx/blob/main/bookMng/views.py#L58-L65) class to views.py
    - added imports:
        ```
        from django.views.generic.edit import CreateView
        from django.contrib.auth.forms import UserCreationForm
        from django.urls import reverse_lazy
        ```
- created [**registration**](https://github.com/iGotenks/bookEx/tree/main/bookEx/templates/registration) directory (/bookEx/templates/**registration**)
    - created [**register.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/registration/register.html), [**login.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/registration/login.html), [**register_success.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/registration/register_success.html) files
- added [**`span`**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/base.html#L19-L27) tag to base.html for Login/Logout
- added 3 new [**path()**](https://github.com/iGotenks/bookEx/blob/main/bookEx/urls.py#L26-L29) to /bookEx/urls.py (**_not_** /bookMng/urls.py)
    - added imports:
        ```
        from django.views.generic.base import TemplateView
        from bookMng.views import Register
        ```

#### *03/16/21* ####
- added [**`displaybooks()`**](https://github.com/iGotenks/bookEx/blob/main/bookMng/views.py#L42-L51) function to views.py
- updated [**displaybooks.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/displaybooks.html#L17-L35)
- added [**displaybooks**](https://github.com/iGotenks/bookEx/blob/main/bookMng/urls.py#L7) path to urls.py
- created [**index.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/index.html#L1-L18) file
- added django title blocks to [**index.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/index.html#L4-L6), [**displaybooks.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/displaybooks.html#L4-L6), and [**postbook.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/postbook.html#L4-L6)

#### *03/09/21* ####
- created [**forms.py**](https://github.com/iGotenks/bookEx/blob/main/bookMng/forms.py) file
- added [**`postbook()`**](https://github.com/iGotenks/bookEx/blob/main/bookMng/views.py#L20-L37) function to views.py
- created [**postbook.html**](https://github.com/iGotenks/bookEx/blob/main/bookEx/templates/bookMng/postbook.html) file
- added [**postbook**](https://github.com/iGotenks/bookEx/blob/main/bookMng/urls.py#L6) path to urls.py
