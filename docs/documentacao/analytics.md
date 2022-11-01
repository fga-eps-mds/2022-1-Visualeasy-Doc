# Documento de Analytics
 
### Objetivo
<p align = "justify"> Este documento mostra por meio de análise de dados do sonarcloud e com auxílio do notebook da matéria, como está o andamento do time em relação ao padrão de qualidade do qRapids.</p>
 
### Repositório Controle
<p align = "justify"> Abaixo podemos observar na cor laranja a reta que indica a confiabilidade do código, onde se manteve fixo no valor mais alto possível. E na cor azul, podemos observar a manutenibilidade do código que teve seu aprimoramento e depois seu decremento, pelo fato da métrica m2, onde houve a retirada de muitos comentários do código-fonte. De verde podemos ver a soma das duas medidas de qualidade.</p>
 
[![controle](images/controleTotal.png)](images/controleTotal.png)
 
### Repositório Front-end
<p align = "justify"> Na imagem podemos observar na cor laranja a reta que indica a confiabilidade do código, tendo discrepâncias ao passar do tempo, sendo que seu valor mais baixo, deve-se ao problema relacionado as falhas de testes inesperadas, porém foram corrigidas aumentando então seu valor. E na cor azul, podemos observar a manutenibilidade do código que teve um aumento no começo devido à métrica m2, e depois ficou fixo no valor de 0,33. De verde podemos ver a soma das duas medidas de qualidade.</p>
 
[![fronend](images/fronendTotal.png)](images/fronendTotal.png)
 
### Qualidade agregada
<p align = "justify"> Abaixo, exibe-se os valores do indicador característico de qualidade agregada. Sendo que o repositório que obteve mais números de versões foi o Front-end. E em comparação com o outro repositório, podemos analisar pouca discrepância nos valores de manutenibilidade. Já na confiabilidade, observa-se uma grande discrepância dos valores, com o desvio padrão alcançando valores mais altos do que esperado, devido à oscilação dessa qualidade.</p>
 
[![agregado](images/agregado.png)](images/agregado.png)
 
### Valores obtidos na planilha
 
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT_IGIEg2fVanXRPbyhs54cgEKox27sbYhURNjtt3HmOHfhR7xCBj8K4yOnNkl0aQ/pubhtml?gid=1972720110&amp;single=true&amp;widget=true&amp;headers=false"   width="100%" style="height: 80vh;"></iframe>
 
 
## Avaliação Notebook

### 1) Qual é o microsserviço de backend que apresenta o pior indicador de manutenabilidade e o que foi feito pela equipe do Visualeasy para melhorá-lo?
O projeto do Visualeasy foi planejado e desenvolvido com apenas 1 microsserviço de backend, o microsserviço chamado de Controle. Consequentemente, é ele que apresenta o pior indicador de manutenabilidade. 

A equipe identificou e se propôs a tentar melhorar o indicador dessa métrica após a entrega da release 5. Porém, houve um erro de interpretação da equipe sobre qual o número ideal que deveria estar nessa métrica. 

A equipe aplicou algumas refatorações retirando os comentários presentes no código, o que levou a métrica ao valor 0, onde acreditávamos ser o ideal. Entretanto, apenas após a entrega, foi compreendido pela equipe que o ideal seria entre manter 10% a 30% de comentários no código.
 
### 2) No microsserviço que apresentar o pior indicador de confiabilidade, mostre qual(is) o(s) módulos/arquivos mais críticos e explique como a equipe do Visualeasy tratou esse problema.

O microsserviço do nosso projeto que apresentou o pior indicador de confiabilidade, foi o Frontend. E dentro desse microsserviço, o diretório /src/pages/components/FormGraph contém o arquivo mais crítico do nosso projeto. 

Esse arquivo contém a funcionalidade principal do nosso produto, portanto, aconteceram muitas modificações, importações de outros arquivos menores, geração de bugs e erros, e por falta de conhecimento da equipe sobre como renderizar os testes, os testes ficaram reduzidos para esse arquivo. 

Por fim, a equipe tentou melhorar e aumentar a cobertura de testes para esse arquivo, porém não gerou tanto resultado.
 
### 3) Explique o comportamento da qualidade do produto observada ao longo do tempo de desenvolvimento do projeto.

Analisando a qualidade do produto podemos dizer que, em relação ao microsserviço Controle, houve uma estabilidade nas métricas durante o todo o projeto, com um desvio padrão pequeno, onde o mínimo foi 0,75 e o máximo 0,88. Isso foi resultado da utilização de TDD durante o desenvolvimento do projeto.

Porém, em relação ao microsserviço Frontend, esse desvio padrão foi bem mais alarmante durante o projeto. Houve uma queda drástica da métrica relacionada a confiabilidade do produto, principalmente entre a versão 0.4 e 0.5, alarmando a equipe sobre a qualidade do produto. Após a análise da razão dessa queda, foi constatado que o motivo foi uma atualização de uma ferramenta utilizada para desenvolvimento do produto, gerando uma queda na porcentagem de cobertura de testes do microsserviço. Então a equipe dedicou esforços para refatorar o código e aumentar a cobertura de testes, tendo esse objetivo concluído na geração da última versão do produto.

Por fim, pode-se concluir que a qualidade do produto se manteve em um intervalo aceitável durante boa parte do projeto, saindo apenas durante um curto período, mas logo após o problema foi resolvido pela equipe, resultando em um produto final com uma qualidade satisfatória.
 
## Versionamento
 
| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|19/09/2022|1.0|Adiciona documento de analytics|[Bruno Nunes](https://github.com/brunocmo)
|19/09/2022|1.1|Revisão e Correção ortográfica|[Marcos Vinícius](https://github.com/marcos-mv)
|19/09/2022|1.2|Ajuste de visualização|[Damarcones Porto](https://github.com/damarcones)
|31/10/2022|1.3|Adição da avaliação do analytics|[Bruno Nunes](https://github.com/brunocmo)
 

