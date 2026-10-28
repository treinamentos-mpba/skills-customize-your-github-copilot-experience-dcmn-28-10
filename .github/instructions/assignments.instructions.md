---
description: "Instruções para usar sempre que criar ou editar arquivos markdown de assignment, garantindo consistência e clareza para os alunos."
applyTo: "assignments/**/*.md"
---

# Diretrizes de Estrutura para Markdowns de Tarefas

Todos os arquivos markdown de tarefas devem seguir estas diretrizes:

## 1. Uso do Template

- Os arquivos markdown de tarefas devem seguir a estrutura em [`templates/assignment-template.md`](../../templates/assignment-template.md).
- A tarefa deve ser criada como um arquivo `README.md`
- Preserve as seções obrigatórias e a ordem definida pelo template. A quantidade de tarefas pode variar conforme o escopo do exercício.

## 2. Orientação das Seções

Use os cabeçalhos exatamente como aparecem no template, incluindo os ícones emoji:

- `# 📘 Atividade: [Título da Atividade]` — Use um título curto e descritivo para o exercício.
- `## 🎯 Objetivo` — Resuma em 1 ou 2 frases o que o aluno aprenderá ou construirá.
- `## 📝 Tarefas` — Inclua uma ou mais tarefas. Para cada uma, use esta estrutura:
   - `### 🛠️ [Título da Tarefa]` — Escolha um título específico e orientado à ação.
   - `#### Descrição` — Explique claramente o que o aluno deve fazer.
   - `#### Requisitos` — Inclua a frase `O programa concluído deve:` e liste os resultados esperados em tópicos específicos e verificáveis.

Use exemplos de entrada e saída em blocos de código quando ajudarem a esclarecer o resultado esperado. Escreva o conteúdo em português, mantendo em inglês identificadores, comandos e textos de saída quando fizerem parte do exercício. Não inclua seções extras além das previstas no template, a menos que sejam solicitadas.