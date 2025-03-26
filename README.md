# bu_banking



## Running the application
1. Run: `docker build -t banking` in the terminal.
2. After succesfull build run the container from image: `docker run -p 8001:8000 banking`
3. Access the website on your localhost http://127.0.0.1:8000/api/


## Running tests
- Make sure you are in your virtual environment first.
- Run: `python manage.py test`