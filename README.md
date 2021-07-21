GETTING STARTED

1 - Install requirements
  pip install -r requirements.txt
 
2 - Runserver on port 8000

    python manage.py runserver
    
    http://127.0.0.1:8000/
    
3 - Create superuser
    python manage.py createsuperuser
    
![Test Image 1](https://github.com/babbarutkarsh/ThapSpace-V1.0/blob/main/Thapspace_1.PNG)

We can show featured posts on homepage by clicking featured radio button while submitting the created post.

![Test Image 2](https://github.com/babbarutkarsh/ThapSpace-V1.0/blob/main/LatestPosts.PNG)

A contact form for asking queries and personal doubts

![Test Image 2](https://github.com/babbarutkarsh/ThapSpace-V1.0/blob/main/ContactForm.PNG)

After we click on 'view more' we can see all posts, using a paginator we have limited it to 5 posts in a page 

Also we can search posts based on Headline or Tags

![Test Image 2](https://github.com/babbarutkarsh/ThapSpace-V1.0/blob/main/SearchPosts.PNG)

Authentication System

Login Page

![Test Image 2](https://github.com/babbarutkarsh/ThapSpace-V1.0/blob/main/Login.PNG)

Register Page

![Test Image 2](https://github.com/babbarutkarsh/ThapSpace-V1.0/blob/main/Register.PNG)

Forget Password Page

![Test Image 2](https://github.com/babbarutkarsh/ThapSpace-V1.0/blob/main/ResetPassword.PNG)

After a user gets logged in then he/she can comment on the posts and if they are given the editor rights then they can create posts

![Test Image 2](https://github.com/babbarutkarsh/ThapSpace-V1.0/blob/main/Create_Posts.PNG)

This system comes with 5 different themes that are cached once selected. Also Django provides us with an admin panel of its own so we need not to make one.

