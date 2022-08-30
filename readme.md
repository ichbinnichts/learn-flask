# Notes
This is a project so i can learn Flask
## References
* https://www.youtube.com/watch?v=Z1RJmh_OqeA
* https://realpython.com/flask-by-example-part-2-postgres-sqlalchemy-and-alembic/
### Cmd codes used in this project
* pip install virtualenv
* pip install Flask-Migrate
* pip install psycopg2
* virtualenv env
* source env/bin/activate (activate env on linux distributions)
* env\Scripts\activate (activate env on windows)
* pip install flask flask-sqlalchemy

* python app.py (run)

#### Tips
* {% %} "this are for 'if, for, while' statements"
* {{}} "Thing like printed strings"
  
##### Config your database
* app.config['SQLALCHEMY_DATABASE_URI'] = 'postgresql://'username':'password'@localhost/'db name''
* app.config['SQLALCHEMY_TRACK_MODIFICATIONS'] = False
* db = SQLAlchemy(app)

###### DB Shell commands
* python
* from app import db
* db.create_all()