Link site: https://book-evaluator.herokuapp.com/

Code: https://github.com/Vukan-Markovic/Book-evaluator

Project theme: Web app for evaluating, commenting, reading and searching books with supported authentication.

Short description of the application:

Registered users have the ability to rate books and comment on them, delete them and edit their comments and ratings,
reading individual books as well as creating logs of read books with the ability to search. Each registered user has his own profile
with some basic information about it and its activity on the site and the ability to view other users' profiles.
Unregistered users can review books, comments, ratings, profiles of other users and search the books without any other options.
The site administrator has all the capabilities of the registered user and also the ability to delete and change the ratings and comments of all users
as well as a review of all registered users with the possibility of their deletion.

Books are delivered through the Google Books API (https://developers.google.com/books/).

Technologies:

The following applications were used to create the application:
- Flask web python framework (http://flask.pocoo.org/)
- CS50.io development environment (https://cs50.io)
- phpliteadmin database (https://www.phpliteadmin.org/) i
- host service for hosting (https://www.heroku.com/).

Sources:
- https://www.edx.org/course/cs50s-introduction-computer-science-harvardx-cs50x
- http://ellab.ftn.uns.ac.rs/moodle/course/view.php?id=560
- http://flask.pocoo.org
- https://stackoverflow.com
- https://www.youtube.com/watch?v=4_RYQJfiuVU
- https://bootswatch.com/minty

Installing all necessary startup packages in the CS50 environment by executing the command: pip3 install --user -r requirements.txt.

To run locally:
- install git
- git clone
- install python  
- install python3 
- install virtualenv
- virtualenv -p python3 venv
- source venv/bin/activate 
- pip install -r requirements.txt
- export FLASK_APP=application.py 
- export FLASK_DEBUG=1 
- flask run
App is running on http://127.0.0.1:5000.