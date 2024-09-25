# DVG Blog

Blog feito com Django, Vue e GraphQL seguindo as instruções [deste artigo no Real Python](https://realpython.com/python-django-blog) para exercitar a construção de aplicações WEB divididas em front e back-end.

## Versão do Python

3.12.4.

## Execução

1. Escolha uma pasta no seu compudtador e faça um clone deste repositório:

```git clone git@github.com:aldeoliveira/dvg-blog-api.git .```

2. Instale as dependências:

```pip install requirements.txt```

3. Faça as migrações:

```python manage.py migrate```

4. Inicie o servidor:

```python manage.py runserver```

Seguindo esses procedimentos, a API deverá ficar disponível em ```http://localhost:8000```.

## Uso

Caso seja seu primeiro acesso, crie um superusuário com o comando

```python manage.py createsuperuser```

Insira, edite ou apague posts, usuários e tags no blog usando o Django Admin, no ```http://localhost:8000/admin```. Sugerimos criar algumas instâncias desses elementos antes de fazer uso do front-end.

## Front-End

O front-end da aplicação está disponível [neste outro respositório](https://github.com/aldeoliveira/dvg-blog-front).

*__Bom proveito!__*
