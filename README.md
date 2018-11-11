# Overview
- Django tutorial app


# Usage

```
$ git clone https://github.com/i35-267/django-app.git
```
- サーバ起動
```
$ cd mysite/
$ python3.7 manage.py runserver
Performing system checks...

System check identified no issues (0 silenced).
November 11, 2018 - 14:03:38
Django version 2.1.3, using settings 'mysite.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.

...
```
`http://localhost:8000/admin/`
<img width="1277" alt="2018-11-11 23 05 06" src="https://user-images.githubusercontent.com/40228637/48313957-4cf33680-e606-11e8-8549-e28e02e1841b.png">


- テスト
```
$ python3.7 manage.py test polls
Creating test database for alias 'default'...
System check identified no issues (0 silenced).
.......
----------------------------------------------------------------------
Ran 7 tests in 0.038s

OK
```
