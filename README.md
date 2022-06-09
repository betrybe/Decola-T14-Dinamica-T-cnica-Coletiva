# Decola T14 Dinâmica Técnica Coletiva

## Preparação do ambiente

1. **Criar o ambiente virtual**

```bash
$ python3 -m venv .venv
```

2. **Ativar o ambiente virtual**

```bash
$ source .venv/bin/activate
```

3. **Instalar as dependências no ambiente virtual**

```bash
$ python3 -m pip install -r requirements.txt
```

## Rodando os testes

Para executar todos os testes

```bash
$ python3 -m pytest
```

Para executar os testes relacionados a apenas um desafio (_para o desafio 1, por exemplo_)

```bash
$ python3 -m pytest tests/test_problem1.py
```
