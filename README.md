

# Screenshots

![psy](https://user-images.githubusercontent.com/39271713/75101431-7c586780-55ed-11ea-8f00-431714ade996.png)

**Psychology Blog** is a blog written in Python 3 and using Django framework.
The application allows users read and comment on posts. It allows authors to add Posts in the backend. 


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See installing instructions for notes on how to deploy the project on a live system.


### Prerequisites
You will find hereafter what I use to develop and to run the project
* Python 3.8
* Django 3.0.3
* Virtualenv (not mandatory but highly recommended)

### Installing
Get a local copy of the project directory by cloning "Psychology Blog" from github. `git clone https://github.com/BabGee/psych-blog.git`
I use Virtualenv for developing this project so I recommend you to create a virtual environment, `virtualenv venv`, activate the virtual environment `source venv/Scripts/activate`  and to install the requirements `pip install -r requirements.txt`.

Then follow these steps:
1. Move to root folder `cd psychology`
2. Create the tables with the django command line `python manage.py makemigrations` then `python manage.py migrate`
3. Create your admin log in credentials to add Posts in the backend `python manage.py createsuperuser`
4. Finally, run the django server `python manage.py runserver ` go to /admin and add posts 


## Built With

* [Python 3](https://www.python.org/downloads/) - Programming language
* [Django](https://www.djangoproject.com/) - Web framework 


## Versioning
I use exclusively Github

## License

This is an open source project not under any particular license.
However framework, packages and libraries used are on their own licenses. Be aware of this if you intend to use part of this project for your own project.




