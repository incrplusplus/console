# Incr++

## Setup

`git clone` this repository:

```sh
$ git clone git@github.com:incrplusplus/console.git
```

Build apps:

```sh
$ docker-compose build
```

Setup Rails app:

```sh
$ docker-compose run web bundle install
$ docker-compose run web bundle exec rails db:create
```
