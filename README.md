# Django Rest To Do

##### Projeto em desenvolvimento
Django Rest ToDo: Utilizando o básico do Django Rest Framework para criar uma API simples de tasks, a qual será consumida com ReactJS.

### Api End Points:
Lista de todos os end-points:
- http://localhost:8000/api/

Listar todas as minhas tasks
- http://localhost:8000/api/task-list/

Detalhes de uma task(GET)
- http://localhost:8000/api/task-detail/<str:pk>/

Criar uma task(POST)
- http://localhost:8000/api/task-create/

Atualizar uma task(POST)
- http://localhost:8000/api/<str:pk>/

Deletar uma task(DELETE)
- http://localhost:8000/api/<str:pk>/

### Instalando em ambiente local

Criar um ambiente virtual: 
- python3 -m venv nomeDoAmbiente
- . nomeDoAmbiente/bin/activate
- Para desativar so digitar deactivate no terminal

Instalar os requerimentos do sistema
- pip install -r requirements-dev.txt

Rodar o sistema
- No terminal utilize o comando python manage.py runserver
- **Em alguns casos é necessario utilizar python3 manage.py runserver ou python2 manage.py runserver**

### packages:
- [Django Rest Framework Docs](https://www.django-rest-framework.org/)
- [Python Decouple](https://github.com/henriquebastos/python-decouple)