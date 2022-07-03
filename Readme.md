## Managment System

Create a Virtual Enviroment for the Auction System.
 cd Auction
> py -3 -m venv venv
venv\Scripts\activate



or

 pipenv shell
 pipenv install

Database Setup
python
    from App.model import db
    db.create_all()


