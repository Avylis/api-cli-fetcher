# api-cli-fetcher

##opis projektu
Aplikacja CLI która pobiera dane z API i zapijue je jako plik JSON
##Instrukcje instalacji i jak uruchomić aplikacje

##Jak Zainstalować i się ptzgotować
1. Sklonuj repozytorium:

```bash
git clone https://github.com/Avylis/api-cli-fetcher.git
cd api-cli-fetcher
```
2.Zainstaluj wymagane biblioteki

```bash
pip install -r requirements.txt
```

## uruchomienie aplikacji
### Przykłady komend

```bash
# Pobranie danych z API
python cli_fetcher.py --fetch --url https://github.com/Avylis/api-cli-fetcher

# Zapis do innego pliku
python cli_fetcher.py --fetch --url https://github.com/Avylis/api-cli-fetcher --output dane.json
```

##Jak rozszerzeyć aplikacje
- Umożliw różne formaty danych (np. CSV, XML) poprzez dodatkowe flagi CLI
