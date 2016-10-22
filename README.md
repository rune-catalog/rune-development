# rune-development
A development environment for the Rune API

### How to get started

``` bash
git -v
docker -v
docker-compose -v
git clone git@bitbucket.com:<project>/development.git <project> && cd <project>
git submodule init && git submodule update
git submodule foreach npm install
docker-compose up -d
```
