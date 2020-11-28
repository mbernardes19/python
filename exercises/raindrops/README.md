# Gotas de chuva

Sua tarefa é converter um número em uma string que contenha sons de gotas de chuva de acordo com sua divisbilidade. Um número é divisível por outro quando na divisão não sobre resto. A forma mais simples de testar se um número é divisível por outro, é usando a [operação módulo](https://pt.wikipedia.org/wiki/Opera%C3%A7%C3%A3o_m%C3%B3dulo).

As regras de `gotas de chuva` são que se um número:

- for divisível por 3, adicione 'Pling' ao resultado.
- for divisível por 5, adicione 'Plang' ao resultado.
- for divisível por 7, adicione 'Plong' ao resultado.
- _não for_ divisível por 3, 5 nem 7, o resultado será os dígitos do número.

## Exemplos

- 28 é divisível por 7, mas não por 3 ou 5, então o resultado será "Plong".
- 30 é divisível por 3 e por 5, mas não por 7, então o resultado será "PlingPlang".
- 34 não é divisível por 3, por 5 e nem por 7, então o resultado será "34".

## Mensagens de Exceção

Às vezes pode ser necessário levantar uma exceção. Quando você fizer isso, inclua uma mensagem de erro explicativa para indicar qual é a causa do erro. Isso faz o seu código ficar mais legível e ajuda muito na hora de debugar. Nem todos os exercícios vão exigir que você levante uma exceção, mas para aqueles que precise, os testes só vão passar se você incluir uma mensagem.

Para levantar uma mensagem com uma exceção, escreva-a como um argumento para o tipo de exceção. Por exemplo, ao invés de `raise Exception`, você deve escrever:

```python
raise Exception("Mensagem explicativa que indica a causa do erro")
```

## Rodando os testes

Para rodar os testes, execute `pytest two_fer_test.py`

Você também pode executer o pytest module: `python -m pytest raindrops_test.py`

### Opções comuns de `pytest`

- `-v` : habilitar output verboso
- `-x` : parar de rodar testes depois da primeira falha
- `--ff` : rodar falhas do teste anterior antes de rodar outro teste

Para outras opções, veja `python -m pytest -h`

## Enviando Exercícios

Quando for tentar enviar um exercício, tenha certeza de que a solução está no diretório `$EXERCISM_WORKSPACE/python/raindrops`.

Você pode saber qual é o seu workspace do Exercism rodando `exercism debug` e olhando para a linha que começa com `Workspace`.

Para informações mais detalhadas sobre como rodar os testes, o code style e linting, por favor veja [Rodando os Testes](http://exercism.io/tracks/python/tests).

## Fonte

Uma variação de FizzBuzz, uma famosa pergunta de entrevista técnica feita para remover candidatos. A pergunta em si é derivada de FizzBuzz, um jogo de criança famoso que ensina divisão. [https://en.wikipedia.org/wiki/Fizz_buzz](https://en.wikipedia.org/wiki/Fizz_buzz)

## Enviando Soluções Incompletas

É possível enviar uma solução incompleta para que você possa ver como os outros fizeram o exercício.