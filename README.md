# html-desenvolvimento

# Ambiente Dev: preparando o seu computador

# Criando paginas HTML

O HTML é a base de qualquer website ou aplicação WEB hoje, e aqui você vai aprender HTML enquanto cria páginas do mundo real.

# Modulo 01 - Sua base


# O que é necessário - aula 00

- Google Chrome

- Edge

- VSCode: Existe uma grande comunidade que desenvolve estensões para facilitar o desenvolvimento.

Instale os seguintes plugins

1. Live Server: Servidor local ver as modificações no Navegador.

3. Bracket Pair Colorizer 2: Faz a junção dos parentes, chaves e colchetes

5. vscode-icons: icones para falicitar entender o projeto.

# Lendo o código fonte de páginas - aula 01

# Sua primeira Tag - aula 02

https://developer.mozilla.org/pt-BR/docs/Web/HTML

* No site da mozila tem muitas explicações sobre como usar as tags HTML. A bse para entender como criar aplicações web. HTML é forma de comunicação entre a nossa pagina e o navegador.

<p align="center">
    <img src="/criado-pagina-html/modulo 01/aula-02/sua-primeria-tag-01.jpeg" width="724" height="324">
</p>

<p align="center">
    <img src="/criado-pagina-html/modulo 01/aula-02/sua-primeria-tag-02.jpeg" width="724" height="324">
</p>

# Comentarios e Hierarquia - aula 03

Exemplo de comentario: <!-- Tudo que eu escrever dentro desta tag-->

Não será encontrado na pagina. Mas consegue inspecionar elementos pelo Navegador e ver esses comentários.

Comentario:
    
    Exemplo:
    
    <!--tudo que eu escrever dentro dessa tag sera oculto da pagina html-->

    Dicas: 
    
    Cltr+K+C  : Comenta seu codigo html
    Cltr+K+U  : Descomenta seu codigo html

 Hierarquia:

 Relacao pai e filho...
 importante para referencia alguns valor...
 ou para inserir algum elemento CSS.

    Exemplo:

    Facilita na hora de fazer uma captura de valor, ou gerenciar esses elementos por CSS.

# Estruturas HEAD e BODY (title) - aula 04

TAGS:

DOCTYPE html: Informação para navegdaor que é um arquivo HTML

html lang="pt-br": Elemento PAI

head: Elemento não visual para o cliente final 

meta: Informa alugumas caracteristica da pagina para o navegador

title: Titulo da sua pagina visualizamos na barra de titulo do navegador.

body: São elemento visual como paragrafo, imagem, video etc...

# Modulo 02: Elementos HTML

Vamos entender neste modulo a diferença entre elementos de textos.

Dica:

Alt+Z : Faz uma quebra de linha no seu codigo dentro do VISUAL CODE.

# Elemento Texto - aula 05

Lorem+10 : Coloca o paragrafo com 10 palavras e assim por diante...

ALT+Z: Quebra as linhas do seu codigo mas não interfere no seu codigo

s: Reideriza um texto tachado. Porem não quebra a linha.

br: Break faz a quebra a linha.

u: Sumblina o texto.

b: Deixa o texto em BOLD (negrito)

strong: Apesar de aparentemente não ter diferença da tag 'b' na documentação porem semanticamente o uso dela é para usar em texto muito forte 'importante'.

i: Deixa o texto em italico.

address: Especificar endereço apesar de ter o mesmo formato do italico mas semanticamente essa é a forma correta de estilizar.

Lembre-se que mesmo o HTML possuir tags que aparentemente mostra a mesma formatação, precisamos entender que existe uma semantica por traz do html.

# Hiperlinks e Atributos - aula 06

a href="http://site.x.x": Faz uma ligação com outra pagina.

a href="pagina.html: Faz uma ligação com outra pagina.

a href="#": Não direciona para nenhuma pagina.

a href="http://site.x.x" target="_blank": Faz uma ligação com outra pagina. E abre uma pagina nova.

a href="mailto:email@x.x.x": Abre seu aplicativo de email.
# Imagens - aula 07

 img src="imagen.jpg" alt="" width="300" height=""

 img src="public/imagen.jpg" alt="Backgroud da Empresa X" width="300" height="200"

 src: Referente onde a imagem está localizada.
 
 alt: É um texto alternativo caso sua imagem não seja exibida na tela.
 
 width: Atributos que especifica o tamanho da imagem
 
 height: É opcional caso voce precise alterar a altura.
 
 * Ela não recebe um paramentro de texto como as tags ateriores que aprendemos ate aqui.

# Listas ordenadas e não ordenadas - aula 08

ul: Lista não ordenada, ele coloca um bolinha em cada item.

li: adiciona itens nessa lista.

ol: Lista ordenada, ele coloca um numero em cada item. (1 ate o infinito)

# Elementos de Formulário - 09

É umas das aulas mais usada em toda carreira de um desenvolvedor.

Ex:

form: Elemento que criar um formulario.

form action="" method"GET": Enviar os dados atraves da url porem não seguro, e quando voce não tem ações sigilosa. Pois as informações fica exposta na url.

form action="enviar.php" method"POST": Enviar os dados atraves de um outro arquivo ex: enviar.php. Pode ser um outro  formato *.php, *.hmtl, *.js etc. Assim os dados fica camuflado e são enviados para o servidor.

fieldset: Cria um conjunto de campos.

legend: Cria uma legenda para seu formluario.

label for="": Sera relacionado ao 'id' de um determinado input. Existe alguns valores que podemos alterar.

input type="text": Cria um campo para digitar qualquer caracter.

type="radio": Permite voce selecionar as opções no formulario.

type="username": Nome do Usuario

type="password": Senha será oculta ao digitar

type="text": Aceita qualquer tipo de caracter.

type="number": Somente aceita caracteres numericos.

type="email": Somente aceita valor nesse campo se for no formato de e-mail x@x.x.x

type="submit": Envia os valores digitado e executa uma ação.

type="reset": Apaga os valores digitado no formulario

required: Quando ele estiver no final do seu input ele vai obrigar que o campo seja digitado.

<p align="center">
    <img src="https://github.com/alvesnet-suporte/html-desenvolvimento/blob/main/criado-pagina-html/modulo%2002/aula-09/cadastro-de-usuarios.PNG" width="724" height="324">
</p>

# Elementos de Tabela - aula 10

Como criar tabela, Colunas e Linhas

table: Cria uma tabela.

tr: Cria uma linha.

td: Cria um coluna.
# Meta Tags - aula 11

title: Titulo do documento que sera mostrado na Aba do navegador.

style: Interpretador de codigos CSS. Normalmente não se usa essa tag style em projetos.

link: Normalmente se um essa opção para estilização de codigo CSS.

    rel="stylesheet" href="style.css": Estlizar condigo CSS

    rel="shortcut icon" href="favicon.ico" type="imagem/x-icon": Publica uma imagem favicon na barra de titulo do seu navegador.


Criador de favicon:

https://www.favicon-generator.org/

https://www.flaticon.com/

Seletor de Cores:

https://color.adobe.com/pt/create/color-wheel

meta: Elemento para definir conjunto de caracter, e informações da sua pagina para os mecanismo de busca.

Dica: www.w3school.com

# Na Prática - Modulo 03

# Dicas de Produtividade

ALT+SHIFT : E as seta para baixo e para acim duplica sua linha do codigo

ALT: Aperta e clicar em cada linha seu cursos sera replicado para faciliar a replicação de valores digitados.

ALT+SETA: Move a linha de lugar.

CLRT+Y: Refaz uma ação para frente o contrario do CTRL+Z.

# Semântica

https://demo.ghost.io/grow/

Entende a estrututa dos elementos HTML

# Prática (Ghost)

Instale o seguinte Plugin no seu VSCode

- Prettier Code Formatter




..











