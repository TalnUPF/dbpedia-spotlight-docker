Docker container image with [DBpedia Spotlight in Catalan](http://ca.dbpedia.org) 

### How to run

Assume your docker host is localhost and HTTP public port is 2240 (change these values if you need).

Run 
    
    docker build -f Dockerfile  -t catalan_spotlight .

And finally

    docker run -i -p 2240:80 catalan_spotlight spotlight.sh


