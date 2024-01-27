# RiversDocker
> To run application locally, you must have installed [Docker](https://www.docker.com/) software.

> Aby uruchomić aplikacje lokalnie należy posiadać zainstalowane oprogramowanie [Docker](https://www.docker.com/).
## Uruchomienie aplikacji
 W konsoli z poziomu dostarczonego folderu **RLM** należy wykonać polecenie
`docker compose up -d`.

![pliki folder](https://github.com/MarcinGS/RiversDocker/assets/48533024/3331b614-533b-4599-95a8-d9899d053c52)

![konsola](https://github.com/MarcinGS/RiversDocker/assets/48533024/678a18ed-494a-4f38-b146-f8394bdea90b)

Zazwyczaj uruchomienie kontenera z bazą danych trwa dłużej niż reszty składowych.
Dlatego zaleca się odczekanie około 30 sekund od uruchomienia na pełną inicjalizację aplikacji.
Pozostałe warstwy skonfigurowane są na ponowne uruchamianie się w przypadku niepowodzenia, więc nie ma potrzeby ręcznego ich restartowania.

![docker uruch](https://github.com/MarcinGS/RiversDocker/assets/48533024/6141c80b-6953-4488-aa84-57ad86e89b56)

Po uruchomieniu się wszystkich kontenerów aplikacja dostępna będzie w przeglądarce pod adresem `http://localhost`.
