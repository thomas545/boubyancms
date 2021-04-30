# Boubyan CMS
### Django Documentation:

1. [Django](https://docs.djangoproject.com/en/2.0/releases/2.0/)


### Installation:

##### System Dependencies:
1. Install git on Linux:  
`sudo apt-get install -y git`
2. Clone or download this repo.
3. Install pip and vitualenv on Linux:  
`sudo apt-get install -y virtualenv`  
`sudo apt-get install -y python3-pip`
4. Create a virtual environment on Linux or Mac:  
`virtualenv -p python3 ~/.virtualenvs/boubyan`
5. Activate the virtual environment on Linux or Mac:  
`source ~/.virtualenvs/boubyan/bin/activate`
6. Install requirements in the virtualenv:  
`pip3 install -r requirements.txt`

##### Relational database is MySQL


9. Activate the virtual environment:  
`source ~/.virtualenvs/boubyan/bin/activate`
10. Make Django database migrations:
`python manage.py makemigrations`  
`python manage.py migrate`
then: `python manage.py runserver`
