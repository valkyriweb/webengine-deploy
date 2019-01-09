# WebEngine Deploy

A collection of deployment files for Web Engine

Running Postgres in docker container, alongside a pgadmin container which has access to the postgres container.
Add postgres server to pgadmin to use the gui in the browser.

DB and PGadmin data is persistent and stored in data folder.

Quickstart
----------

1. CD into ../webengine-deploy/
2. Run the command ``` docker-compose up -d ```
3. Login to PGadmin via ``` http://localhost:5050 ```
4. username: ``` luke@valkyriweb.com ```
5. password: ``` admin ```
6. Click add new server on the landing page.
7. give a name for the server.
8. click the connection tab, the host is db, default ```username: postgres ```, default ``` password: postgres```.
9. ``` port: 5432 ```