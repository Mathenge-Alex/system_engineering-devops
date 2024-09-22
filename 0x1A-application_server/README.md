## 0x1A-application_server
##### Background Context

Your web infrastructure is already serving web pages via Nginx that you installed in your first web stack project. While a web server can also serve dynamic content, this task is usually given to an application server. In this project you will add this piece to your infrastructure, plug it to your Nginx and make is serve your Airbnb clone project.

##### Resources:
* [Application server vs Web server](https://www.nginx.com/resources/glossary/application-server-vs-web-server/)
* [How to Serve a Flask Application with Gunicorn and Nginx on Ubuntu 16.04](https://www.digitalocean.com/community/tutorials/how-to-serve-a-flask-application-with-gunicorn-and-nginx-on-ubuntu-16-04)
* [Running Gunicorn](http://docs.gunicorn.org/en/stable/run.html)
* [Be careful with the way Flask manages slash](http://werkzeug.pocoo.org/docs/0.14/routing/)
* [Upstart documentation](http://upstart.ubuntu.com/cookbook/)
* [How to set up Nginx to proxy to Gunicorn](https://www.digitalocean.com/community/tutorials/how-to-set-up-django-with-postgres-nginx-and-gunicorn-on-ubuntu-18-04#step-7-creating-systemd-socket-and-service-files-for-gunicorn)