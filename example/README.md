[![RoR](https://img.shields.io/badge/RoR-5.1.5-blue.svg)]()
[![Postgres](https://img.shields.io/badge/Postgres-10.3.0-blue.svg)]()
[![Node](https://img.shields.io/badge/Node-8.X-blue.svg)]()
[![ruby](https://img.shields.io/badge/ruby-2.5.0-blue.svg)]()

# README

> Check [Quickstart: Compose and Rails](https://docs.docker.com/compose/rails/) for more details.

#### Development setup

* Add file `.env` to root folder
* `docker-compose build`
* `docker-compose run web bundle install`
* `docker-compose run web bin/yarn`
* `docker-compose run web rake db:setup`

#### Mount application
* `docker-compose run --service-ports web`
* Open `localhost:3000` with any browser
