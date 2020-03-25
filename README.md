<h2>Setup dockerowy na nasz serwer</h2>
<h3>Zawiera:</h3>
<h4>Docker-composa z cała architektura aplikacji<h4>
Postgres ✔
<br />Nginx ✔
<br />Pgadmin ✔
<br />Tomcat ✔
<br /><br />
<h3>Zmienne środowiskowe:</h3>
POSTGRES_USER
<br />POSTGRES_PASSWORD
<br />PGADMIN_DEFAULT_EMAIL
<br />PGADMIN_DEFAULT_PASSWORD
<br />PGADMIN_PORT
<br /><br />
<h3>Uruchamianie:</h3>
docker-compose up -d <-detached mode
<br />docker-compse up
<br /><br />
<h3>informacje dodatkowe</h3>
Baza danych postgresa dziala na porcie 5432
<br />pgadmin działa na porcie 5050
<br />tomcat działa na porcie 8080
<br />
<br />Postgres dane do logowania:
<br />postgres:postgres
<br />
<br />Pgadmin dane do logowania:
<br />pgadmin@pgadmin.org:admin
<br />
<br />
<h4>Docker-composa z Jenkinsem:</h4>
<br />WIP: Przydałby się setup z niezbędnymi pluginami
<br />Działa na porcie 8080
<br />logowania:
<br />admin:losowo_generowany_w_dockerze_jenkinsa
