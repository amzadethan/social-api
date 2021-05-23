### Development

For the default Flask development server.

1. Build the images and run the containers:

    sh
    $ docker-compose up -d --build
    

    Test it out at [http://localhost:3005](http://localhost:3005).

### Production

gunicorn + nginx.

1. Build the images and run the containers:

    sh
    $ docker-compose -f docker-compose.prod.yml up -d --build
    

    Test it out at [http://localhost:1337](http://localhost:1337)