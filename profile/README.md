# Micro Services for Komponenten Basierte Entwicklung (KBE) course at HTW Berlin
This is a micro services project that is implemented with [Django](https://www.djangoproject.com/) and [DRF (Django Rest Framework)](https://www.django-rest-framework.org/) with a React front end. The services have a similiar configuration and CI/CD pipeline and therefore we created a [boilerplate / template repository](https://github.com/LN-Django/boilerplate) for further use. All of the services are deployed on Heroku as its own application and the production links are displayed in the corresponding repository.

## Architecture Diagram
![Architecture Diagram](https://github.com/LN-Django/boilerplate/blob/main/docs/architecture_diagram.png?raw=true)

## Sequence Diagram
![Sequence Diagram](https://raw.githubusercontent.com/LN-Django/boilerplate/main/docs/sequence_diagram2.png)

## CI/CD Pipeline
For this project, CI/CD is also implemented using [Github Actions](https://github.com/features/actions). Please take a look into the diagram below to see more about the CI/CD pipeline.
![CI/CD Diagram](https://github.com/LN-Django/boilerplate/blob/main/docs/CI_CD_KBE.drawio.png?raw=true)
