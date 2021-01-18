# Instagram-app
 
  
# Description  
This is a Django application that allow users to have an account post pictures,like and comment on them
#  Live Link  
Click to visit the webite
# User Story  
  
* Sign in to the application to start using.
* Upload pictures to the application.  
* See  profile with all my pictures.
* Like a picture and leave a comment on it.
* Follow other users and see their pictures on my timeline.

  
# Setup and Installation  
To get the project .......  
  
1. Cloning the repository:  
 
 git clone :https://github.com/Abdisamad100/Instagram-app.git
2. Navigate into the folder and install requirements  
 
 cd Istagram-app pip install -r requirements.txt 
`
3. Install and activate Virtual  
- python3 -m venv virtual - source virtual/bin/activate  
4. Install Dependencies  
 
 pip install -r requirements.txt 
  
5. Setup Database  
  SetUp your database User,Password, Host then make migrate  
 
python manage.py makemigrations app 
Now Migrate  
  
 python manage.py migrate 
6. Run the application  
 
 python manage.py runserver 
 
7. Running the application  
 
 python manage.py server
8. Testing the application  
 
 python manage.py test 

# Known Bugs  
* The follow and unfollow buttons are not working properly 
* The likes are not implememnted properly
  
  
  
  
## Technology used  
  
* Python3.6
* Django 1.11
* Heroku
  
  
  
## Author  
Abdisamad Mohamed

## License 