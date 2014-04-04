---
layout  : post
person  : Dojo 03/04/2014
summary : Pokerface!
---

Agora o Coding Dojo é toda primeira quinta do mês. Reserve o espaço na sua agenda :-)

## Qual foi o problema proposto?

[Poker](http://dojopuzzles.com/problemas/exibe/poker/ "DojoPuzzles")

Resumo do problema: 

No jogo de Poker, uma mão consiste em cinco cartas que podem ser comparadas, da mais baixa para a mais alta, da seguinte maneira:

- Carta Alta: A carta de maior valor.
- Um Par: Duas cartas do mesmo valor.
- Dois Pares: Dois pares diferentes.
- Trinca: Três cartas do mesmo valor e duas de valores diferentes.
- Straight (seqüência): Todas as carta com valores consecutivos.
- Flush: Todas as cartas do mesmo naipe.
- Full House: Um trinca e um par.
- Quadra: Quatro cartas do mesmo valor.
- Straight Flush: Todas as cartas são consecutivas e do mesmo naipe.
- Royal Flush: A seqüência 10, Valete, Dama, Rei, Ás, do mesmo naipe.

![Exemplos](/images/2014-04-03-coding_dojo_2.png "Exemplos de mãos")

As cartas são, em ordem crescente de valor: 2, 3, 4, 5, 6, 7, 8, 9, 10, Valete, Dama, Rei, Ás.

Os naipes são: Ouro (D), Copa (H), Espadas (S), Paus (C)
Se dois jogadores possuem a mesma mão, vence que tiver a mão formada pelas cartas de maior valor.

Alguns exemplos de mão e seus respectivos vencedores:

| Jogador 1 | Jogador 2 | Vencedor |
|------------|-----------|-----------|
|5H 5C 6S 7S KD (Par de cinco) | 2C 3S 8S 8D TD (Par de oito) | Jogador 2|
|5D 8C 9S JS AC (Carta mais alta: Ás) | 2C 5C 7D 8S QH (Carta mais alta: Dama) | Jogador 1|
|2D 9C AS AH AC (Trinca de Ás) | 3D 6D 7D TD QD (Flush com Ouro)| Jogador 2|
|4D 6S 9H QH QC (Par de Damas , Carta mais alta: 9) | 3D 6D 7H QD QS (Par de Damas, Carta mais alta: 7) | Jogador 1|
|2H 2D 4C 4D 4S (Full House com três 4) | 3C 3D 3S 9S 9D (Full House com três 3) | Jogador 1|


Desenvolva um programa que, de acordo com as mãos de dois jogadores, informe qual deles é o vencedor.

Linguagem escolhida: Python. 

Especialista: Wagner Macedo.

## Qual a situação da solução no final do dojo?

[Faltam muitas regras a serem implementadas](https://github.com/dojo-se/poker/issues/1). Sinta-se à vontade para contribuir com a solução!

## E cadê o código?

[Tá aqui no GitHub!](https://github.com/dojo-se/poker)

## Pós-dojo

Finalmente tivemos um pós-dojo! Esperamos que continuemos a ter nas próximas vezes.

**Positivos**

- Novatos!
- Mais gente!
- Ambiente descontraído.
- Problema interessante.
- Café.
- Pós-dojo!

**Negativos**

- Baby steps e TDD negligenciados.
- Todos eram co-pilotos. Pitacos everywhere!


## Links úteis

[Evento no Facebook](https://www.facebook.com/events/649326105103737/)

[Evento no Google+](https://plus.google.com/events/cp070id92gf7gj1ap9carns8umc?authkey=CLa2leWxx8vxsQE)

[Fotos no Flickr](http://www.flickr.com/photos/erickmendonca/sets/72157641953730615/)