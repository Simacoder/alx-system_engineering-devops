# 0x1A. Application server

## Concepts
For this project, we expect you to look at these concepts:
- [Web Server](https://intranet.alxswe.com/concepts/17)
- [Server](https://intranet.alxswe.com/concepts/67)
- [Web stack debugging](https://intranet.alxswe.com/concepts/68)

## Background Context
- Your web infrastructure is already serving web pages via Nginx that you installed in your first web stack project. While a web server can also serve dynamic content, this task is usually given to an application server. In this project you will add this piece to your infrastructure, plug it to your Nginx and make is serve your Airbnb clone project

## Resources
Read or watch:
- [Application server vs web server](https://intranet.alxswe.com/rltoken/B9fOBzIxX_t1289WAuRzJw)
- [How to Serve a Flask Application with Gunicorn and Nginx on Ubuntu 16.04](https://intranet.alxswe.com/rltoken/kpG6RwmwRJHzRmGUM_ERcA) (As mentioned in the video, do not install Gunicorn using virtualenv, just install everything globally)
- [Running Gunicorn](https://intranet.alxswe.com/rltoken/2LF1j7xKJGYaUtD1HKgUeQ)
- [Be careful with the way Flask manages slash in route - strict_slashes](https://intranet.alxswe.com/rltoken/lEg0zpkkDcLtdl3VD4ACRQ)
- [Upstart documentation](https://intranet.alxswe.com/rltoken/mcEsKqFsjJA3tHAjiMknaw)
 

# Tasks
# 0. Set up development with Python
- Let’s serve what you built for AirBnB clone v2 - Web framework on web-01. This task is an exercise in setting up your development environment, which is used for testing and debugging your code before deploying it to production.

## Requirements:
- Make sure that task #3 of your SSH project is completed for web-01. The checker will connect to your servers.
- Git clone your AirBnB_clone_v2 on your web-01 server.
- Configure the file web_flask/0-hello_route.py to serve its content from the route /airbnb-onepage/ on port 5000.
- Your Flask application object must be named app (This will allow us to run and check your code).

# 1. Set up production with Gunicorn
- Now that you have your development environment set up, let’s get your production application server set up with Gunicorn on web-01, port 5000.

# 2 Serve a page with Nginx
- Building on your work in the previous tasks, configure Nginx to serve your page from the route /airbnb-onepage/

# 3. Add a route with query parameters
- Building on what you did in the previous tasks, let’s expand our web application by adding another service for Gunicorn to handle. In AirBnB_clone_v2/web_flask/6-number_odd_or_even, the route /number_odd_or_even/<int:n> should already be defined to render a page telling you whether an integer is odd or even.

# 4. Let's do this for your API
- Let’s serve what you built for AirBnB clone v3 - RESTful API on web-01.

# 5. Serve your AirBnB clone
- Let’s serve what you built for AirBnB clone - Web dynamic on web-01.


# AUTHOR
- Simanga Mchunu
