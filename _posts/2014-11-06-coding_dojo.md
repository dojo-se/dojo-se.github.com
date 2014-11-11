---
layout  : post
person  : Dojo 06/11/2014
summary : GDG Dojo Novembro/2014
---

##Qual foi o problema proposto?

[Nuvem de Cinzas](http://dojopuzzles.com/problemas/exibe/nuvem-de-cinzas/)

##Resumo do problema:

Um vulcão acaba de entrar em erupção, provocando uma nuvem de cinzas que se alastra impedindo a circulação aérea. O governo está muito preocupado e deseja saber quando que a nuvem de cinzas irá atingir todos os aeroportos do país.

Está disponível um mapa detalhando a situação atual. O mapa é retangular, dividido em pequenos quadrados. Neste mapa existem três tipos de quadrados: nuvem (indicando que esta região do mapa já está coberto por nuvens), aeroportos (indicando a localização de um aeroporto) e todas as outras (indicando locais onde a nuvem ainda não chegou).

A cada dia, a nuvem expande-se um quadrado na horizontal e um quadrado na vertical. Ou seja, ao fim de cada dia, todos os quadrados adjacentes (vertical ou horizontalmente) a uma nuvem, também passam a conter nuvens. Por exemplo:

	. . * . . . * *      . * * * . * * *     * * * * * * * *
	. * * . . . . .      * * * * . . * *     * * * * * * * *
	* * * . A . . A      * * * * A . . A     * * * * * . * *
	. * . . . . . .  ->  * * * . . . . .  -> * * * * . . . .
	. * . . . . A .      * * * . . . A .     * * * * . . A .
	. . . A . . . .      . * . A . . . .     * * * A . . . .
	. . . . . . . .      . . . . . . . .     . * . . . . . .
     	  Dia 1                Dia 2               Dia 3

Para preparar os planos de contingência, o governo necessita saber: quantos dias demorará para ao menos um aeroporto ficar coberto pelas nuvens e daqui quantos dias todos os aeroportos estarão cobertos pelas nuvens.

Dados um quadriculado com L linhas e C colunas, além da indicação inicial das nuvens e dos aeroportos, desenvolva uma programa que informe o número de dias até um primeiro aeroporto ficar debaixo da nuvem de cinzas e o número de dias até que todos os aeroportos ficarem cobertos pelas cinzas.

##Qual a situação da solução no final do dojo?

[Quase nada!](https://github.com/dojo-se/nuvem_de_cinza)

Tivemos alguns problemas com o JavaScript. Mas graças ao [lecneri](https://github.com/lecneri), agora temos o código funcional :-)

Quer mexer no código? É bem fácil, só clicar em Fork e brincar!

## Não sabe o que é um Coding Dojo?

É uma reunião de desenvolvedores para trocar ideias e resolver, juntos, um problema. Não precisa ser expert nem manjar de todos os paranauês, basta ter interesse!

## Links úteis

[Evento no Google+](https://plus.google.com/events/coaavldhodanv3iu6u4lpu71jqc)

[Evento no Facebook](https://www.facebook.com/events/877204682299351/)

[Participe da comunidade GDG Aracaju](http://www.gdgaracaju.com.br/p/participe.html)

