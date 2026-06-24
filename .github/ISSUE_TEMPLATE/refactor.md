---
name: Tarefa Técnica / Refatoração 🔧
about: Sugira uma melhoria na estrutura do código, performance ou organização.
title: '[REFACTOR] '
labels: refactoring, technical debt
assignees: ''
---

**Qual é o alvo da refatoração?**
Indique qual ficheiro, função ou módulo precisa de ser melhorado.

**Por que essa mudança é necessária?**
Explique o benefício técnico. Ex: "Melhorar a legibilidade do código, reduzir o uso de memória, facilitar testes futuros, etc."

**O que deve ser feito?**
- [ ] Criar um ficheiro separado para...
- [ ] Mudar o tipo da variável de... para...
- [ ] Remover código comentado / inutilizado.

**📋 Critérios de Aceite (Condições para Conclusão):**
- [ ] O código deve compilar sem novos erros ou avisos (warnings).
- [ ] O comportamento externo do sistema **não deve** ter sofrido qualquer alteração (o dispositivo/software tem de fazer exatamente o mesmo que fazia antes).
- [ ] (Opcional) A métrica de performance ou memória visada deve apresentar melhoria comprovada (ex: menor consumo de RAM).

**Impacto esperado**
Existem riscos de quebra de compatibilidade com outras partes do sistema? Se sim, quais?