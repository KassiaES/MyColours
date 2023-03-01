# MyColours
trabalho para estudo de HTML e CSS

## HTML
###### _Origem: Wikipédia, a enciclopédia livre_

HTML (abreviação para a expressão inglesa HyperText Markup Language, que significa: "Linguagem de Marcação de Hipertexto") é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.

HyTime é um padrão para a representação estruturada de hipermídia e conteúdo baseado em tempo. Um documento é visto como um conjunto de eventos concorrentes dependentes de tempo (como áudio, vídeo, etc.), conectados por hiperligações (em inglês: hyperlink e link). O padrão é independente de outros padrões de processamento de texto em geral.

SGML é um padrão de formatação de textos. Não foi desenvolvido para hipertexto, mas tornou-se conveniente para transformar documentos em hiper-objetos e para descrever as ligações.

### Marcas (tags)
Todo documento HTML possui marcadores (do inglês: tags), palavras entre parênteses angulares (chevron) (< e >); esses marcadores são os comandos de formatação da linguagem. Um elemento é formado por um nome de marcador (tag), atributos, valores e filhos (que podem ser outros elementos ou texto). Os atributos modificam os resultados padrões dos elementos e os valores caracterizam essa mudança.

## CSS (Cascading Style Sheets)
Cascading Style Sheets (abreviado CSS) é um mecanismo para adicionar estilos (cores, fontes, espaçamento, etc.) a uma página web,[1] aplicado diretamente nas tags HTML ou ficar contido dentro das tags <style>. Também é possível, adicionar estilos adicionando um link para um arquivo CSS que contém os estilos. Assim, quando se quiser alterar a aparência dos documentos vinculados a este arquivo CSS, basta modifica-lo.

Com a variação de atualizações dos navegadores, o suporte ao CSS pode variar. A interpretação dos navegadores pode ser avaliada com o teste Acid2, que se tornou uma forma base de revelar quão eficiente é o suporte de CSS, fazendo com que a nova versão em desenvolvimento do Firefox seja totalmente compatível a ele, assim como o Opera já é. O Doctype informado, ou a ausência dele, determina o quirks mode ou o strict mode, modificando o modo como o CSS é interpretado e a página desenhada.

### Sintaxe
CSS tem uma sintaxe simples, e utiliza uma série de palavras em inglês para especificar os nomes de diferentes propriedade de estilo de uma página.

Uma instrução CSS consiste em um seletor e um bloco de declaração. Cada declaração contém uma propriedade e um valor, separados por dois pontos (:). Cada declaração é separada por ponto e vírgula (;).

Em CSS, seletores são usados para declarar a quais elementos de marcação um estilo se aplica, uma espécie de expressão correspondente. Os seletores podem ser aplicados a todos os elementos de um tipo específico, ou apenas aqueles elementos que correspondam a um determinado atributo; elementos podem ser combinados, dependendo de como eles são colocados em relação uns aos outros no código de marcação, ou como eles estão aninhados dentro do objeto de documento modelo.

Pseudoclasse é outra forma de especificação usada em CSS para identificar os elementos de marcação, e, em alguns casos, ações específicas de usuário para o qual um bloco de declaração especial se aplica. Um exemplo frequentemente utilizado é o :hover pseudoclasse que se aplica um estilo apenas quando o usuário 'aponta para' o elemento visível, normalmente, mantendo o cursor do mouse sobre ele. Isto é anexado a um seletor como em a:hover ou #elementid:hover. Outras pseudoclasses e pseudoelementos são, p. ex., :first-line, :visited ou :before. Uma pseudoclasse especial é :lang(c), "c".

Uma pseudoclasse seleciona elementos inteiros, tais como :link ou :visited, considerando que um pseudoelemento faz uma seleção que pode ser constituída por elementos parciais, tais como :first-line ou :first-letter.

Seletores podem ser combinados de outras formas também, especialmente em CSS 2.1, para alcançar uma maior especificidade e flexibilidade.

### Seletores
Definição de estilo é um conjunto de propriedades visuais para um elemento, o CSS define regras que fazem as definições de estilo casarem com um elemento ou grupo de elemento, o documento pode conter um bloco de CSS num elemento style ou usando o elemento link apontando para um arquivo externo que contenha o bloco CSS.

Para uso com o CSS, foi criado o atributo class que todo elemento pode conter.

As regras de casamento para o CSS são chamadas de seletores, uma definição de estilo pode ser casada com um seletor ou um grupo de seletores separados por vírgula, um seletor pode casar um elemento por:

elemento do tipo : element_name { style definition; }
elemento do tipo com a classe : element_name.class_name { style definition; }
todos os elementos com a classe : .class_name { style definition; }
o elemento com o id : #id_of_element { style definition; }
casamento de um grupo : element_name_01, element_name_02, .class_name { style definition; }
Exemplos
