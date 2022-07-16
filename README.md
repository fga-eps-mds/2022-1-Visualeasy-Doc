# 2022-1-Squad7

## Sobre

O Visualeasy é uma aplicação Web que fornece uma visualização gráfica de métricas históricas de variáveis de produção. 

O projeto é desenvolvido por alunos de gadruação em engenharia de Software da Universidade de Brasília - do Campus do Gama (FGA) - para a disciplina de Engenharia de Produto de Software (EPS).

A aplicação Visualeasy proporciona a visualização de dados de forma gráfica ao longo do tempo, para auxiliar na tomada de decisões.

## Informações Complementares 

### Para publicação no gh-pages

1 - Use o comando:

```pip install mkdocs```

2 - Para verificar se tudo deu certo, execute esse comando:

```mkdocs --version```

Deve estar na versão: version 1.2.2

3 - Após a instalação do mkdocs, é preciso instalar o nosso tema, utilizando o comando:

```pip install mkdocs-material```

```pip install mkdocs-awesome-pages-plugin```

4 - Para iniciar a página de documentação do projeto, entre no local onde a pasta do projeto foi clonada e execute o comando:

```mkdocs serve```

5 - Para realizar o deploy das suas mudanças nos documentos, verifique se não existe nenhuma divergência na main realize o push e depois utilize o comando dentro da branch main:

```mkdocs build```


 e depois o comando

```mkdocs gh-deploy``` 

