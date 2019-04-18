# Django Rest Framework Tutorial

Curso: https://teamtreehouse.com/library/django-rest-framework

## Requisitos
* Python 3+ (de preferência o 3.6.8)
* PostgreSQL 11

## Como desenvolver?

* Clone o repositório;
* Crie um virtualenv com Python 3.6.8;
* Ative o virtualenv;
* Instale as dependências do ambiente de desenvolvimento;
* Crie um banco de dados PostgreSQL.


```
git clone https://github.com/marcellobenigno/drf_tutorial.git
cd drf_tutorial
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
createdb drf_turorial
```

* Renomeie o arquivo `env-sample` para `.env`:

```
mv contrib/env-sample .env
```

* Preencha as informações do `.env` e rode os seguintes comandos:

```
python manage.py makemigrations
python manage.py migrate
```