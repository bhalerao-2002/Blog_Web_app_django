# Django_blog
blog website using django framework also provided admin panel , where you can control , write and modify blogs ..


### To run this project 

1. clone into your local machine :  ``` git clone https://github.com/shubhamAW/Django_blog.git```
2. go to project using ```cd django_blog```
3. go to inside folder ```cd django_blog ```
4. now to install and activate virtual environment type command : ``` pipenv shell```
5. Now install django to your inside the virtual environment : ``` pipenv install django ```
6. Now run this project using : ```djangoenv/bin/activate ``` 
7. head over to http://127.0.0.1:8000/ to see the output
8. You will see the output window : 
![image](https://user-images.githubusercontent.com/66414385/171388000-0c754e8b-6073-4e3b-b822-c3c9765c5326.png)

### Now you only see the blog but you will not able to write or modify or delete . 

for that you need to access the admin , for this you need to create a superuser and provided the login information and login ..

1. to create a super user run ``` python manage.py createsuperuser``` 
2. This will ask you username : 
                     password : 
                     Email: 
                     
3.run again ```python manage.py runserver ```
4. Now to go http://127.0.0.1:8000/admin/ and login with your username and password .
5. output : 
  ![image](https://user-images.githubusercontent.com/66414385/171389285-24ab1a30-c8f9-4f8f-94e2-aa3a1b5f7c4c.png)
Now you can add blog , delete and update the blog posts..
