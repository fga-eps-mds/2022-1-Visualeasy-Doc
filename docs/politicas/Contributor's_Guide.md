# Contributor's Guide

'COMO CONTRIBUIR PARA O CÓDIGO ABERTO' aceite PR's (pull requests) somente de **novatos**. Isso é uma ajuda para **novatos** familiariza-se com o processo de contribuição.

Issues podem ser submetidas por qualquer pessoa - desenvolvedores experientes ou novatos    .

**Conteúdo**

- [Começando](#getting-started)
- [Submetendo um Pull Request](#submitting-a-pull-request)
- [Adicionando o README na Main](#adding-to-the-main-readme)
- [Adicionando um README traduzido](#adding-to-non-english-readme)
- [Adicionando arquivos do projeto](#adding-to-the-project-file)
- [Recursos Úteis](#helpful-resources)

### Começando

1.  Se você é novo no GIT ou Github, é recomendado que veja
    [GitHub para iniciantes](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1/)
    **antes** de ir para o passo 2.

2.  Fork o projeto no GitHub.
    [Guia de ajdua para Fork de repositório](https://help.github.com/en/articles/fork-a-repo/).

    ![Illustration for How to Fork a Repository](https://hisham.hm/img/posts/github-fork.png)

3.  Clone do projeto.
    [Guia de ajuda para clonar um repositório](https://help.github.com/en/articles/cloning-a-repository)

4.  Criar uma branch(ramo) para a issue que está trabalhando.

    ```shell
    git checkout -b update-readme-file
    ```

    Para clareza, nome de sua branch `atualizacao-xxx` ou `correcao-xxx`. O `xxx` é uma descrição curta das mudanças que está fazendo. Examplo incluir `atualizacao-readme` ou
    `correcao-ortografica-na-contribuicao-md`.

5.  Abra o projeto no seu editor de textp favorito, selecione o arquivo que fará a contribuição, e faça suas alterações.

    Se estiver fazendo alterações no arquivo `README.md`, teria que ter conhecimento em Markdown. Visite
    [aqui para ler sobre GitHub Markdown](https://guides.github.com/features/mastering-markdown/)
    e
    [aqui para praticar](http://www.markdowntutorial.com/).

    * Se está adicionando um novo projeto/organização ao README, tenha certeza de listar em ordem alfabética

    * Se está adicionando uma nova organização. tenha certeza de adicooonar um tórtulo de organização ao nome da organização. Isso ajudará a diferenciar projetos de organizações.
    
6.  Adicionando suas modificações no Git, [Como fazer Add, Commit, Push, e Go](http://readwrite.com/2013/10/02/github-for-beginners-part-2/).

    ```shell
    git add path/to/filename.ext
    ```

    Você pode adicionar todos os arquivos usando:

    ```shell
    git add .
    ```

    **Note:** usando o  `git add .`  irá automaticamente adicionar todos os arquivos. Vocẽ pode fazer um 
    `git status` para ver suas alterações, mas **antes** do `git add`.

6.  Commit suas mudanças usando um comentários descritivo.

    ```shell
    git commit -m "Breve descricao do Commit"
    ```

7.  Push seus commit para o Fork do GitHub:

    ```shell
    git push -u origin branch-nome
    ```

8.  Submeta um pull request.

    Dentro do GitHub, visite o repositório E deve procurar a sugestão de como realizar um pull request. Enquanto está escrevendo o pull request, você pode adicionar `Closes #XXX` no corpo da mensagem `#XXX` é a issue que você resolveu. Portanto, um exemplo seria `Closes #42` a issue
    `#42` é fechada.

### Submetendo um Pull Request

[O que é um Pull Request?](https://yangsu.github.io/pull-request-tutorial/)

Se você decide resolver uma issue, é aconselhável verificar o tópico de comentários para saber se outra pessoa não está resolvendo a mesma issue. Se ninguém estiver trabalhando nela, deixe um comentário sinalizando que pretende trabalhar. FAzendo isso, outras pessoas não farão trabalho duplicado acidentalmente.

Em uma situação que alguém decide resolver uma issue mas não continua por um período de tempo, de 2 ou 3 semanas, é aceitável pegar essa issue, mas faça um cometário dizendo que tem essa intenção.

*Nota*: Todo projeto de código-aberto tem um arquivo **CONTRIBUTING.md**, por favor tenha a certeza de ler antes de subir um pull request; caso contrário, ele pode ser rejeitado. No entanto, se não encontrou um arquivo CONTRIBUTING.md, você pode enviar o pull request mas de uma maneira descritiva.

### Adicionando o README a página principal

O
[arquivo `README.md` da página principal](https://github.com/freeCodeCamp/how-to-contribute-to-open-source/blob/master/README.md) uma lista de recursos úteis para iniciantes que querem contribuir para um porjeto de código-aberto.



Você pode contribuir para está página adicionando um link Markdown-formatado.

É algo similar ao exemplo abaixo.


```
- [Title of the page](www.websitename.com/slug-name-here) - Add a description of why I should look at this site
```

Se estiver em dúvida, pode olhar a lista de itens submetidos para saber como é formatada as contribuições.


### Recursos úteis

- [Pro GIT Book](https://git-scm.com/book/en/v2)

- [Try Git](https://try.github.io/)

- [Git/ Git Hub on Windows](https://www.youtube.com/watch?v=J_Clau1bYco)
