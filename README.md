# Aplicação Full-stack em Django

a aplicação consiste em um pequeno website de cadastro de receitas

# Como rodar em sua máquina

- instale python(www.python.org/downloads/)
- instale postgresql(www.postgresql.org/download/)
- abra o terminal no projeto
- crie e abra um ambiente virtual
    - execute o comando: python -m venv venv
    - logo após, execute o comando(no windows): venv/scripts/activate
    - logo após, execute o comando(no linux/mac): source venv/bin/activate
- instale os pacotes com o comando: pip install -r requirements.txt
- abra o pgAdmin4
    - crie um server, dentro de "Servers", chamado "dbserver", com o Hostname/adress como "localhost"
    - dentro de dbserver, crie um database dentro de "Databases", chamado "shin_receita"
- volte ao editor de código e vá ate o arquivo settings.py dentro da pasta "shinreceita"
    - procure por "password" em "DATABASES"
    - altere para sua senha registrada no postgresql qdo realizada a instalação
- execute o comando: python manage.py migrate
- execute o comando: python manage.py runserver
- ctrl + click no link após a mensagem "Running on >link<"
- realize um cadastro
- efetue o login
- explore seu novo livro de receitas

# Aprendizados

- desenvolvimento de aplicações web utilizando a linguagem Python
- configuração e conexão de uma aplicação com um banco de dados sql(Postgresql)
- melhoramento de código, reaproveitando em outras partes da aplicação
- compreensão da arquitetura de uma aplicação feita com Django
- filtros e listas
- criação e integração de modelos
- admin com Django admin
- página de busca com páginação
- sistema de autenticação de usuários não vinculado ao Django admin
- formulários no Django
- requisições protegidas, evitando falsificação de requisições
- aprimoramento de experiência dos usuários, mensagens de sucesso e de erro
- CRUD em Django
