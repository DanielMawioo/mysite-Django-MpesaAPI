### Mpesa(Daraja Api) and Django integration.

Created on, September 24th 2021

## Technologies used

- Django
- Daraja Api
- Git

## Tools

- Postman
- Git
- ngrok

## Development and Setup.

### prerequisites

- Python 3.8+ should be installed
- django 3.0 +


### Installation.

- Ensure python3.8+ is installed.
- Clone the repository git clone <repo url>
- create a virtual environment virtualenv <envname> and activate source <envname>/bin/activate
- Install the required packages pip3 install -r requirements.txt
- set up your database.
- Once the database is set up, make migrations. This creates database schemas for the application python manage.py -makemigrations
- Then create the actual database tables by python manage.py migrate
- Start the application by python manage.py runserver and open http://127.0.0.1:8000 in the browser.



## Further help

To get Further help you can visit the official python ,django, django_daraja, daraja-api documentation.

## Licence

[MIT License](LICENSE) (c) 2021 Daniel Mawioo
