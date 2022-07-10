# django-restframework-jwt-only-use-username
## If necessary
### Social login(ex.slack)+Django-restframework-jwt
     If you sign up with a social login,
     you don't need a django password. 
## Requirements
* Python
* Django
* Django REST framework
## Installation
install using pip
<pre>
<code>
pip install django-restframework-jwt-only-use-username
</code>
</pre>

## Main project settings.py
<pre>
<code>
JWT_AUTH = {
    'JWT_SECRET_KEY': SECRET_KEY,
    'JWT_ALGORITHM': Algorithm,
    'JWT_ALLOW_REFRESH': True or False,
    'JWT_EXPIRATION_DELTA': Time,
    'JWT_REFRESH_EXPIRATION_DELTA': Time,
}
</code>
</pre>

