# Python Rapid Stack | Cookiecutter Project Template

***This is a work-in-progress.  This template is not ready to use.  Yet!***

*A rapid-prototyping software stack for backend Python Apps.*

I frequently find myself using a common backend software stack for rapidly prototypying Python apps and automations.  Containers and Docker Hub images make things much easier, but you still have setup all the boilerplate configuration files and code to get everything connected.  I'd rather template all if this and start from, "Stack Ready!"

## Features

Projects created from this template will have the following capabilities configured and integrated right from the start:

- Fast Python backend web service (configured to serve RESTful API endpoints and templated web views)
- Background asyncronous task queuing service for executing long-running or scheduled tasks
- Schema-less NoSQL database
- Database and application services are configured and deployed as micro-service containers in a preconfigured application stack

## Technologies & Frameworks Used

- [Python Responder](https://python-responder.org/en/latest/) - a familiar HTTP Service Framework for Python
- [MongoDB](https://www.mongodb.com/) - open-source JSON-like document oriented database
- [Celery](http://www.celeryproject.org/) - asynchronous task/job queuing service
- [Redis](https://redis.io/) - open-source, networked, in-memory, key-value data store
- [Docker](https://www.docker.com/) - Container runtime
- [Docker-Compose](https://docs.docker.com/compose/) - app stack deffinition

## Using the Project Template

### The First Time

```bash
$ cookiecutter https://github.com/CiscoSE/cc-rapid-stack
```

...or using abbreviated syntax:

```bash
$ cookiecutter gh:CiscoSE/cc-rapid-stack
```

### Thereafter

```bash
$ cookiecutter cc-rapid-stack
```

## Cookiecutter Installation

If you have a working Python development environment, installation is simple:

```bash
$ pip install cookiecutter
```

If you need a bit more help than that, see the Cookiecutter [Installation](https://cookiecutter.readthedocs.io/en/latest/installation.html) docs.

## Credits

The following excellent resources were influencial in the creation of this project:

- [Cookiecutter](https://github.com/audreyr/cookiecutter) by Audrey Roy Greenfeld ([@audreyr](https://github.com/audreyr))
- [Python Responder](https://python-responder.org/en/latest/) - making rapid API prototyping fast and easy!

## Who is this for?

This project template is for use by **Cisco Systems Engineers** who are creating example and demonstration code *(aka. Cisco Sample Code)* and sharing it with Cisco's customers and partners for use with Cisco products and services.  **The Cisco Sample Code License is for use in Cisco Repositories Only.**  It is not an Open Source license. The license should only be used by Cisco and/or its affiliates to post and share Cisco Sample Code.
