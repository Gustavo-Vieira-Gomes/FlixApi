# FlixAPI

Api REST criada para gerenciamento de filmes, atores e avaliações de filmes. Projeto desenvolvido durante o curso Django Master.

## Funções
- CRUD de Atores
- CRUD de gêneros de filmes
- CRUD de filmes
- CRUD de avaliações
- Cálculo de informações baseadas nas avaliações

## Tecnologias utilizadas
Projeto desenvolvido utilizando apenas **PYTHON** e as seguintes bibliotecas:
- Django
- Django Rest Framework


## Como Rodar o projeto?

Com o ambiente virtual ativado, instale as dependências do projeto usando o comando:

```
pip install -r requirements.txt
```

Após instalar as dependências, aplique as migrations no banco de dados com o comando:

```
python manage.py migrate
```

Agora o projeto jã pode ser inicializado com o comando:

```
python manage.py runserver
```
Após isso, o sistema estará pronto para ser acessado em: http://localhost:8000