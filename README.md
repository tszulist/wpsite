# Środowisko do tworzenia stron (Wordpress + MySQL + Docker)
## Instalacja Dockera
* [Windows](https://docs.docker.com/docker-for-windows/install/)
* [Linux](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
## Pobranie skryptu dla docker-compose
```
git clone https://github.com/tszulist/wpsite.git
```
## Utworzenie środowiska
W katalogu `wpsite` należy wykonać poniższe polecenie
```
docker-compose up
```
Pobrane zostaną gotowe obrazy oraz uruchomione kontenery zawierające kompletne środowisko uruchomieniowe Wordpress'a. Katalog `/var/www/html` z kontenera z Wordpress'em zostanie zmapowany do katalogu bieżącego na komputerze host'a. Ułatwi to edycję plików źródłowych strony przy użyciu edytora z funkcją zdalnej edycji plików (np. [Visual Studio Code](https://code.visualstudio.com/download) + plugin Remote Explorer)
## Pierwsze uruchomienie
W przeglądarce należy otworzyć stronę `http://<hostname-albo-adres-ip-servera>:8080` oraz dokończyć instalację Wordpress'a.
