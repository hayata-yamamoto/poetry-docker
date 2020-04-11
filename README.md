# poetry-docker 

[![dockeri.co](https://dockeri.co/image/hayata/poetry-docker)](https://hub.docker.com/r/hayata/poetry-docker)

[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-360/)
[![CircleCI](https://circleci.com/gh/hayata-yamamoto/poetry-docker/tree/master.svg?style=svg)](https://circleci.com/gh/hayata-yamamoto/poetry-docker/tree/master)

## Usage 

```bash
$ cd poetry-docker 
$ docker build -t poetry-docker .
$ docker run -it poetry-docker example.py 
>>> Hello World
```

## TODO 

- [ ] Dockerfile / poetry based
- [x] Dockerfile / only use poetry on first stage build
