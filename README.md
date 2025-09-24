Projeto API: API de Gerenciamento Escolar

**Descrição do Projeto**
Este projeto consiste em uma API RESTful desenvolvida em Python com o framework FastAPI. O objetivo é fornecer um sistema para gerenciar os dados de uma escola, permitindo operações de CRUD (Criar, Ler, Atualizar e Deletar) para as tabelas de Alunos e Endereços. A aplicação se conecta a um banco de dados MySQL para persistir os dados e utiliza bibliotecas como Pandas e SQLAlchemy para a manipulação e consulta das informações de forma eficiente. ✨

**Funcionalidades Principais**
* **Gerenciamento de Endereços:** Consultar endereços por ID ou por Estado. Cadastrar um novo endereço. Atualizar os dados de um endereço existente. Deletar um endereço.
* **Gerenciamento de Alunos:** Consultar alunos por ID ou por Nome. Cadastrar um novo aluno, associando-o a um endereço. Atualizar os dados de um aluno. Deletar um aluno.
* **Gerenciamento de Disciplinas:** Consultar disciplinas por ID ou por Semestre. Cadastrar uma nova disciplina. Atualizar os dados de uma disciplina existente. Deletar uma disciplina.
* **Segurança:** Utiliza variáveis de ambiente para proteger a senha de acesso ao banco de dados.
* **Documentação Automática:** Por ser construída com FastAPI, a API gera documentação interativa automaticamente (via Swagger UI e ReDoc).

**Tecnologias Utilizadas**
* **Python 3.10+:** Linguagem de programação principal.
* **FastAPI:** Framework web de alta performance para a construção da API.
* **SQLAlchemy:** ORM para facilitar a comunicação com o banco de dados MySQL.
* **Pandas:** Biblioteca utilizada para a manipulação dos dados retornados pelo banco.
* **python-dotenv:** Para gerenciamento de variáveis de ambiente.
* **Uvicorn:** Servidor ASGI para rodar a aplicação FastAPI.
* **MySQL:** Sistema de gerenciamento de banco de dados relacional.