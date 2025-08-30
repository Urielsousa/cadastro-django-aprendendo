# Projeto de cadastro de ususarios 
O projeto é uma aplicação web desenvolvida em Dajango para cadastro de listagem de usuários  
Projeto criado para fins de aprendizado com Django.

#funcionalidades 
- Cadastro de usuários (nome e idade)
- Listagem dos ususários cadastrados

# como rodar o projeto 
 
1 instale as dependencias do Django 
pip install django 

2 Use o comando ls no terminal para saber em qual pasta você está

3 navegue até a pasta do projeto (onde esta o arquivo manage.py)
cd projeto_cad_ usuario 

4 execute o servidor de desenvolvimento: 
python ./manage.py runserver 

5 acesse 'http://127.0.0.1:8000/' no navegador

# Arquivos principais do projeto
- 'models.py' : Define o modelo de 'Usuario'.
- 'views.py': Lógica para o cadastro e listagem de usuários.
- 'home.html': Pagina de cadastro.
- 'usuarios.html': Pagina de Listagem.
- 'url.py': Rotas do projeto.
  
# Obs: 
- O banco de dados utilizado é o SQLITE (padrão do Django).
- Para cadastrar um usuário, preencha o formulário na pagina inicial e envie. 
- Os usuários cadastrados aparecem na pagina de listagem.
