# Library-Management-System

The repository contains web pages using Django web development framework in python language. It contains
  a) Two Forms Students and Books 
  b) One Form to issue a book to particular student. (where multiple transaction require on one student).
 
## Getting Started
 

Open terminal using Ctrl + Alt + T. Run the following command <br>
```
   git clone https://github.com/vcode4u95/LMS.git
```

Create and activate virtual environment using <br>
```
   virtualenv -p python3 venv
```
<br>

``'
    cd venv
``` 
<br>

```
   source bin/activate
``` 
<br>

### Run Steps:
```
   cd ..
```

```
   cd LMS
```


```
   python manage.py makemigrations
```

```
   python manage.py migrate
``` 

```
   python manage.py runserver
``` 
