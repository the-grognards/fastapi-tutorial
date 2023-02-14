# fastapi-tutorial

Tutorial FastAPI

## Criar e ativar ambiente virtual
```console
python3 -m venv .venv
source .venv/bin/activate
```

Criar arquivo para variáveis de ambiente `.env`.
```console
touch .env.example
```

## Dependências do Projeto

Criar arquivo para as dependências do projeto.
```console
touch requirements.txt
```

Coloque o conteúdo:
```txt
fastapi==0.92.0 
uvicorn[standard]==0.20.0 
```

Instalando dependências:
```console
pip install -r requirements.txt
```

## Executar projeto
```console
uvicorn main:app --reload
```