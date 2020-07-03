# Informações básicas sobre HTML & CSS

- esse documento tem como finalidade reunir informações básicas sobre HTML & CSS que reuni durante a graduação em Sistemas para Internet pela FATEC

- esse repositório conta com uma página que exibe o resultado de todos os códigos reunidos nesse documento

## O que é HTML

- Html é uma abreviação de *HyperText Markup Language*
- Uma linguagem de marcação é um conjunto de **marcação de tags**
- Documentos HTML são descritos por **HTML Tags**
- Cada tag HTML descreve diferentes conteúdos do documento

## HTML Tags

- Tags html são **palavras-chave** entre colchetes

```html 
<nomeTag>conteúdo</nomeTag>
```

- As tags HTML normalmente são usadas em pares
- A primeira tag do par refere-se a **tag inicial** e a segunda tag refere-se a **tag final**
- A tag final é escrita com um barra (/) antes do nome da Tag final

## Estrutura de um arquivo HTML

- Basicamente um arquivo HTML possui 3 *containers* principais

~~~html
<!DOCTYPE html> <!-- Especifica para o navegador qual é o tipo de página HTML utulizada -->
<html>
    <head> </head> <!-- Define o inicio e o fim do cabeçalho do documento -->
    <body> </body> <!-- Insere-se os conteúdos do site que deverão ficar visiveis quando a página for rendenizada no navegador -->
</html> <!-- Definir o inicio e o fim de um documento HTML-->
~~~

## Tag Head

- Contém as instruções para o navegador

* Titulo
* Codificação (DOCTYPE)
* Descrição da página (cabeçalho)
* Palavras chaves (para sistema de busca)
* Chamadas de arquivos externos (scripts, css)

## Tag Body

- Define o que será mostrado ao usuário, contém vários tipos de elementos

* Imagens;
* Animações;
* Textos;
* Links;
* Formulários;
* Listas e
* etc.

## Metadados do Documento

```html 
<head></head>
```
Repesenta uma coleção de metadados sobre o documento, incluindo links das suas definições de scripts e folhas de estilo.

```html 
<tiitle></title>
```
Define o titulo do documento, apresentado na barra de título do navegador ou na guia da página

## Seções
```html 
<body></body>
```
Representa o principal conteúdo de um documento HTML. Há apenas um elemento `<body>` em um documento.

```html 
<h1> <h2> <h3> <h4> <h5> <h6>
```
São elementos que representam os seis níveis de titulos de cabeçalhos dos documentos. Um elemento título descreve brevemente o tema da seção.

## Agrupando Conteúdo

```html
<p> </p>
```
Define o que deve ser exibido como um paragráfo.

```html
<hr>
```
Representa uma ruptura temática entre paragráfos de um artigo ou seção ou qualquer conteúdo mais longo

```html
<ol> </ol>
```
Define uma lista ordenada

```html
<ul> </ul>
```
Define uma lista não ordenada

```html
<li> </li>
```
Define um item de uma lista `<ol>` ou de uma `<ul>`

```html
<dl> </dl>
```
Representa uma lista de Definição

```html
<dt> </dt>
```
Representa um item da Lista de Definição `<dd>`

```html
<dd> </dd>
```
Representa a definição dos termos listados imediadamente antes deles

```html
<div> </div>
```
Representa um *container* genérico sem nenhum significado especial

## Semântica Textual

`<a></a>` (usado com atributo href) representa um *hyperlink*, ligando a outro recurso.

`<em></em>` ou `<i></i>` representa a ênfase do conteúdo em itálico.

`<strong></strong>` representa a importância de um pedaço de texto como um forte elemento mas não altera o sentido da frase.

`<small></small>` texto com fonte menor que o padrão

`<code></code>` saída com estilo código

`<samp></samp>` saída como *output* de código de computador

`<kbd></kbd>` estilo *input* de teclado

`<u></u>` texto sublinhado

`<big></big>` texto maior que o padrão

`<sub></sub>` texto subescrito

`<sup></sup>` texto sobrescrito

`<s></s>` ou `<strike></strike>` texto tachado.

## Tags para Máquina

~~~html
<!DOCTYPE html>
<meta charset="utf-8">
<html lang="pt-br">
<meta name="keywords" content="esportes, jornais, revistas,bibiliotecas">
<meta name="description" content="O uol é o maior provedor de acessoa à internet do Brasil.">
~~~

# HTML 5 

=> Um dos principais objetivos do HTML5 é **facilitar a manipulação do elemento** possibilitando o desenvolvedor a modificar as caracteristicas dos objetos de forma não intrusiva e de maneira que seja transparente para o usuário final.
=> O HTML5 fornece ferramentas para a **CSS** e o ***JAVASCRIPT*** fazerem seu trabalho da melhor maneira possível. Permite por meio de suas APIs a manipulação das caracteristicas destes elementos, de forma que o *website* ou a aplicação continue leve e funcional.

## *Section Contente*

=> Estes elementos definem um grupo de cabeçalhos e rodapés. Basicamente são elementos que juntam grupos de textos no documento.

**- article**: O elemento `<article>` é uma especie de `<section>` especializada; possui valor semântico mais especifico do que o valor semântico de `<section>`, no sentido de ser um bloco de conteúdo relacionados independente e autossuficiente. Representa uma parte da página que poderá ser distribuido e reutilizável em *feeds* por exemplo. Isto pode ser um *post*, artigo, um blocode comentários de usuários ou apenas um bloco de texto comum.

**- aside**: Marcamos com `<aside>`, aquele conteúdo relacionado ao conteúdo principal do site. Pode ser representado por conteúdos em *sidebar*, em textos impressos, publicidade ou até mesmo para criar um grupo de elementos *nav* e outras informações separados do conteúdo principal do *website*.

**- nav**: Marcamos como *nav*, a navegação do site. Os links pelos quais os visitantes vão alcançar nossos conteúdos, somente *links* importantes. Até mesmo um formulário pode fazer parte da nossa navegação.

**- section**: O elemento `<section>` é tão somente um bloco de conteúdos relacionados.

**- header**: Parte que se mantém fixa mesmo com a mudança de páginas. Geralmente, a área que contém o logotipo e a naegação principal do site.

**- footer**: Geralmente contém aquela copyright de direitos autorais, contém os artigos relacionados, os botões das redes sociais e etc.

**- hgroup**: Este elemento consiste em um grupo de titulos. Ele serve para agrupar elementos de titulo de H1 até H6 quando eles tem multiplos níveis como título com subtitulos e etc.

**- time**: Este elemento serve para marcar parte do texto que exibe um horário ou uma data precisa no calendário gregoriano

# CSS (Cascading Style Sheets)

É um especificação que define como elementos que compõem uma página, um documento ou aplicação web serão exibidos.
O CSS traz toda a informação do *layout*, isto é, cores, posicionamento, fontes, tamanhos e imagens de fundo, enquanto o HTML deve fornecer uma 'arquitetura' para o conteúdo.

**O ARQUIVO DEVE SER SALVO COM A EXTENSÃO .CSS**

## Como funciona

Em um documento você pode ter vários arquivos CSS, carregando diferentes regras que se referem a multiplos ou ao mesmos elementos.

## Quais os beneficios

- controle de interface em diferentes documentos em um único arquivo
- controle de diferentes interfaces para diferentes dispositivos (*responsive design*)
- precisão para manter a mesma interface para diferentes navegadores
- melhorias na acessibilidade com a possibilidade de esconder elementos da tela para usuarios sem problemas de visão, mas manter os mesmos elementos acessíveis para leitores de tela
- menor consumo de banda para usuário e servidor
- inumeras técnicas dinâmicas que não poderiamser utilizadas em tabelas
