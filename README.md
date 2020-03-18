<h2>Setup dockerowy na nasz serwer</h2>

<h3>Zawiera:</h3>
<br />Postgres ✔
<br />Pgadmin ✔
<br />Tomcat ✖
<br />Jenkins ✖
<br /><br />
<h3>Zmienne środowiskowe:</h3>
<br />POSTGRES_USER
<br />POSTGRES_PASSWORD
<br />PGADMIN_DEFAULT_EMAIL
<br />PGADMIN_DEFAULT_PASSWORD
<br />PGADMIN_PORT
<br /><br />
<h3>Uruchamianie:</h3>
<br />docker-compose up -d <-detached mode
<br />docker-compse up
<br /><br />
<h3>informacje dodatkowe</h3>
<br />Baza danych postgresa dziala na porcie 5432
<br />pgadmin działa na porcie 5050
<br />
<br />Postgres dane do logowania:
<br />postgres:postgres
<br />
<br />Pgadmin dane do logowania:
<br />pgadmin@pgadmin.org:admin
