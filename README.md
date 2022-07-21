# Heroku


Machine-learning (ML) deployment involves placing a working ML model into an environment where it can do the work it was designed to do.

Heroku provides three different ways to deploy models: Heroku git, GitHub, and the container registry. The Git technique is used in this post to deploy the model. The GIT and Heroku CLI (You can create and administer Heroku apps straight from the terminal using the Heroku Command Line Interface (CLI).)

![image](https://user-images.githubusercontent.com/67821036/180205296-18d43651-bda6-45e3-8fc6-04596f24f080.png)


## configuration files

### procfile
this file is created for mentioning the file that has to be run at the beginning. (flask app name also has to be included)

example:
```
web: gunicorn app:app
```

### requirements.txt

What is the requirements txt file?
In Python requirement. txt file is a type of file that usually stores information about all the libraries, modules, and packages in itself that are used while developing a particular project.

```
Flask==1.1.1
gunicorn==19.9.0
itsdangerous==1.1.0
Jinja2==2.10.1
MarkupSafe==1.1.1
Werkzeug==0.15.5
numpy>=1.9.2
scipy>=0.15.1
scikit-learn>=0.18
matplotlib>=1.4.3
pandas>=0.19
```

These libraries will be used for deploymeny in heroku
## Documentations

[AWS](https://docs.aws.amazon.com) 

[Heroku](https://devcenter.heroku.com/categories/reference)

[sklearn](https://devdocs.io/scikit_learn/) 

[Flask](https://flask.palletsprojects.com/en/2.1.x/) 




## Author 

- [@Anshumaan031 - <anshuphukan031@gmail.com>](https://github.com/Anshumaan031)
