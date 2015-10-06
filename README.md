# node-cms-api
NodeJS simple API for create, update, detele article, use Elasticsearch as Database
## Start Elasticsearch with docker
1. Install docker http://docker.com
2. Run with command - Elasticsearch will start docker container as background.
  See more at https://github.com/docker-library/docs/tree/master/elasticsearch
  ````````````````````````````````````````
  docker pull elasticsearch:latest
  docker run -d elasticsearch:latest
  ````````````````````````````````````````
Or use fig - file config of Fig : fig.yml
```````````````````````````````````````````
fig up
```````````````````````````````````````````
