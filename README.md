 # Dicas _HTML_CSS

 # Dominando algumas TAGs HTML

 ## Principal 

 * < !DOCTYPE html > - indica a versão do html

 * < html > - conteúdo do código html

 * < head > - informações de cabeçalho

 * < body > - envolve todo o corpo do documento

 * < !-- > - comentário


  * No HTML5, o documento padrão recebe a seguinte estrutura:

   * < !DOCTYPE html >
   * < html lang="en" >
   * < head >  < !--cabeçalho-- >
       * < meta charset="UTF-8" >
       * < meta http-equiv="X-UA-Compatible" content="IE=edge" >
       * < meta name="viewport" content="width=device-width, initial-scale=1.0" >
       * < link rel="stylesheet" href="home.css" > < !-- link para estilização da pagina, originado de outra estrutura de cogido usando CSS -- >
       * < title >Home< /title > < !--Titulo da pagina-- >
   * < /head >
   * < body > < !-- Corpo da pagina -- >

   * < /body >
   * < /html >

 ## Demais TAGs
 * < b > - negrito
 * < i > - itálico
 * < u > - sublinhado
 * < strong > - maior ênfase no texto em negrito
 * < em > - maior ênfase no texto em itálico
 * < ol > - lista ordenada
 * < ul > - lista não ordenada
 * < li > - um item da lista
 * < menu > - menu com lista de itens
 * < dir > - lista de diretórios
 * < dl > - lista de descrição
 * < dt > - termo a ser descrito
 * < dd > - descrição
 * < table > - cria uma tabela
 * < caption > - legenda da tabela
 * < tr > - linha da tabela
 * < th > - célula de cabeçalho
 * < td>  - célula de dados
 * < form > - define um formulário
 * < input > - caixa de entrada de dados
 * < textarea > - campo de texto
 * < select > - seleção de opções
 * < option > - define uma opção
 * < label > - legenda para os campos
 * < main > - conteúdo principal do corpo
 * < header > - cabeçalho da página
 * < footer > - rodapé da página
 * < section > - define uma seção na página
 * < article > - define um artigo na página
 * < aside > - conteúdo "ao lado” (lateraliza)
 * < nav > - seção de links de navegação
 * < div > - define uma divisão na página
 * < style > - estilização do conteúdo indicado
 * < script > - conteúdo de linguagem script
 * < p > - parágrafo
 * < a > - criação de links
 * < img > - imagem
 * < pre > - texto pré formatado (com enter, tab)
 * < h1 > - cabeçalho escrito (vai de h1 - h6, sendo h1o maior tamanho de letra e h6 o menor)
 * < br > - quebra de linha
 * < title > - título da página web (na aba)
 * < meta > - informações do documento (metadados)
 * < link > - inclusão de outros documentos


 # Dominando o CSS

 # Principais Propriedades

 ## Testos e Fontes

 * font-family - Família de fonte utilizada (ex.: serif)
 * font-style - estile usado na fonte (ex.: italic)
 * font-size - tamanho da fonte (ex.: 12px)
 * font-weight - o peso ou a intensidade da fonte (ex.: bold)
 * font-variant - altera a variante da fonte (ex.: normal or small-caps)
 * text-ident - recuo a esquerda da primeira linha (ex.: 3em)
 * text-align - alinhamento do texto (ex.: letf)
 * test-decoration - efeitos decorativos (ex.: underline)
 * word/letter-spacing - espaço entre palavras/letras (ex.: 1em)

   ou também é possivel utilizar os atalhos para definir tudo em uma só propriedade: font

 ## Cores e Fundos

 * color - cor do texto (ex.: #ffffff)
 * background-color - cor do fundo (ex.: black)
 * background-image - imagem do fundo (ex.: url(http://...))
 * background-repeat - define se a imagem de fundo repetirá (ex.: no-repeat)
 * background-attachment - define se a imagem do fundo será fixa ou moverá conforme 
                            a página (ex.: scroll)
 * background-position - posição da imagem de fundo (ex.: right top)

   ou também é possivel utilizar os atalhos para definir tudo em uma só propriedade: background

 ## Bordas

 * border-top-width         
 * border-right-width        lagura das bordas nos quatro
 * border-bottom-width        quadrantes (ex.: medium)
 * border-left-width

 * border-top-color
 * border-right-color         cor das bordas nos quatro
 * border-bottom-color         quadrantes (ex.: black)
 * border-left-color
 
 * border-top-style
 * border-right-style         definição de estilos das 
 * border-bottom-style         bordas nos quatro    
 * border-left-style            quadrantes (ex.: dotted)

   ou também é possivel utilizar os atalhos para definir tudo em uma só propriedade:

         border-width          border-color             border-style             border

 ## Contornos e Tabelas

 * cursor - especifica o cursor (ex.: pointer)
 * outline-width - espessura da linha de contorno (ex.: thin) 
 * outline-style - estilo da linha de contorno (ex.: dotted)
 * outline-color - cor da linha de contorno (ex.: #F22)
 * caption-side - posiçao do título da tabela (ex.: bottom)
 * table-layout - define layout automático (ex.: fixed)
 * border-collapse - modelo de borda usado (ex.: collapse)
 * clear - controle de limpeza do elemento float (ex.: left)
 * border-spacing - distâncias entre células (ex.: 15pt)
 * empty-cells - visibilidade de células vazias (ex.: hide)

 ## Margens e Espaçamento

 * margin-top
 * margin-right               Tamanho da margem para
 * margin-bottom              cada um dos quatro 
 * margin-left                quadrantes (ex.: 2em)

 * padding-top
 * padding-right              Distância utilizada para
 * padding-bottom             espaçamento nos quatro
 * padding-left               quadrantes (ex.: 2em)

   ou também é possível utilizar os atalhos para definir tudo em
                  uma só propriedade: 

              margin              padding

 ## Formatação visual

 * display - forma de exibição do conteúdo (ex.: inline)
 * position - posicionamento (ex.: absolte)
 * float - posicionamento adjacente à esquerda ou à direita 
           do elemento (ex.: left)
 * clear - controle de limpeza de elemento float (ex.: left)
 * direction - define a direção do texto da direita para a esquerda
               ou da esquerda para a direita (ex.: ltr)
 * top
   right           distância do elemento com relação à 
   bottom          extremidade de seu elemento pai (ex.: 20px)
   left

 # Principais Seletores

 ## Seletores Básicos

 * *{} - afeta todos os elementos da página
 * tag {} - afeta todos elementos dessa tag
 * .classe {} - afeta todos os elementos com essa classe
 * #identificador {} - afeta todos os elementos com esse id
 * [atributo] {} - afeta todos os elementos que contenham esse atributo
 * [atributo=valor] {} - afeta todos os elementos que contenham esse atributo com esse valor
 * [atributo*=valor] {} - afeta todos os elementos que contenham esse valor em algum lugar desse atributo

 ## Seletores Combinadores 

 * elem1 elem2 {} - afeta todos os elem2 que sejam descendetes de elem1 (filhos diretos ou não)
 * elem1 > elem2 {} - afeta todos os elem2 que sejam filhos diretos do elem1
 * elem1 + elem2 {} - afeta o elem2 seguinte de elem1, ambos com o mesmo pai (irmãos adjacentes)
 * elem1 - elem2 {} - afeta todos os elem2 seguintes de elem1, todos com o mesmo pai (irmãos de forma geral)

 ## Seletores Pseudo-classe 

    São palavras-chaves adicionadas aos seletores que especificam um estado especial do elemento selecionado

                                  elemento : pseudoclasse {}

 ### Exemplos de pseudpclasses:

 * :hover - aparece ao passsar o mouse por cima
 * :active - aparece quando o elemento é ativado/clicado
 * :visited - aparece quando o elemento/link já foi visitado
 * :focus - aparece quando o elemento recebe foco, como quando é 
            selecionado com o teclado, por exemplo                                   

 ### Exemplo

 * div.menu a:hover {}
 * #content p {}

                qual é o mais específico?

 * div.menu a:hover {} = (0,0,2,2)
 * #content p {} = (0,1,0,1)

   Portanto, o segundo será utilizado para estilizar o elemento!
