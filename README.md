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
## Desafios

São 3 desafios ao todo.

Para cada desafio, temos um arquivo no qual você desenvolverá sua solução:
- `problems/problem1.py`
- `problems/problem2.py`
- `problems/problem3.py`

A solução deve ser realizada dentro da função `solve()` que está presente do arquivo

### Desafio 1

Entrada: 
- `number`: inteiro
- `iterations`: inteiro

Implemente a seguinte lógica: 
- Se o número `number` não terminar em zero, subtraia `1` de `number`;
- Se `number` terminar em zero, divida-o por `10`.
- Faça isso enquanto `iterations` for maior que zero

Retorne o valor final de `number`, que deve ser um numero inteiro.
