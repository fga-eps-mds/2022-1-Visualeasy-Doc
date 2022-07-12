# Padrão para Documentos da Wiki

<p align="justify">Este documento tem como objetivo apresentar a padronização para os documentos que serão adicionados na WIKI de documentação do projeto <b>Visualeasy</b>, para o 1º semestre de 2022 da disciplina Engenharia de Produto de Software (EPS).</p>

<p align="justify">A primeira recomendação é quanto aos títulos do documento. Deve-se diferenciar títulos e subtítulos da seguinte forma:</p>

# Título

<p align="justify">Usado para caracterizar o título principal do documento.</p>

## Subtítulo 1

<p align="justify">Utilizado para tópicos principais do texto.</p>

### Subtítulo 2

<p align="justify">Aplicado em subseções dos tópicos do texto.</p>

<br>

## Padrões de texto

<p align="justify">Quanto aos textos, listam-se as seguintes recomendações:</p>


+ Todos os textos devem ser justifados, utilizando a label:
>```<p align="justify"> TEXTO </p>```;

+ Palavras estrangeiras devem ser escritas em <i>Itálico</i>, utilizando a label:
>```<i> TEXTO EM ITÁLICO </i>```;

+ Para destacar alguma palavra ou trecho do texto, deve-se usar <b>Negrito</b>, utilizando a label:
>```<b> TEXTO EM NEGRITO </b>```;

+ Para pular uma linha, o seguinte comando pode ser utilizado:
> ```<br>```

<br>

### Listas

<p align="justify">Se for necessário o uso de listas, elas devem ser da seguinte forma:</p>

> <b>+: </b>Para ponto principal;

> <b>-: </b>:Para subpontos.

+ Primeiro ponto
+ Segundo ponto
+ Terceiro ponto
    - Primeiro subponto do terceiro ponto
    - Segundo subponto do terceiro ponto
+ Quarto ponto

<br>

## Imagens

<p align="justify">Imagens devem ser adicionadas utilizando o seguinte comando:</p>

```![apelido do arquivo](URL do arquivo)```

<p align="justify">E devem conter uma legenda, para detalhar do que se trata a imagem:</p>


![exemplo](./Imagem.png)<figcaption>Figura 1 - Exemplo de legenda para a imagem.</a></figcaption>

<br>

### Vídeos

<p align="justify"> Em relação à vídeos, eles devem ser adicionados ao documento utilizando o seguinte código:</p>

```<iframe width="1366" height="483" src="https://www.youtube.com/embed/ABzDOSQkhTM" title="Imagens Incríveis da Natureza (4k)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>```

<iframe width="1366" height="483" src="https://www.youtube.com/embed/ABzDOSQkhTM" title="Imagens Incríveis da Natureza (4k)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br></br>

### Arquivos PDF

 <object data="../../docs/politicas/pdf-exemplo.pdf" type="application/pdf" width="700px" height="400px">
<embed src="../../docs/politicas/pdf-exemplo.pdf">
        <p>Esse navegador não suporta arquivos em PDF. Por favor, faça o download do arquivo para visualizar: <a href="../../docs/politicas/pdf-exemplo.pdf">Download PDF</a>.</p>
    </embed>
</object>


 ```<object data="../../docs/politicas/pdf-exemplo.pdf" type="application/pdf" width="700px" height="400px">
<embed src="../../docs/politicas/pdf-exemplo.pdf">
        <p>Esse navegador não suporta arquivos em PDF's. Por favor, faça o download do arquivo para visualizar: <a href="../../docs/politicas/pdf-exemplo.pdf">Download PDF</a>.</p>
    </embed>
</object>
```


<br></br>

## Tabelas

<p align="justify"> A tabelas devem ser estruturadas da seguinte forma: </p>

|Título 1|Título 2|Título 3|
|--------|--------|--------|
|Dado 1.1|Dado 2.1|Dado 3.1|
|Dado 1.2|Dado 2.2|Dado 3.2|
|Dado 1.3|Dado 2.3|Dado 3.3|

<br>

### Tabelas de versionamento

<p align="justify"> Todos os documentos adicionados nesta WIKI devem conter, ao final da página, uma tabela de versionamento contendo as seguintes informações:</p>

+ Data da criação ou alteração do documento (DD/MM/AAAA);
+ Versão do documento, que inicia em 1.0;
+ Descrição da mudança que foi feita no documento;
+ Nome do autor ou autores do documento, com link para a conta do github do referente autor:
    - ```[Nome do autor](Link para a conta do GitHub do autor)```.

<br>

## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|12/07/2022|1.0|Adiciona regras de padronização da WIKI|[Bruna Santos](https://github.com/brunaalmeidasantos), [Damarcones Porto](https://github.com/brunaalmeidasantos), [Itallo Gravina](https://github.com/brunaalmeidasantos)|
