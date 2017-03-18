---
layout: post
title:  "Linux #1 - O Linux!"
date: 2017-03-17
author: Michel Lacerda
---
![GNU/Linux vs Linux](/imgs/gnu-linux.png){:width="300"}
É comum encontrar discussões  na internet sobre GNU/Linux vs Linux, porém, dificilmente achará alguém que saiu ganhando nessa discussão. Como o próprio Linus Torvalds disse uma vez "chame como quiser, desde que use" (ou algo assim).

Para entender o que é Linux precisamos entender um pouco sobre o que é GNU (GNU is Not Unix -  GNU Não é Unix). O projeto GNU foi criado por Richard Stallman na primeira metade da década de 80, o estopim para criação do projeto GNU se deu por conta de uma discrepância entre Stallman e alguns dispositivos (reza a lenda que foi uma impressora da Xerox) de código fechado que apresentavam mal funcionamento no MIT, a ausência do código fonte o irritou muito, já que esse problema poderia ser resolvido com alguns ajustes (se não me engano era algo relacionado a fila de impressão). 

Devido a esse pequeno infortúnio  Stallman decide criar um sistema operacional aos moldes do Unix, utilizando apenas software livre e sobre a licença GPL (General Public License - Licença Pública Geral), também criada por ele. Posteriormente  Stallman criou uma instituição sem fins lucrativos chamada de Free Software Foundation (Fundação para o Software Livre) para defender e propagar o software livre.

Stallman desenvolveu diversas ferramentas que substituiam as ferramentas do Unix e que poderiam compor um sistema operacional, porem o seu kernel (hurd) estava e está longe de ser efetivamente útil, e é nesse ponto da história que o Kernel Linux entra e da inicio a toda essa discussão.  Futuramente Linus Torvalds lançou seu kernel sobe a licença livre, possibilitando que as ferramentas do GNU pudessem ser incorporadas ao Linux.

> [Ferramentas do GNU](https://www.gnu.org/software/software.html){:target="_blank"} - são muitas!

Por hora podemos definir de forma grosseira o que é um Kenel (vai haver uma postagem só sobre Kernel), o Kernel é responsável por criar uma interface entre software e hardware, algumas dessas interfaces são: 

- Process Management - Gerir Processos
- Memory Management - Gerir Memória,
- Virtual File System - Sistema de Arquivos Virtual
- Networking Layer - Comunicação de Rede
- Interprocess Communications - Comunicação entre Processos.

Agora que já sabemos que o Linux é um Kernel e GNU é um conjunto de ferramentas que compõe o sistema operacional GNU/Linux, não há motivos para discutir qual nome é mais adequado, já que se você substituir todas ferramentas GNU por qualquer outra equivalente o Kernel Linux não vai deixar de existir assim como o GNU também não.

> A principio o Linux se chamaria Freax (free - Livre , freak - estranho, X do Unix), mas um cara chamado Ari Lemmke achou que seria melhor o acrônimo entre Linus e Unix, dando então o nome Linux (Linus + X de Unix).

> O Pinguim característico do Linux se chama Tux e foi escolhido pelo Linus, que diz gostar muito de pinguins.  

A principio o Kernel Linux era apenas um projeto pessoal de Linus Torvalds, inspirado no Minix, um sistema operacional simples de micro-kernel.

> Linus Torvalds: a better Minix than Minix - um Minix melhor que o Minix.

A primeira versão oficial do Linux foi lançada em outubro de 1991 (0.02), no ano seguinte Linus altera a licença do Linux para uma licença livre e compatível com a GPL.

A iniciativa foi tão bem aceita que em poucos meses o Linux já tinha algumas dezenas de colaboradores e em poucos anos começou a surgir empresas especializadas em Linux, a mais famosa de todas é a Red Hat, fundada em 1993, seguida por diversas outras empresas que passaram a apoiar o desenvolvimento do Linux.

Hoje o Linux roda em diversas plataformas, desde uma geladeira (LoT (Internet of Things - internet das coisa)) até um mainframe como o IBM One (atual).

Atualmente existe diversos blogs e canais no YouTube sobre Linux, vou deixar alguns legais:

- [DioLinux](https://www.youtube.com/user/Diolinux){:target="_blank"}
- [TocaDoTux](https://www.youtube.com/user/tocadotux){:target="_blank"}
- [Oficina do Tux](https://www.youtube.com/channel/UCfh_Dbh1LrqGVJQ1k2f6DgQ){:target="_blank"}
- [Ubuntu Dicas](http://www.ubuntudicas.com.br/){:target="_blank"}

> Ajudem a manter os textos bem escritos, qualquer erro de ortografia, concordância, incoerência e etc podem ser reportados.