Example Counter App
===================

A simple distributed application that counts the number of visits to the web page.

Getting started
---------------

Download [Docker Desktop](https://www.docker.com/products/docker-desktop) for Mac or Windows. [Docker Compose](https://docs.docker.com/compose) will be automatically installed. On Linux, make sure you have the latest version of [Compose](https://docs.docker.com/compose/install/). 


## Containers

The stack runs Node.js with Redis in different containers. 



For running the app, navigate to npm-docker folder

```
cd npm-docker
```

Run the app using:

```
docker-compose -f docker-compose.yml up -d
```

Open the browser and navigate to http://localhost:9001. Initially the count is 0. As you refresh the page the counter increases.
The counter value is stored in Redis. As the webpage is refreshed the counter value is incremented by 1.



