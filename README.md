# django-blog-9
Lesson 09 Assignment: Django Deployment

My blog is deployed here: https://py230-ubuntu009000.westus.cloudapp.azure.com/

I am using an Ubuntu server and a Postgres database.

In order to make the Facebook login work, I had to secure my site with HTTPS.  
However, some features won't work until the app is in production.

I am running my blog application as a service and it will automatically reload if the server gets restarted.