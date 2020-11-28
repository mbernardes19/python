# Um pra você, um pra mim

Dado um nome, retorne uma string ccom a mensagem:

```text
Um pra X, um pra mim.
```

Onde X é um nome dado.

Contudo, se não tiver nome, retorne a string:

```text
Um pra você, um pra mim.
```

Alguns exemplos:

|Nome    |String pra retornar
|:-------|:------------------
|Alice   |Um pra Alice, um pra mim.
|Bob     |Um pra Bob, um pra mim.
|        |Um pra você, um pra mim.
|Zaphod  |Um pra Zaphod, um pra mim.

## Mensagens de Exceção

Às vezes pode ser necessário levantar uma exceção. Quando você fizer isso, inclua uma mensagem de erro explicativa para indicar qual é a causa do erro. Isso faz o seu código ficar mais legível e ajuda muito na hora de debugar. Nem todos os exercícios vão exigir que você levante uma exceção, mas para aqueles que precise, os testes só vão passar se você incluir uma mensagem.

Para levantar uma mensagem com uma exceção, escreva-a como um argumento para o tipo de exceção. Por exemplo, ao invés de `raise Exception`, você deve escrever:

```python
raise Exception("Mensagem explicativa que indica a causa do erro")
```

## Rodando os testes

Para rodar os testes, execute `pytest two_fer_test.py`

Você também pode executer o pytest module: `python -m pytest two_fer_test.py`

### Opções comuns de `pytest`

- `-v` : habilitar output verboso
- `-x` : parar de rodar testes depois da primeira falha
- `--ff` : rodar falhas do teste anterior antes de rodar outro teste

Para outras opções, veja `python -m pytest -h`

## Enviando Exercícios

Quando for tentar enviar um exercício, tenha certeza de que a solução está no diretório `$EXERCISM_WORKSPACE/python/two-fer`.

Você pode saber qual é o seu workspace do Exercism rodando `exercism debug` e olhando para a linha que começa com `Workspace`.

Para informações mais detalhadas sobre como rodar os testes, o code style e linting, por favor veja [Rodando os Testes](http://exercism.io/tracks/python/tests).

## Fonte

[https://github.com/exercism/problem-specifications/issues/757](https://github.com/exercism/problem-specifications/issues/757)

## Enviando Soluções Incompletas

É possível enviar uma solução incompleta para que você possa ver como os outros fizeram o exercício.
