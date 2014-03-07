---
layout  : post
person  : Dojo 05/03/2014
summary : Quarta de cinzas!
---

## Qual foi o problema proposto?

[Índice de Equilíbrio](http://dojopuzzles.com/problemas/exibe/indice-de-equilibrio/ "DojoPuzzles")

Resumo do problema: 

Um vetor com N números inteiros é dado. O índice de equilíbrio deste vetor é o número inteiro P (com 0 ≤ P < N) e soma dos elementos do vetor com índices inferiores é igual a soma dos elementos de índices superiores. Isto é:

A[0] + A[1] + ... + A[P−1] = A[P+1] + ... + A[N−2] + A[N−1]

Assumimos que a soma de zero elementos é igual a zero. Isso pode acontecer se P = 0 ou se P = N-1.

Por exemplo, tendo o seguinte vetor com 7 elementos:

A[0] = -7; A[1] = 1; A[2] = 5; A[3] = 2; A[4] = -4; A[5] = 3; A[6] = 0.

Então:

- P = 3 é um índice de equilíbrio deste vetor, já que A[0] + A[1] + A[2] = A[4] + A[5] + A[6]
- P = 6 também é um índice de equilíbrio deste vetor, já que A[0] + A[1] + A[2] + A[3] + A[4] + A[5] = 0 e não existem elementos com índices maiores que 6.

Escreva uma função que, dado um vetor A com índices iniciando em zero, com N número inteiros, retorna qualquer um de seus índices de equilíbrio.
A função deve retornar -1 se o índice de equilíbrio não existir.

Linguagem escolhida: C++. 

Especialista: Fernando Almeida

## Qual a situação da solução no final do dojo?

Funcionando :-)

## E cadê o código?

[Tá aqui no GitHub!](https://github.com/dojo-se/indice_equilibrio)

## Pós-dojo Virtual

Terminamos às pressas por causa do horário e ficamos sem a finalização e pós-dojo. Então lá vai um virtual.

**Positivos**

- Mais uma vez não caímos no Python (adoramos a linguagem, mas estava monopolizando já!);
- Respeitamos mais a filosofia de baby steps;
- Finalmente um dojo neste ano!

**Negativos**

- Cadê o café?;
- Apressado no final (justificado pelo horário);
- Pós-dojo que nunca acontece!;
- O ladrão não levou o monitor CRT. =/

## Links úteis

[Nossa lista de discussão](https://groups.google.com/forum/?fromgroups#!forum/dojo-se)

[Evento no Facebook](https://www.facebook.com/events/254164024757899/)

[Evento no Google+](https://plus.google.com/u/0/events/chsp5mmlclns55hu2u4u3sg7hc0)

[Fotos no Flickr](http://www.flickr.com/photos/erickmendonca/sets/72157641953730615/)