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
html <p> </p>
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