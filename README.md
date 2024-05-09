# DJANGO AGENDA

## Iniciar o projeto Django

Crie o ambiente virtual para começar o seu projeto isso te ajudará no futuro acredite.
```
python -m venv venv
. venv/bin/activate
pip install django
django-admin startproject project .
python manage.py startapp contact
```
---
## CONFIGURANDO O GIT
```
git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
```
---
## ASSOCIANDO O GIT AO GITHUB

Selecione a pasta do projeto para executar os comandos asseguir.
```
git init
git add .
git commit -m 'Mensagem'
git remote add origin URL_DO_GIT
```
---
## Migrando a base de dados do Django
```
python manage.py makemigrations
python manage.py migrate
```
---
## Criando e modificando a senha de um super usuário Django
python manage.py createsuperuser
python manage.py changepassword USERNAME