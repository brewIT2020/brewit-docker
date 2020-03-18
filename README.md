<h2>Setup dockerowy na nasz serwer</h2>

<h3>Zawiera:<h3>
Postgres ✔
Pgadmin ✔
Tomcat ✖
Jenkins ✖

<h3>Zmienne środowiskowe:<h3>
POSTGRES_USER
POSTGRES_PASSWORD
PGADMIN_DEFAULT_EMAIL
PGADMIN_DEFAULT_PASSWORD
PGADMIN_PORT

<h3>Uruchamianie:<h3>
docker-compose up -d <-detached mode
docker-compse up

<h3>informacje dodatkowe<h3>
Baza danych postgresa dziala na porcie 5432
pgadmin działa na porcie 5050

Postgres dane do logowania:
postgres:postgres

Pgadmin dane do logowania:
pgadmin@pgadmin.org:admin
