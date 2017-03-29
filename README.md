Monitoring Framework Setup
Server (Local Setup)
Node.js

    We need a NodeJS version that supports the setImmediate (>= 0.9)
    Download binaries or source from http://nodejs.org/download/
    Add binaries to your environment path via: export PATH=:$PATH
    e.g.: export PATH=/home/sane/Downloads/node/bin:$PATH

Elasticsearch

    Download package from web-site
    Start elasticsearch: sudo /etc/init.d/elasticsearch start

Starting the server

    node monitoring-framework-server/elasticnodetest1/app.js

