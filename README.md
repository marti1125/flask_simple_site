Flask Web Project
=================

* Installation:
 
        $ virtualenv venv
        $ venv\Scripts\activate
        $ pip install -r requirements.txt

* Databases Creating Tables:
 
        (venv) $ python hello.py shell
        >>> from hello import db
        >>> db.create_all()

* Creating a Migration Repository:

        (venv) $ python hello.py db init
        (venv) $ python hello.py db migrate -m "initial migration"
        (venv) $ python hello.py db upgrade

* Email Configuration in Windows:

        (venv) $ set MAIL_USERNAME=<Gmail username>
        (venv) $ set MAIL_PASSWORD=<Gmail password>
		(venv) $ export FLASK_ADMIN=<your-email-address>
        (venv) $ set FLASK_ADMIN=<Gmail username>


        