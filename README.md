## About

Django interface to manage RFID lock users

## Quick start

Clone the repository. 

    $ git clone git@github.com:gnarlinsky/rfid-lock-admin.git

To avoid dependency issues, create a virtualenv and install the required packages.

    $ cd rfid-lock-admin
    $ virtualenv ve --no-site-packages
    $ source ve/bin/activate      # activate the virtual environment
    $ pip install -r requirements.txt

Create the database and load the initial data.

    $ python manage.py syncdb
    $ python manage.py loaddata rfid_lock_management/fixtures/initial.json

Run the Django development server. 

    $ python manage.py runserver   

Go to [http://localhost:8000/lockadmin](http://localhost:8000/lockadmin) to see the application in action.  (You can log in as user "moe" and password "moe") 

## Details
See [http://gnarlinsky.github.io/rfid-lock-admin](http://gnarlinsky.github.io/rfid-lock-admin) for more details about the project and walkthroughs of some basic tasks. 
