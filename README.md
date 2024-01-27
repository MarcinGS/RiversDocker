# RiversDocker

> To run application locally, you must have installed [Docker](https://www.docker.com/) software.

> Aby uruchomić aplikacje lokalnie należy posiadać zainstalowane oprogramowanie [Docker](https://www.docker.com/).

<br>

## Launching the application (EN)
In the console from the path of the **RLM** folder, run the command `docker compose up -d`.

<br>

## Uruchomienie aplikacji (PL)
W konsoli z poziomu dostarczonego folderu **RLM** należy wykonać polecenie
`docker compose up -d`.

<br>

![pliki folder](https://github.com/MarcinGS/RiversDocker/assets/48533024/3331b614-533b-4599-95a8-d9899d053c52)

![konsola](https://github.com/MarcinGS/RiversDocker/assets/48533024/678a18ed-494a-4f38-b146-f8394bdea90b)

>(EN) ⚠️ Typically, the database container takes longer to start up than the rest of the components.
Therefore, it is recommended to wait about 30 seconds after startup for the application to fully initialize.
The other layers are configured to restart on failure, so there is no need to restart them manually.

---

>(PL) ⚠️ Zazwyczaj uruchomienie kontenera z bazą danych trwa dłużej niż reszty składowych.
Dlatego zaleca się odczekanie około 30 sekund od uruchomienia na pełną inicjalizację aplikacji.
Pozostałe warstwy skonfigurowane są na ponowne uruchamianie się w przypadku niepowodzenia, więc nie ma potrzeby ręcznego ich restartowania.

![docker uruch](https://github.com/MarcinGS/RiversDocker/assets/48533024/6141c80b-6953-4488-aa84-57ad86e89b56)

(EN) ➡️ Once all the containers are up and running, the application will be available in the browser at `http://localhost`.

(PL) ➡️ Po uruchomieniu się wszystkich kontenerów aplikacja dostępna będzie w przeglądarce pod adresem `http://localhost`.
