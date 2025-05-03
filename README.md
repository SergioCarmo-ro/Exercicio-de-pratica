# Nome do Projeto

![NPM Version](https://img.shields.io/npm/v/npm)

> Descrição curta do seu projeto. Explique em uma linha o que ele faz ou resolve.

## 🐍 Tecnologias e Ferramentas

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

- **Python 3.10+**
- **FastAPI** – framework para construção de APIs modernas
- **Uvicorn** – servidor ASGI leve e rápido
- **SQLAlchemy** – ORM para banco de dados relacional
- **Pydantic** – validação de dados com tipagem
- **Alembic** – controle de versionamento do banco de dados
- **PostgreSQL** – banco de dados relacional (ou SQLite para testes)
- **Docker** – conteinerização da aplicação
- **Pytest** – testes automatizados

## 🚀 Como rodar o projeto

### Pré-requisitos

- Python instalado (recomenda-se uso de virtualenv ou Poetry)
- Docker (opcional, para rodar em container)

### Passos

```bash
# Crie e ative o ambiente virtual
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows

# Instale as dependências
pip install -r requirements.txt

# Inicie o servidor
uvicorn app.main:app --reload
