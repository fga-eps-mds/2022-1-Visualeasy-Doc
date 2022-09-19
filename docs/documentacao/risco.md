# Gerenciamento de Riscos
 
Amplamente divulgado através do PMBOK, o Gerenciamento de Riscos propõe a identificação de riscos e planos de ação para mitigá-los, eliminá-los, ou mesmo transferi-los. Dentre eles enfatizamos os seguintes:
 
- Riscos de Projeto.
- Riscos Técnicos.
- Riscos Externos.
- Riscos de Produto.
 
Cada um dos riscos acima foram subdivididos nos subtópicos abaixo:
 
 
## Riscos de Projeto
 
| Riscos | Consequência |Contigência|
|--------|--------------|-----------|
| Indefinição do escopo | Alteração no planejamento e andamento das sprints | Definir o escopo|
| Mudança do escopo | Alteração no planejamento e andamento das sprints |Organizar novamente as sprints|
| Imaturidade da gerência | Planejamentos falhos, falta de qualidade, aumento do custo e tempo do projeto, entre outros | Trocar a gerência|
| Alteração na arquitetura | Gera retrabalho, alteração nas histórias planejadas, mudança de infraestrutura e código | Análisar se é a melhor alternativa mudar arquitetura |
| Comunicação não eficiente do grupo | Falhas de desenvolvimento, perda de informação e retrabalho | Estruturar um padrão de comunicação no time| 
| Baixa produtividade dos integrantes  | Risco para o planejamento e aumento de tarefas não concluídas | Reorganização das tarefas e em último caso, retirada de membros que atrapalham o time|
| Divergência de horários entres os membros | Risco para o planejamento e aumento de tarefas não concluídas | Tentar alocar aqueles com horários compatíveis e os que não tem trabalham individualmente|
| Dificuldades na integração do time | Risco para o planejamento e aumento de tarefas não concluídas |Procurar divergências para soluncionar e novas técnicas de entrosamento|
| Saída de membro do grupo | Sobrecarga e desgaste dos demais membros do grupo | Redisbuição de tarefas de acordo com afinidade de conteúdo|
| Falta de dedicação em atividades | Risco para o planejamento e aumento de tarefas não concluídas |Reuniões para motivar o time|
| Atividades atrasadas | Risco para o planejamento e aumento de tarefas não concluídas | Procurar o motivo dos atrasos e solucionar|
| Atividades secundárias dos membros | Risco para o planejamento e aumento de tarefas não concluídas |Encaixar os horários disponíveis dos membros na agenda do time| 
 
## Riscos Técnicos
 
| Riscos | Consequência |Contingência|
|--------|--------------|------------|
| Falta ou falha de equipamentos | Prejudica o planejamento e atrasa as entregas |Buscar novos equipamentos assim que constatado o problema|
| Dificuldade com versionamento (git) | Inviabiliza o desenvolvimento do projeto |Treinamento de git para os membros com dificuldade|
| Adaptação da equipe com as tecnologias | Prejudica o planejamento e atrasa as entregas |Treinar toda a equipe no uso das ferramente (Dojô)
 
## Riscos Externos
 
| Riscos | Consequência |Contigência|
|--------|--------------|-----------|
| Questões burocráticas | Pode inviabilizar o andamento do projeto |Resolver as questões burocráticas antes de dar início ao projeto|
| Indisponibilidade do cliente para validação do produto | Dificuldade de validação do produto |Trabalhar naquilo que não precise de validação ou interromper a produção justificando o motivo para o cliente.
 
 
## Riscos de Produto
 
| Riscos | Consequência |Contigência|
|--------|--------------|-----------|
| Produto não atende às necessidades do cliente | Projeto falho e inutilizável |Refatorar requisitos e reescrever escopo|
| Complexidade de codificação | Dificuldade na prestação de manutenção e correção de bugs |Refatorar o código para verificar se a complexidade está correta|
| Estabilidade do produto | Não atender às expectativas do cliente |Aplicar testes ou refatorar o produto
| Falta de especificação de teste | Cobertura insuficiente de possíveis problemas e inviabilização da utilização do produto | Aumentar a cobertura de testes ou criar testes mais robustos
 
 
## Visualização Riscos
 
### Classificação dos Riscos
 
O grau dos riscos é definido pela multiplicação da probabilidade de ocorrência, pelo impacto dos mesmos, causados ao projeto.
 
As classificações de risco foram definidas da seguinte forma:
 
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vR7kctCU30z6PdOfWeeuDTmj6d1ol2pdk5jSt0oaa7NFsXvE2IvJGgmACh7EWpmEtqUw0DB_zInGMLs/pubhtml?gid=1432428913&amp;single=true" width="81%" height="255px"></iframe>
 
### Quadro de Riscos
 
Seguindo um dos pilares do Scrum que diz respeito à transparência, e do PMBOK  a respeito do monitoramento e gerenciamento de riscos, os riscos serão mapeados rigorosamente (e pontuados) e podem ser vistos na tabela abaixo:
 
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vR7kctCU30z6PdOfWeeuDTmj6d1ol2pdk5jSt0oaa7NFsXvE2IvJGgmACh7EWpmEtqUw0DB_zInGMLs/pubhtml?gid=0&amp;single=true" width="100%" height="680px"></iframe>
 
 
### *Burndown* de Riscos
 
As informações coletadas durante a avaliação de risco podem ser usadas para criar um Gráfico de *Burndown* de Risco. Ele descreve os riscos identificados no projeto, os monitora analisando seus respectivos impactos e probabilidade de ocorrência ao longo do período de desenvolvimento do projeto.
 
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vR7kctCU30z6PdOfWeeuDTmj6d1ol2pdk5jSt0oaa7NFsXvE2IvJGgmACh7EWpmEtqUw0DB_zInGMLs/pubhtml?gid=403121833&amp;single=true" width="100%" height="900px"></iframe>
 
### Velocity
 
Tem como objetivo verificar a média de pontos que o grupo consegue entregar por sprint. Quanto mais alta for essa medida, maior a produtividade e, consequentemente, maior capacidade de desenvolvimento da equipe. Ele será elaborado ao fim de cada sprint e é consultado no planejamento da sprint seguinte.

<iframe width="100%" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRRcmGp2J8hwLAXFNeJDz2b5BkdsILm8dHGXEYWs7wMwuaS7_SRj1xRsOxQAPmigh9CxTXc3OTHbjDj/pubchart?oid=1763211652&amp;format=interactive"></iframe>
 
### Referências
 
+ GitHub. <b>Bot Lino</b>. Disponível em [github.com/BotLino/Lino](https://github.com/BotLino/Lino). Acesso em 14 de julho de 2022.

+ Gerenciamento de riscos em projetos ágeis - Cultura Ágil. Disponível em [Cultura Ágil](https://www.culturaagil.com.br/gerenciamento-de-riscos-em-projetos-ageis/). Acesso em 14 de julho de 2022.

+ Devmedia. <b>Visão da gerência de riscos na engenharia de software</b>. Disponível em [devmedia.com](https://www.devmedia.com.br/visao-da-gerencia-de-riscos-na-engenharia-de-software/9144#:~:text=%C2%A7%20Riscos%20de%20Produto%20de,codifica%C3%A7%C3%A3o%20e%20especifica%C3%A7%C3%A3o%20de%20testes.). Acesso em 14 de julho de 2022.

+ PMBOK. <b>Project Management Body of Knowledge</b>. Disponível em [PMBOK](https://web.archive.org/web/20200701142517/http://itq.ch/pdf/pmbok1.pdf). Acesso em 14 de julho de 2022.
 
 
## Versionamento
 
| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|14/07/2022|1.0|Adiciona riscos do projeto|[Bruno Nunes](https://github.com/brunocmo), [Marcos Vinicius](https://github.com/marcos-mv)
|10/08/2022|2.0|Adiciona contigências|[Damarcones Porto](https://github.com/damarcones)
|29/08/2022|3.0|Atualização e adição de gráficos|[Marcos Vinícius](https://github.com/marcos-mv)
|11/09/2022|4.0|Atualização de Gráfico do Velocity|[Marcos Vinícius](https://github.com/marcos-mv)
 
 

