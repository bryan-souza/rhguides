# <center>Guia Definitivo de ROM Hacking para Iniciantes [v1.00]</center>

> Autor: InVerse (28/02/2003)  
> Tradução e Conversão para Markdown: Hellstrike12

***

## <a name="introducao">Introdução</a>

O propósito deste guia é introduzir principiantes ao universo das _Hack ROMs_ com direções para que encontrem a informação que desejam. Este guia
 NÃO te ensinará como criar uma _Hack ROM_, ele te mostrará onde encontrar informação sobre _ROM Hacking_, como começar e erros a serem evitados.

***

## <a name="conteudos">Tabela de Conteúdos</a>

01. [Introdução](#introducao)
02. [Tabela de Conteúdos](#conteudos)
03. [Histórico do Documento](#historico)
04. [Índice](#indice)
05. [Seção I     (O Básico)](#01)
06. [Seção II    (Começando)](#02)
07. [Seção III   (Editando Gráficos)](#03)
08. [Seção IV    (Editando Textos)](#04)
09. [Seção V     (Editando Outras Coisas)](#05)
10. [Seção VI    (Traduzindo)](#06)
11. [Seção VII   (_ROM Hacking_ Avançado)](#07)
12. [Seção VIII  (Linguagem _Assembly_)](#08)
13. [Seção IX    (Miscelânea)](#09)
14. [Seção X     (Ferramentas)](#10)
15. [Seção XI    (Etiqueta)](#11)
16. [Seção XII   (O Cenário das _Hack ROMS_)](#12)
17. [Recursos](#recursos)
18. [Conclusão](#conclusao)
19. [Créditos](#creditos)
20. [Contato](#contato)

***

## <a name='historico'>Histórico do Documento</a>

28/02/2003 - v1.00 - Lançamento inicial

***

## <a name='01'>Seção I - (O Básico)</a>

* [O que é a _ROM_?](#0101)
* [O que é _ROM Hacking_?](#0102)
* [Porque as pessoas fazem _Hack ROMs_?](#0103)
* [Quais tipos de pessoas fazem _Hack ROMs_?](#0104)
* [Qual a qualidade mais importante de um _ROM Hacker_?](#0105)
* [_ROM Hacking_ é legalizado?](#0106)

## <a name="02">Seção II - (Começando)</a>

* [Como eu posso fazer uma _Hack ROM_?](#0201)
* [De quais ferramentas preciso?](#0202)
* [O que eu devo fazer primeiro?](#0203)
* [Qual a coisa mais importante que eu deveria saber antes de começar?](#0204)
* [Porque xxxxx programa não funciona?](#0205)
* [E as ferramentas para Mac, Unix, etc?](#0206)

## <a name="03">Seção III - (Editando Gráficos)</a>

* [Como faço para editar os gráficos?](#0301)
* [Porque os gráficos estão todos embaralhados?](#0302)
* [Porque não consigo encontrar os gráficos que quero modificar?](#0303)
* [Como faço para editar a tela inicial de uma _ROM_?](#0304)
* [Porque as cores estão todas erradas?](#0305)
* [Como faço para mudar a cor dos gráficos?](#0306)
* [Porque minhas modificações não aparecem?](#0307)

## <a name="04">Seção IV - (Editando Textos)</a>

* [Como faço para editar textos?](#0401)
* [O que é uma tabela?](#0402)
* [Como crio uma tabela?](#0403)
* [E se os textos que quero modificar estiverem em Japonês?](#0404)
* [Como libero mais espaço para meus textos?](#0405)
* [Porque não consigo encontrar o texto que quero modificar?](#0406)
* [O que é um _script_?](#0407)
* [Como faço para extrair/inserir um _script_?](#0408)
* [Como faço para construir um _script dumper_ personalizado?](#0409)

## <a name="05">Seção V - (Editando Outras Coisas)</a>

* [Como faço para modificar níveis?](#0501)
* [Como faço para editar estatísticas?](#0502)
* [Como faço para editar itens?](#0503)
* [Como faço para modificar arquivos de salvamento?](#0504)
* [Como faço para tornar meus códigos de _Game Genie_ permanentes?](#0505)

## <a name="06">Seção VI - (Traduzindo)</a>

* [Como faço para traduzir Japonês?](#0601)
* [Posso usar um tradutor online?](#0602)
* [Como posso encontrar um tradutor de _scripts_?](#0603)
* [Como posso visualizar os caracteres japoneses em meu computador?](#0604)
* [Como posso digitar em Japonês?](#0605)
* [Quais são os diferentes tipos de caracteres japoneses?](#0606)

## <a name="07">Seção VII - (_ROM Hacking_ Avançado)</a>

* [O que é um arquivo ISO?](#0701)
* [Como posso modificar jogos de Playstation?](#0702)
* [Como posso modificar jogos de sistemas mais atuais?](#0703)
* [Como posso modificar jogos de PC?](#0704)

## <a name="08">Seção VIII - (Linguagem _Assembly_)</a>

* [O que é a linguagem _Assembly_?](#0801)
* [O que é _Assembly Hacking_?](#0802)
* [Como faço para aprender _Assembly_?](#0803)

## <a name="09">Seção IX - (Miscelânea)</a>

* [Porque as _Hacks_/Traduções são distribuidas como _Patches IPS_?](#0901)
* [O que devo escolher para meu primeiro projeto de tradução?](#0902)
* [Porque existem tantas _Hack ROMs_ inacabadas de determinados jogos?](#0903)

## <a name="10">Seção X - (Ferramentas)</a>

* [Quais ferramentas para edição de gráficos devo usar?](#1001)
* [Quais ferramentas para edição de textos devo usar?](#1002)
* [Quais emuladores são bons para _hacking_?](#1003)

## <a name="11">Seção XI - (Etiqueta)</a>

* [Como posso pedir ajuda sem parecer idiota?](#1101)
* [Como posso começar um grupo de _ROM Hacking_?](#1102)
* [Como posso encontrar uma pessoa para traduzir um jogo em particular?](#1103)
* [Porque não devo enviar uma _ROM_ para um _ROM Hacker_ por email?](#1104)

## <a name="12">Seção XII - (O Cenário das _Hack ROMs_)</a>

* [O que é "O Cenário"?](#1201)
* [Quem é um membro do "Cenário"?](#1202)
* [Como posso entrar para "O Cenário"?](#1203)
* [Quais os benefícios do "Cenário"?](#1204)
* [Sobre o que essas pessoas estão falando?](#1205)
* [Como eu saio do "Cenário"?](#1206)

***

## <center>**O Básico**</center>

***

### <a name="0101">O que é a _ROM_?</a>

Uma _ROM_ é uma cópia do programa contido em um cartucho de console, recebe esse nome devido ao componente eletrônico usado para armazenar o programa (_**R**ead-**O**nly **M**emory_). Em outras palavras, é o próprio jogo. _ROMs_ podem ser executadas por emuladores, que te permitem jogar jogos de console em um computador.

### <a name="0102">O que é _ROM Hacking?_</a>

 _ROM hacking_ envolve editar uma _ROM_ para diversos propósitos. O termo
 _'hacking'_ é derivado da definição original, que está relacionada com a computação, da palavra cujo significado é 'explorar tecnologia'. O _ROM hacking_ não involve quebrar a segurança da ROM com intuito de desfigurar sua página _web_ ou roubar seu cartão de crédito.

 O _ROM hacking_ pode envolver a tradução de textos de uma língua para outra, a edição de gráficos, a correção de um _glitch_ na programação de um jogo ou qualquer outro número de modificações possíveis.

 ### <a name="0103">Porque as pessoas fazem _Hack ROMs_?</a>

 A única razão distinta e válida para isso é porque elas gostam. Sim, elas desejam ver o jogo que estão modificando jogável em Português. Sim, algumas delas gostam da atenção que recebem por estarem trabalhando em um projeto de alto nível. Mas se você não gosta de enfrentar e superar os desafios envolvidos na modificação de _ROMs_, você jamais conseguirá terminar um projeto com sucesso.

 ### <a name="0104">Quais tipos de pessoas fazem _Hack ROMs_?</a>

 ### <a name="0105">Qual a qualidade mais importante de um _ROM Hacker_?</a>

 ### <a name="0106">_ROM Hacking_ é legalizado?</a>

 ***

 ## <center>**Começando**</center>

 ***

 ### <a name="0201">Como eu posso fazer uma _Hack ROM_?</a>

 ### <a name="0202">De quais ferramentas preciso?</a>

 ### <a name="0203">O que eu devo fazer primeiro?</a>

 ### <a name="0204">Qual a coisa mais importante que eu deveria saber antes de começar?</a>

 ### <a name="0205">Porque xxxxx programa não funciona?</a>

 ### <a name="0206">E as ferramentas para Mac, Unix, etc?</a>

 ***

 ## <center>**Editando gráficos**</center>

 ***

 ### <a name="0301">Como faço para editar os gráficos?</a>

 ### <a name="0302">Porque os gráficos estão todos embaralhados?</a>

 ### <a name="0303">Porque não consigo encontrar os gráficos que quero modificar?</a>

 ### <a name="0304">Como faço para editar a tela inical de uma _ROM_?</a>

 ### <a name="0305">Porque as cores estão todas erradas?</a>

 ### <a name="0306">Como faço para mudar a cor dos gráficos?</a>

 ### <a name="0307">Porque minhas modificações não aparecem?</a>

 ***

 ## <center>**Editando Textos**</center>

 ***

 ### <a name="0401">Como faço para editar textos?</a>

 ### <a name="0402">O que é uma tabela?</a>

 ### <a name="0403">Como crio uma tabela?</a>

 ### <a name="0404">E se os textos que quero modificar estiverem em Japonês?</a>

 ### <a name="0405">Como libero mais espaço para meus textos?</a>

 ### <a name="0406">Porque não consigo encontrar o texto que quero modificar?</a>

 ### <a name="0407">O que é um _script_?</a>

 ### <a name="0408">Como faço para extrair/inserir um _script_?</a>

 ### <a name="0409">Como faço para construir um _script dumper_ personalizado?</a>

***

## <center>**Editando Outras Coisas**</center>

***

 ### <a name="0501">Como faço para modificar níveis?</a>

 ### <a name="0502">Como faço para editar estatísticas?</a>

 ### <a name="0503">Como faço para editar itens?</a>

 ### <a name="0504">Como faço para modificar arquivos de salvamento?</a>

 ### <a name="0505">Como faço para tornar meus códigos de _Game Genie_ permanentes?</a>

***

## <center>**Traduzindo**</center>

***

 ### <a name="0601">Como faço para traduzir Japonês?</a>

 ### <a name="0602">Posso usar um tradutor online?</a>

 ### <a name="0603">Como posso encontrar um tradutor de scripts?</a>

 ### <a name="0604">Como posso visualizar os caracteres japoneses em meu computador?</a>

 ### <a name="0605">Como posso digitar em Japonês?</a>

 ### <a name="0606">Quais são os diferentes tipos de caracteres japoneses?</a>

***

## <center>**_ROM Hacking_ Avançado**</center>

***

 ### <a name="0701">O que é um arquivo ISO?</a>

 ### <a name="0702">Como posso modificar jogos de Playstation?</a>

 ### <a name="0703">Como posso modificar jogos de sistemas mais atuais?</a>

 ### <a name="0704">Como posso modificar jogos de PC?</a>

***

## <center>**Linguagem _Assembly_**</center>

***

 ### <a name="0801">O que é a linguagem _Assembly_?</a>

 ### <a name="0802">O que é _Assembly Hacking_?</a>

 ### <a name="0803">Como faço para aprender _Assembly_?</a>

***

## <center>**Miscelânea**</center>

***

 ### <a name="0901">Porque as _Hacks_/Traduções são distribuidas como _Patches IPS_?</a>

 ### <a name="0902">O que devo escolher para meu primeiro projeto de tradução?</a>

 ### <a name="0903">Porque existem tantas _Hack ROMs_ inacabadas de determinados jogos?</a>

***

## <center>**Ferramentas**</center>

***

 ### <a name="1001">Quais ferramentas para edição de gráficos devo usar?</a>

 ### <a name="1002">Quais ferramentas para edição de textos devo usar?</a>

 ### <a name="1003">Quais emuladores são bons para _Hacking_?</a>

***

## <center>**Etiqueta**</center>

***

 ### <a name="1101">Como posso pedir ajuda sem parecer idiota?</a>

 ### <a name="1102">Como posso começar um grupo de ROM Hacking?</a>

 ### <a name="1103">Como posso encontrar uma pessoa para traduzir um jogo em particular?</a>

 ### <a name="1104">Porque não devo enviar uma ROM para um ROM Hacker por email?</a>

***

## <center>**O Cenário das _Hack ROMs_**</center>

***

 ### <a name="1201">O que é "O Cenário"?</a>

 ### <a name="1202">Quem é um membro do "Cenário"?</a>

 ### <a name="1203">Como posso entrar para "O Cenário"?</a>

 ### <a name="1204">Quais os benefícios do "Cenário"?</a>

 ### <a name="1205">Sobre o que essas pessoas estão falando?</a>

 ### <a name="1206">Como eu saio do "Cenário"?</a>

***

## <center><a name="recursos">**Recursos**</a></center>

***



***

## <center><a name="conclusao">**Conclusão**</a></center>

***



***

## <center><a name="creditos">**Créditos**</a></center>

***



***

## <center><a name="contato">**Contato**</a></center>


***