What is this?
--------------
This is Dockerized image of NodeJS and NPM based on:

- [wernight/alpine-nginx-pagespeed](https://hub.docker.com/r/wernight/alpine-nginx-pagespeed).
- [mhart/alpine-node](https://hub.docker.com/r/mhart/alpine-node/)

Usage
---------------
Configuration is very similar to the official [Nginx image](https://hub.docker.com/_/nginx).

    $ docker run -d -p 8080:8080 waskito/alpine-node-nginx-pagespeed


Note
------
This is experimental repository only. Not yet tested on production.