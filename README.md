# markdow
 
## Principais comandos

**O que é ?**

Markdown converte seu texto em HTML válido. Frequentemente usado para formatar arquivos README.
Formato de simples de markup, isso é, de marcação de texto. Marcar um texto informando o que é:
Salvar o nome do arquivo com a extensão .md

**Estrutura**

* importante
* tópico
* links 
* imagens
* Cabeçalhos:

**Utilizar marca de hash (#)**

# Nivel 1 (título do artigo)
## Nível 2
### Nível 3
#### Nível 4 
##### Nível 5 <h5>
###### Nível 6 <h6>

**Texto básico**

Um paragrafo nâo requer  sintaxe  especial no markdown.

Para formatar um texto:

**texto em negrito** ou __texto em negrito__ 
*texto em itálico* ou _
***negrito e itálico***

Para ignorar os caracteres de formatação use \ antes do caractere:

Este não é um tipo \*itálico\* 

**Listas numeradas e lista de itens**

Começar com a linha 1. ou 1( mas não ambos os formatos na mesma linha. Não precisa especificar os números. 

Exemplo:

1. passo 1.
1. próximo passo.

Vira:

1. passo1.
2. próximo passo.

Para criar listas de itens, comece uma linha com * ou - ou +, mas não misture os formatos em uma mesma lista.

Exemplo 1:

* primeiro item em uma lista não ordenada
* um outro item.

Exemplo 2:

1. bla bla bla
1. bal bla bla bla 


![imagem]("foto.png")
1. bla bla

| Hello | world |
|---|---|
| How | are you ? |
1. bla bla bla bla

<div class="extension note">
    <div>Observação</div>
    <div>
        <p>Texto</p>
    </div>
</div>

1. bla bla bla

**Tabela**

As tabelas não fazem parte da especificação principal do Markdown. O Markdown não é compatível com listas de várias linhs em células. A prática recomendada é evitar o uso de várias linhas em tabelas.

**Crindo tabelas**

Inclua uma linha em branco antes da tabela para que ela seja renderizada corretamente.

| define colunas e linhas separando cada coluna
- criam cabeçalhos de cada coluna

<linha em branco>
 
| header 1 | header 2 | header 3 |
|--- |--- |--- |
| row 1 | column 2 | colum 3 |
| row 2 | row 2 column 2 | row 2 colum 3 |

**Links**

* texto âncora:

[link text](link)

Exemplo:

[Adobe](www.adobe.com)

Links para artigos (referências cruzadas) utilize links relativos.

Veja [Overview example article](../../overview.md)

**Imagem**

![imagem](/marcos_2021/foto.png?lang=pt-BR)
![imagem](foto.png)

Dado espaços:

Para colocar outros blocos de Markdown numa citação basta acionar:.

> + <space>

Exemplo:

> O '>' nas linhas em branco é obrigatório 
> para criar um único bloco de citação.
> >

**Editores Markdown**

* MarkPad
* MarkView

**Centralizando texto**

<center>Centered text</center>
<div align="center">Conteúdo</div>

**Pulando linhas**

* usar uma barra invertidano final da linha \
* lista html para criar marcadores ou números ul ou ol
* <br />

**Como formatar Readme**

* Header equivalente <h1> .. <h3>
* Ênfase equivalente ao <b> negrigro </b>, <i> itálico </i> e <strike> riscado </strike>
* lista ordenada equivalente <ol>
* lista não ordenada equivalente ao <ul>
* Links equivalente <a>
* ''' formatar código ou texto '''

**Inserindo imagem**

!["My Mother"]('foto mama'.jpg)

**Documentando um projeto**

1. Logo
2. Name (Título)
3. Description (Descrição)
4. Features (framworks e tecnologias utilizada e o que faz resumidamente cada)
5. Visuals (GIF do projeto ou screenshots)
6. Getting started (como começar a utilizar o repositório)

**Instalando o markdown no Windows**

1. baixar e instalar o ATOM

#<b>Passo a passo de como fazer o Readme aparecer no seu overview:</b>
 
[Natansl](https://natansl.medium.com/criando-um-readme-para-seu-perfil-no-github-6eb119218c4)<br/>
[Repositório para alguns badges que você pode utilizar](https://github.com/alexandresanlim/Badges4-README.md-Profile)<br/>
[Repositório com Dynamic cards](https://github.com/anuraghazra/github-readme-stats)<br/>
[Repositório com Emojis para Readme](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)<br/>
[livros gratuitos de várias linguagens](https://books.goalkicker.com/)<br/>


