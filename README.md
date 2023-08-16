# flask1
### BASIC TERMS
- **Framework:** A framework is a structure that you can build software on. It serves as a foundation, so you're not starting entirely from scratch. Frameworks are typically associated with a specific programming language and are suited to different types of tasks.

### -INSTALLATION:metal:
1. Install python from official website
2. Create a virtual environment in the project directory
3. Install flask using pip
4. Now I have installed flask successffuly on my machine  
> :star:***ALWAYS REMEMBER TO ACTIVATE VIRTUAL ENVIRONMENT ELSE YOU WILL SEE ERROR MODULE NOT FOUND***:star:

## FIRST CODE:one:
-Using minimal demo code I completed my first 'Hello world!' app

## RENDERING HTML:heart_eyes: 
-Render html template from the ***template*** directory

## WORKING WITH SQLITE:confused:
-Add sqlite in app.py for database maagement  
-**Unable to make todo.db file using commands shown below**

   
```
(env) PS C:\Users\Gurdev Singh\Desktop\flask> python
    Python 3.10.5 (tags/v3.10.5:f377153, Jun  6 2022, 16:14:13) [MSC v.1929 64 bit (AMD64)] on win32
    Type "help", "copyright", "credits" or "license" for more information.
    >>> from app import db
    C:\Users\Gurdev Singh\Desktop\flask\env\lib\site-packages\flask_sqlalchemy\__init__.py:851: UserWarning: Neither SQLALCHEMY_DATABASE_URI nor SQLALCHEMY_BINDS is set. Defaulting SQLALCHEMY_DATABASE_URI to "sqlite:///:memory:".
        warnings.warn(
    >>> db.create_all()    
    >>>
```
-***RESOLVED:partying_face:*** the issue of .db file creation following:   
(https://www.pythonfixing.com/2022/02/fixed-neither-sqlalchemydatabaseuri-nor.html)
- Database created successfully
- Deploying app on Heroku
- Heroku successfully connected with github.
- Error deplying app currently.






