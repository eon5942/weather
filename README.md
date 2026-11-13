# weather
barely functioning weather checker made in python as a cli app for la time made with open-mateo
-----------------------------------------------------------------------------------------------
install with (in home dir);
```sh

git clone https://github.com/eon5942/weather/
python3 -m venv .venv && .venv/bin/pip install openmeteo-requests
```
in shell config;
```sh
alias weather="python3 ~/weather.py"
```
to use celcius:
```sh
weather -c
```
