# Music Quiz
Django based Music Quiz
#How to Run
The Music quiz can be run by using the link : http://grahammurphy.pythonanywhere.com/quiz/ for the main quiz page.


The quiz can also be downloaded and run through the Terminal.

Navigate to directory where file was downloaded to. 

To install the required libraries for this file, simply run the following:

    pip install -r requirements.txt
    
# Running the project

To run this project:

	# Navigate into directory containing manage.py
    cd directory location of download

    # Setup the database
    python manage.py migrate
    python manage.py makemigrations

    # Run the server
    python manage.py runserver
    
You can now visit the following URLS:

	* http://127.0.0.1:8000/admin
	* http://127.0.0.1:8000/quiz
	*


In order to access the admin page, an account must be set up.

To access currently ; Username is admin and password is password.
