---
layout  : post
person  : Dojo 08/05/2014
summary : Dojo dos Assassinos
---

## Qual foi o problema proposto?

[Descubra o assassino](http://dojopuzzles.com/problemas/exibe/descubra-o-assassino/ "DojoPuzzles")

Resumo do problema: 

O empresário Bill G. Ates foi assassinado e o corpo dele foi deixado na frente da delegacia de polícia. O detetive Lin Ust Orvalds foi escolhido para investigar este caso. Após uma série de investigações, ele organizou uma lista com prováveis assassinos, os locais do crime e quais armas poderiam ter sido utilizadas.

**Suspeitos:**

 - Charles B. Abbage
 - Donald Duck Knuth
 - Ada L. Ovelace
 - Alan T. Uring
 - Ivar J. Acobson
 - Ras Mus Ler Dorf

**Locais:**

 - Redmond
 - Palo Alto
 - San Francisco
 - Tokio
 - Restaurante no Fim do Universo
 - São Paulo
 - Cupertino
 - Helsinki
 - Maida Vale
 - Toronto

**Armas:**

 - Peixeira
 - DynaTAC 8000X (o primeiro aparelho celular do mundo)
 - Trezoitão
 - Trebuchet
 - Maça
 - Gládio

Uma testemunha foi encontrada, mas ela só consegue responder se Lin fornecer uma teoria. Para cada teoria ele "chuta" um assassino, um local e uma arma. A testemunha então responde com um número. Se a teoria estiver correta (assassino, local e arma corretos), ela responde 0. Se a teoria está errada, um valor 1,2 ou 3 é retornado. 1 indica que o assassiona está incorreto; 2 indica que o local está incorreto; 3 indica que a arma está incorreta. Se mais de uma suposição está incorreta, ela retorna um valor arbitrário entre as que estão incorretos (isso é totalmente aleatório).

Por exemplo, se o assassino for Donald Duck Knuth usando um trezoitão em Tokio:

Teoria: 1, 1, 1

Retorno: 1, ou 2, ou 3 (todos estão incorretos) 

Teoria: 3, 1, 3

Retorno: 1, ou 3 (somente o local está correto)

Teoria: 5, 3, 4

Retorno: 1 (somente o assassino está incorreto)

Teoria: 2, 3, 4

Retorno: 0 (todos corretos, você solucionou o caso)

Você precisa desenvolver um programa que tente resolver o problema. Inicialmente não se preocupe no número de tentativas necessário para encontrar a solução. Depois tente melhorar a maneira com que as teorias são testadas para que Lin encontre a solução do problema no menor número de tentativas.

##Qual a situação da solução no final do dojo?

[Tava indo bem, mas ficou uma bagunça!](https://github.com/dojo-se/descubra-o-assasino). Sinta-se à vontade para contribuir com a solução!

Quer mexer no código? É bem fácil, só clicar no botão Hack abaixo!

[![Hack dojo-se/descubra-o-assasino on Nitrous.IO](https://d3o0mnbgv6k92a.cloudfront.net/assets/hack-l-v1-3cc067e71372f6045e1949af9d96095b.png)](https://www.nitrous.io/hack_button?source=embed&runtime=django&repo=dojo-se%2Fdescubra-o-assasino&file_to_open=README.md)

PS: Usamos a [Raspberry Pi WebIDE da Adafruit](https://learn.adafruit.com/webide/overview) e esquecemos de mudar o comportamento do repositório. Resultado: trocentos commits!

###Retrospectiva

##Prós

 - Usamos o Raspberry Pi e foi show de bola!
 - A presença da galera foi bacana.
 - A data marcada sem enrolação.
 - Ambiente descontraído! Antes de começar rolou um bom papo com experiências de desenvolvimento (ou não) relevantes.

##Contras

 - Demorou para começar, muito chat!
 - Dificuldade para encontrar problemas diversos.
 - Perdido no TDD/Baby steps: a aleatoriedade do problema confundiu!
 - Falta um Sensei Mestre Splinter mais durão para reforçar o Kata.
 - Conversas paralelas.
 - Na próxima: dividir em grupos!
 - Inteligência artificial em RANDOM!

## Links úteis

 - [Evento no Facebook](https://www.facebook.com/events/696663497067465/)
 - [Evento no Google+](https://plus.google.com/u/0/b/117712497785310292400/events/cq16hdnstsblmtikqdverjf8je0?authkey=CLWdgpmut_aWZQ)
 - [Fotos no Flickr](http://www.flickr.com/photos/erickmendonca/sets/72157641953730615/)
