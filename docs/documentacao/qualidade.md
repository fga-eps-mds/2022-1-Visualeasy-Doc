# Documento de Qualidade

### Objetivo
<p align = "justify"> Este documento objetiva explicitar os critérios, ferramentas e o planejamento da qualidade de código do projeto, esclarecendo o como, quais e porquês das adoções de cada tipo de teste durante o desenvolvimento do produto.</p>

###	Planejamento
<p align = "justify"> Visando uma boa qualidade de código do projeto, alguns padrões de qualidade de corpos de conhecimentos e de normas foram definidos e também as ferramentas que serão utilizadas para monitorar essa qualidade. Neste contexto, a qualidade será afirmada através da aplicação de testes unitários, testes estáticos e testes de usabilidade.</p>

<br>

## <b>Testes Unitários</b>

<p align = "justify"> A aplicação de testes unitários se dá por meio da implementação de testes da menor parte testável de um programa Para o NodeJS escolhemos o Jest, que é uma <em>framework</em> que permite realizar testes no nodejs de forma simples. Os testes são executados tanto no escopo das models, como no escopo dos controllers de cada microsserviço.</p>

[![jest](images/jest.png)](images/jest.png)

<br>

## <b>Testes Estáticos</b>
<p align = "justify">A análise estática de <em>softwares</em>, também conhecida como whitebox, trabalha diretamente com o código. Nesse caso, os componentes são verificados sem que o produto seja executado. No Visualeasy estão sendo usadas ferramentas automatizadas onde o principal objetivo dessa técnica é identificar erros de programação como práticas ruins, erros de sintaxe, identação entre outros. As ferramentas utilizadas serão o o ESLiny e o SonarCloud.</p>

### ESLint

[![eslint](images/eslint.png)](images/eslint.png)

<p align = "justify">O ESLint é uma ferramenta de análise de código estática para identificar padrões problemáticos encontrados no código JavaScript. As regras no ESLint são configuráveis ​​e regras personalizadas podem ser definidas e carregadas.</p>
<p align = "justify">Para o código em Javascript utilizamos os padrões do linter ESLint 7.10.0 tanto no frontend (Next.js-ReactJS), como no backend (NodeJS).</p>

<br>

### SonarCloud

[![sonarcloud](images/sonarcloud.png)](images/sonarcloud.png)

<p align = "justify">A utilização do Sonarcloud visa: Gerar métricas e indicadores técnicos, abrir o resultado de testes para que todo o time tenha acesso, e utilizar seus dados para melhora na qualidade de código.</p>

<br>




## <b>Testes de Usabilidade</b>

### Introdução

<p align = "justify">A execução de testes de usabilidade baseia-se na aplicação da técnica de validação utilizada para avaliar um produto ou serviço. Os testes são realizados com usuários representativos do público-alvo. No caso da aplicação Visualeasy, os testes serão efetuados com o cliente logo após o lançamento de cada <i>Release</i>, durante a aplicação dos formulários para validação.</p>

### Planejamento

<p align = "justify">Os testes de usabilidade serão feitos juntamente com a da validação de novas funcionalides com os clientes, durante as releases lançadas nas reuniões semanais com os <i>POS</i> do VisualEasy; e, uma vez que a aplicação esteja online, serão coletados dados de utilização e <i>feedback</i> sobre a aplicação por parte do cliente.</p>

<p align = "justify">O formulário de validação das Histórias de Usuário irá abordar, além de questões para o usuário validar cada uma das USs concluídas, perguntas padronizadas acerca da usabilidade de cada funcionalidade implementada e apresentada na Release.</p>

### Roteiro de perguntas

<p align = "justify">Cada seção do formulário, que corresponde a uma USs a ser validada, conterá as seguintes perguntas:</p>

|ID|Pergunta|Tipo de resposta|
|--|--------|----------------|
|01|Siga as instruções e marque as opções que conseguiu realizar.|Serão apresentadas ao usuário uma lista de passos que ele deve seguir para testar a funcionalidade que deve ser validada.|
|02|Em relação à US00, em uma escala de 1 a 5, onde 1 significa "Muito insatisfeito" e 5 "Muito Satisfeito" marque a opção que mais se adequa à sua satisfação.|Escala de 1 a 5.|
|<b>03</b>|Qual a sua opinião sobre a navegação para completar a tarefa referente à US00?|Resposta livre.|
|<b>04</b>|Teve alguma dificuldade em realizar os passos indicados na 1ª questão? Se sim, qual?|Resposta livre.|
|<b>05</b>|Como se sentiu ao realizar a tarefa?|Checklist com as opções: satisfeito, confuso, decepcionado|
|<b>06</b>|Justifique sua resposta em relação à questão anterior.|Resposta livre.|
|<b>07</b>|A funcionalidade condiz com a sua expectativa como usuário?|Resposta livre.|
|08|Comentários e observações sobre a US03.|Resposta livre.|
|09|Caso deseje, insira alguma imagem para complementar o feedback a respeito da validação da US03|Campo para fazer <i>upload</i> de imagens.|

<p align = "justify">As perguntas com a coluna "ID" em negrito são referentes ao teste de usabilidade.</p>


### Execução dos testes

<p align = "justify">Os resultados dos formulários de validação das Histórias de Usuário, incluindo as perguntas referentes aos testes de usabilidade, serão descritos no <a href="https://fga-eps-mds.github.io/2022-1-Visualeasy-Doc/documentacao/relatorio-qualidade/">Relatório de resultados dos formulários de validação das Histórias de Usuário</a>.</p>


<br>
<br>

### Referências

+ ASQ. <b>What is Software Quality?</b> Disponível em: [asq.org](https://asq.org/quality-resources/software-quality#:~:text=Software%20quality%20is%20defined%20as,defect%20management%20and%20quality%20attributes). Acesso em 20 de Julho de 2022.

+ Jest.org. <b>JEST</b>. Disponível em: [jestjs.io](https://jestjs.io/pt-BR/). Acesso em 20 de Julho de 2022.

+ SonarCloud. <b>SonarCloud</b>. Disponível em: [sonarcloud.io](https://sonarcloud.io/). Acesso em 20 de Julho de 2022.

+ ESLint.org. <b>ESLint</b>. Disponível em: [eslint.org](https://eslint.org/). Acesso em 20 de Julho de 2022.



## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|14/07/2022|1.0|Adiciona documento de qualidade do projeto|[Bruno Nunes](https://github.com/brunocmo), [Marcos Vinicius](https://github.com/marcos-mv)
|25/07/2022|1.1|Revisão ortográfica do documento| [Gustavo Moreira](https://github.com/gustavoduartemoreira)
|14/08/2022|1.2|Refatora tópico de testes de Qualidade em Uso|[Bruna Santos](https://github.com/brunaalmeidasantos), [Damarcones Porto](https://github.com/damarcones)|
|15/08/2022|1.3|Revisão ortográfica do documento|[Damarcones Porto](https://github.com/damarcones)|
