# rune-development
A development environment for the Rune API

### How to get started

``` bash
git -v
docker -v
docker-compose -v
git clone git@github.com:rune-catalog/rune-development.git && cd rune-development
git submodule init && git submodule update
git submodule foreach npm install
docker-compose up -d
```
