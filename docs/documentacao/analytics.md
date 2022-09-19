# Documento de Analytics

### Objetivo
<p align = "justify"> Este documento mostra por meio de analise de dados do sonarcloud e com auxilio do notebook da matéria, como está o andamento do time em relação ao padrão de qualidade do qRapids.</p>

### Repositório Controle
<p align = "justify"> Abaixo podemos observar na cor laranja a reta que indica a confiabilidade do código, onde se manteve fixo no valor mais alto possível. E na cor azul, podemos observar a manutenibilidade do código que teve seu aprimoramente e depois seu decremento, pelo fato da métrica m2, onde houve a retirada de muitos comentários do código fonte. De verde podemos ver a soma das duas medidas de qualidade.</p>

[![controle](images/controleTotal.png)](images/controleTotal.png)

### Repositório Frontend
<p align = "justify"> Na imagem podemos observar na cor laranja a reta que indica a confiabilidade do código, tendo discrepancias ao passar do tempo, sendo que seu valor mais baixo, deve-se ao problema relacionado as falhas de testes inesperadas, porem foram corrigidas aumentando então seu valor. E na cor azul, podemos observar a manutenibilidade do código que teve um aumento no começo devido a métrica m2, e depois ficou fixo no valor de 0,33. De verde podemos ver a soma das duas medidas de qualidade.</p>

[![fronend](images/fronendTotal.png)](images/fronendTotal.png)

### Qualidade agregada
<p align = "justify"> Abaixo, exibi-se o valores do indicador caracteristico de qualidade agregada. Sendo que o repositório que obteve mais numeros de versões foi o Frontend. E ele em compração com o outro repositório, podemos analisar pouca discrempancia nos valores de manutenibilidade. Já na confiabilidade, observa-se uma grande discrepancia dos valores, com o desvio padrão alcançando valores mais altos do que esperado, devido a oscilação dessa qualidade.</p>

[![agregado](images/agregado.png)](images/agregado.png)

### Valores obtidos na planilha

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT_IGIEg2fVanXRPbyhs54cgEKox27sbYhURNjtt3HmOHfhR7xCBj8K4yOnNkl0aQ/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"width="100%" height="229px"></iframe>



## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|19/09/2022|1.0|Adiciona documento de analytics|[Bruno Nunes](https://github.com/brunocmo)

