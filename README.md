

This repository contains a Docker Compose file that sets up a development environment for Strapi, an open-source headless CMS. 

The environment includes a Strapi v4 container with a PostgreSQL database backend. 

The Strapi container is configured to listen on port `1337`, and the PostgreSQL container is configured to expose port `5432`. 

The database is persisted across container restarts using a named volume called data. 

The Strapi app files are also persisted using another named volume called app. 

Simply run `docker-compose up` to start the containers and access the Strapi admin panel at http://localhost:1337/admin.