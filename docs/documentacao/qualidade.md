#	Documento de Qualidade

### Objetivo
<p align = "justify"> Este documento objetiva explicitar os critérios, ferramentas e o planejamento da qualidade de código do projeto, esclarecendo o como, quais e porquês das adoções de cada tipo de teste durante o desenvolvimento do produto.</p>

###	Planejamento
<p align = "justify"> Visando uma boa qualidade de código do projeto, alguns padrões de qualidade de corpos de conhecimentos e de normas foram definidos, tanto quanto as ferramentas que serão utilizadas para monitorar essa qualidade. Neste contexto, a qualidade será afirmada através da aplicação de testes unitários, testes estáticos e testes de usabilidade.</p>

### Testes Unitários

<p align = "justify"> A aplicação de testes unitários se dá por meio da implementação de testes da menor parte testável de um programa Para o NodeJS escolhemos o Jest, que é uma framework que permite rodar testes no nodejs de forma simples. Os testes são feitos tanto do escopo das models, como no escopo dos controllers de cada microserviço.</p>

[![jest](images/jest.png)](images/jest.png)

### Testes Estáticos
<p align = "justify">A análise estática de softwares, também conhecida como whitebox, trabalha diretamente com o código. Nesse caso, os componentes são verificados sem que o produto seja executado. No Visualeasy estão sendo usadas ferramentas automatizadas no qual o principal objetivo dessa técnica é identificar erros de programação como práticas ruins, erros de sintaxe, identação entre outros. As ferramenta utilizadas são o o ESLiny e o SonarCloud.</p>

#### ESLint

[![eslint](images/eslint.png)](images/eslint.png)

<p align = "justify">O ESLint é uma ferramenta de análise de código estática para identificar padrões problemáticos encontrados no código JavaScript. As regras no ESLint são configuráveis ​​e regras personalizadas podem ser definidas e carregadas.</p>
<p align = "justify">Para o código em Javascript utilizamos os padrões do linter ESLint 7.10.0 tanto no frontend (Next.js-ReactJS), como no backend (NodeJS).</p>

#### SonarCloud

[![sonarcloud](images/sonarcloud.png)](images/sonarcloud.png)

<p align = "justify">A utilização do Sonarcloud tem como objetivo: Gerar métricas e indicadores técnicos, abrir o resultado de testes para que todo o time tem acesso, e utilizar seus dados para melhora na qualidade de código.</p>

### Testes de Usabilidade

#### Introdução

<p align = "justify">O cumprimento de testes de usabilidade baseia-se na aplicação da técnica de validação utilizada para avaliar um produto ou serviço. Os testes são realizados com usuários representativos do público-alvo. No caso da aplicação Visualeasy, os testes são feitos com o cliente logo após o lançamento das grandes releases.</p>

### Validação do Sistema e Teste de Qualidade em Uso

<p align = "justify">A validação com o cliente está sendo feita semanalmente e uma vez que a aplicação esteja online serão coletados dados de utilização e feedback da utilização do mesmo.</p>

#### Planejamento


### Relatório de Execução e Resultados



### Referências

* Software Quality. Disponível em: [Software Quality](https://asq.org/quality-resources/software-quality#:~:text=Software%20quality%20is%20defined%20as,defect%20management%20and%20quality%20attributes). Acesso em 20 de Julho de 2022.

* Jest.org. Disponível em: [Jest](https://jestjs.io/pt-BR/). Acesso em 20 de Julho de 2022.

* SonarCloud. Disponível em: [Sonarcloud](https://jestjs.io/pt-BR/). Acesso em 20 de Julho de 2022.

* ESLint. Disponível em: [ESLint](https://eslint.org/). Acesso em 20 de Julho de 2022.




## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|14/07/2022|1.0|Adiciona documento de qualidade do projeto|[Bruno Nunes](https://github.com/brunocmo), [Marcos Vinicius](https://github.com/marcos-mv)