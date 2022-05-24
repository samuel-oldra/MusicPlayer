# Aplicação usando Python e Django 4

## NutriLab - PyStack Week 4.0

Aplicação para nutricionistas e pacientes.

Desenvolvida uma aplicação completa para nutricionistas gerenciarem seus pacientes.

## Tecnologias e práticas utilizadas
- Python
- Django 4
- SQLite
- Arquitetura MVT

## Funcionalidade
- Autenticação e Cadastro de Usuário

###

[imagens]

## Comandos

### pip
```
pip list --outdate
python -m pip install --upgrade pip
python -m pip install --upgrade setuptools
```

### virtualenv (windows)
```
python -m venv env
env\Scripts\activate.bat
env\Scripts\deactivate.bat
```

### Instalar bibliotecas, gravar/instalar requerimentos
```
(env) pip install Django
(env) pip install Pillow

(env) pip freeze > requirements.txt
(env) pip install -r requirements.txt
```

### Criar projeto
```
(env) django-admin startproject nutrilab .
```

### Criar apps
```
(env) python manage.py startapp autenticacao
```

### Migrations
```
(env) python manage.py makemigrations
(env) python manage.py migrate
```

### Executar projeto
```
(env) python manage.py runserver
```
