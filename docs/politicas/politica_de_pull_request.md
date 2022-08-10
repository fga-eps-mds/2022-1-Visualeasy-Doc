# Políticas de Pull Request

Para abrir um Pull Request nesse projeto deverá ser utilizado o template de pull request disponibilizado no repositório do projeto. Além disso, os critérios a seguir também devem ser seguidos:

- O _pull request_ deverá possuir pelo menos um _Reviewer_, que será um dos membros do time responsável pelo projeto. É preferível que os reviewers não tenham realizado alterações presentes no pull request.
- O _pull request_ deverá possuir _Assignees_, que são os contribuidores responsáveis pelas alterações realizadas no pull request.
- O _pull request_ deverá possuir _Labels_ relacionadas/similares às labels usadas na issue correspondente. 

## Template
```markdown
### Descrição

Descrições e justificativas a respeito das mudanças que você realizou.

### Tipo de mudança (Marque "x")

- [ ] Correção de bug
- [ ] Nova funcionalidade
- [ ] Documentação

### Issue relacionada

Fix #<número da issue>

### Checklist

- [ ] Li o documento [CONTRIBUTING](https://fga-eps-mds.github.io/2022-1-Visualeasy-Doc/politicas/Contributor%27s_Guide/)
- [ ] Adicionei testes relacionados as minhas mudanças (se necessário)
- [ ] Documentei minhas mudanças (se necessário)
- [ ] Todos os testes estão passando
- [ ] Revisei minhas alterações
- [ ] Resolvi eventuais conflitos

```

No _Template_ acima os trechos necessários devem ser substituídos e os campos adequados marcados. Abaixo está uma descrição de cada tópico assim como as mudanças necessárias:
- Descrição: Uma breve descrição do _pull request_. O texto da descrição deve substituir as instruções presentes.
- Tipo de mudança: A natureza das mudanças do _pull request_. Para marcar basta substituir os espaço entre os colchetes por "x".
- Issue relacionada: A _issue_ relacionada às mudanças que foram adicionadas no _pull request_. Necessário apenas trocar o texto após o "#" pelo número da _issue_.
- Checklist: Uma lista de controle para checar se os requisitos aplicáveis ao _pull request_ foram satisfeitos. A marcação também acontece trocando o espaço por "x".

## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|23/06/2022|1.0|Adiciona políticas de branchs|[itallo Gravina](https://github.com/itallogravina)|
|09/08/2022|1.0|Adiciona template de pull request|[Gabriel Batalha](https://github.com/Gabriel-Azevedo-Batalha)|


