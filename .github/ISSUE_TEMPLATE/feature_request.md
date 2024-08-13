---
name: Feature request
about: Suggest an idea for this project
title: "[STORY]"
labels: documentation, enhancement
assignees: ''

---

1. No título, se a tarefa for muito grande e precisar ser quebrada em tarefas menores, é bom colocar `[STORY]` no início do título.
2. Adicione as tags de acordo com a tarefa (cada tag tem a descrição devida).
	a. Se a tarefa for para um aparelho específico, adicionar a tag do SO.
3. Preencha as seguintes seções:

## O quê?
Explicar o que será feito (seja no código, fluxo ou desenho) na tarefa de uma maneira geral.

### Imagens
Se hover imagens, usa-se a tag `details` do html. Exemplo:
```
<details>
<summary>Nome exemplo</summary>

Adicionar aqui a imagem
</details>
```

<details>
<summary>Nome exemplo</summary>

Adicionar aqui a imagem
</details>

## Por que?
Qual o motivo de essa tarefa existir? Qual a importância dela?

## Como?
Nesta seção, tudo depende do quão grande a tarefa é. Por exemplo, se ela for muito grande e precisa ser dividida em várias outras, é necessário que se criem outras tarefas para complementar esta:
- [ ] Adicionar aqui a tag/link da tarefa a ser rastreada
- [ ] Aqui também

Com essa função, quando a tarefa estiver fechada, o rastreio automaticamente estará completo.
Se a tarefa for menor e não precisar ser dividida, poderá ser escrito apenas as tasks a serem feitas:
- [ ] Tarefa 1
- [ ] Tarefa 2
