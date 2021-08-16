# my-python-install
Meu go-to install de bibliotecas do python.


## Necessário ter Python instalado ou instalar o python.

Atualizando python:

```
choco upgrade python -y
```

Alternativamente com winget:

```
winget install -e --id Python.Python
```

ou caso seja linux:

```
sudo apt update -y
sudo apt install python
```

## Installar as bibliotecas:

```
pip install -r requirements.txt
```

ou apenas umas bibliotecas com:

```
pip install -r requirements-lite.txt
```