Step-up API
==================

[![Build Status](https://travis-ci.org/OpenConext/Stepup-API.svg)](https://travis-ci.org/OpenConext/Stepup-API) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/OpenConext/Stepup-API/badges/quality-score.png?b=develop)](https://scrutinizer-ci.com/g/OpenConext/Stepup-API/?branch=develop)

This component is part of "Step-up Middleware". See [Stepup-Deploy](https://github.com/OpenConext/Stepup-Deploy) for an overview and installation instructions for a complete Stepup system, including this component. The requirements and installation instructions below cover this component only.

## Warning :warning:

This project is currently a work in progress and is being used as a proof of concept. This means that it might not (fully) work yet.

## Requirements

* PHP 8.1+
* [Composer](https://getcomposer.org/)
* A web server (Apache, Nginx)
* A working [Middleware](https://github.com/OpenConext/Stepup-Middleware)
* Docker
* Docker Compose

## For developers

To create a development environment for this project, the following commands need to be executed:

```bash
$ docker compose up -d
$ docker compose exec stepup-api -c 'composer install'
```