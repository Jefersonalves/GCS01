# Django Basico

## Ambiente de Dev

O ambiente de dev utiliza o sistema operacional Ubuntu Trusty 64.

```
sudo apt-get install python-pip
sudo pip install django flake8
```

Após ter tudo instalado, prepare o ambiente rodando:

```
python manage.py migrate
```

Para rodar os testes:

```
python manage.py test
flake8 --exclude polls/migrations/,manage.py  .
```

### Acesso

Para rodar o projeto:

```
python manage.py runserver 0:8000
```

O acesso deve ser feito através do `localhost:8000`.


