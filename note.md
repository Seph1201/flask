## Some things to take note
- need to export FLASK_APP=/d/GitHub/flask/pushup_logger before running app

- To run app, execute command "flask run" at the project main page

- to start sqlite, start terminal on vs code
> python
> from pushup_logger import db, create_app
> db.create_all(app=create_app())

Can use DB Browser for sqlite to look into the file db.sqlite

