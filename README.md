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

---

## Desafios

São 3 desafios ao todo.

Para cada desafio, temos um arquivo no qual você desenvolverá sua solução:
- `problems/problem1.py`
- `problems/problem2.py`
- `problems/problem3.py`

A solução deve ser realizada dentro da função `solve()` que está presente do arquivo

### Desafio 1

**Entrada**: 
> - `number`, do tipo `int`
> - `iterations`, do tipo `int`

**Desafio**:
> Execute a seguinte lógica pelo número de vezes indicado em `iterations`:
> - Se `number` não terminar em zero, subtraia `1` de `number`. Caso contrário, divida `number` por `10`
> 
> Retorne o valor final de `number`, que deve ser um numero inteiro.

### Desafio 2

**Entrada**: 
> - `brackets`, do tipo `str`

**Desafio**:
> A entrada `brackets` será uma sequência dos caracteres:
> - `(` : abertura de parênteses;
> - `)` : fechamento de parênteses. 
> 
> Verifique se, para cada abertura de parênteses, há um fechamento correspondente. Além disso, não deve haver um fechamento sem uma abertura correspondente. 
> 
> Retorne `True` se a entrada atende as condições, e `False` caso contrário.


