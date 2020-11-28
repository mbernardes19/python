# Pontuações

Administre a lista de pontuações de um jogador de um jogo.

Sua tarefa é fazer um componente de pontuações do jogo clássico Frogger, um dos mais vendidos e viciantes jogos de todos os tempos, e um clássico da era dos fliperamas. Sua tarefa é escrever métodos que retornem a pontuação mais alta da lista, a última pontuação adicionada e as três pontuações mais altas.

Neste exercício, você vai ter que usar e manipular listas. Listas em Python são muito versáteis, e você vai usá-las muito em problemas tanto simples quanto complexos.

- [**Estrutura de Dados (Python 3 Documentation Tutorial)**](https://docs.python.org/3/tutorial/datastructures.html)
- [**Lista e Tuplas em Python (Real Python)**](https://realpython.com/python-lists-tuples/)
- [**Listas em Python (Google for Education)**](https://developers.google.com/edu/python/lists)

## Mensagens de Exceção

Às vezes pode ser necessário levantar uma exceção. Quando você fizer isso, inclua uma mensagem de erro explicativa para indicar qual é a causa do erro. Isso faz o seu código ficar mais legível e ajuda muito na hora de debugar. Nem todos os exercícios vão exigir que você levante uma exceção, mas para aqueles que precise, os testes só vão passar se você incluir uma mensagem.

Para levantar uma mensagem com uma exceção, escreva-a como um argumento para o tipo de exceção. Por exemplo, ao invés de `raise Exception`, você deve escrever:

```python
raise Exception("Mensagem explicativa que indica a causa do erro")
```

## Rodando os testes

Para rodar os testes, execute `pytest high_scores_test.py`

Você também pode executer o pytest module: `python -m pytest high_scores_test.py`

### Opções comuns de `pytest`

- `-v` : habilitar output verboso
- `-x` : parar de rodar testes depois da primeira falha
- `--ff` : rodar falhas do teste anterior antes de rodar outro teste

Para outras opções, veja `python -m pytest -h`

## Enviando Exercícios

Quando for tentar enviar um exercício, tenha certeza de que a solução está no diretório `$EXERCISM_WORKSPACE/python/high-scores`.

Você pode saber qual é o seu workspace do Exercism rodando `exercism debug` e olhando para a linha que começa com `Workspace`.

Para informações mais detalhadas sobre como rodar os testes, o code style e linting, por favor veja [Rodando os Testes](http://exercism.io/tracks/python/tests).

## Fonte

Tributo ao jogo de arcade dos anos 80 Frogger

## Enviando Soluções Incompletas

É possível enviar uma solução incompleta para que você possa ver como os outros fizeram o exercício.