# Introdução

O **Markdown** é uma linguagem de marcação simples para formatar textos de maneira rápida e legível. No GitHub, ele é amplamente usado para:

- Arquivos `README.md`
- Documentação de projetos
- Anotações técnicas 
- Relatórios de atividades  
- Instruções de instalações 
- Registros de aulas
- ISSUES e Pull Requests

#### **A extensão do arquivo Markdown é ".md"**

---

# 1. O que é Markdown?

O Markdown permite aplicar formatação simples em um texto usando caracteres comuns.

### Exemplo de código:
```markdown
# Meu projeto

#### Este projeto foi desenvolvido durante a aula de **Versionamento de código**

## Tecnologias 
- Git
- GitHub
- VS Code
```

### Como o conteúdo será apresentado no GitHub:

# Meu projeto

#### Este projeto foi desenvolvido durante a aula de **Versionamento de código**

## Tecnologias 
- Git
- GitHub
- VS Code

*No GitHub, esse conteúdo será apresentado de forma formatada com título, texto em negrito e lista.*

---

# 2. Criando um arquivo Markdown

No Visual Studio Code:
1. Abra a pasta do projeto.
2. Clique em **"New File"** (Novo Arquivo).
3. Informe o nome do arquivo com a extensão desejada.

**Exemplo:** `README.md`

Para projetos de aulas, também podem ser utilizados nomes como:
- `semana-01.md`
- `semana-02.md`
- `aula-01.md`

## Boas Práticas de Nomenclatura

Prefira nomes:
- Curtos
- Descritivos 
- Escritos em letras minúsculas 
- Sem acentos
- Sem espaços
- Separados por hífen quando necessário

### Recomendado:
- `resumo-git.md`
- `aula-01.md`
- `comandos-git.md`

### Evite:
- `Resumo Git.md`
- `Aula 01.md`
- `Atividade Prática GitHub.md`
- `Meu Arquivo Novo.md`

---

# 3. Títulos e Subtítulos

O Markdown utiliza o caractere `#` para criar títulos.

```markdown
# Título principal (H1)
## Título nível 2 (H2)
### Título nível 3 (H3)
#### Título nível 4 (H4)
##### Título nível 5 (H5)
```

## Boa Prática: Utilize uma estrutura hierárquica

### Exemplo Correto:
```markdown
# Semana 08 - Introdução ao Git
## Objetivos da aula
## Conceitos aprendidos
### Repositório
### Commit
### Branch
### Atividade Prática
## Conclusão
```

### Evite pular níveis sem necessidade, como:
```markdown
# Título Principal
### Subtítulo (Pulando o H2)
```

---

# 4. Parágrafos

Para criar um parágrafo, basta deixar uma linha em branco entre os textos.

```text
Git é um sistema de controle distribuído.

Ele permite registrar e acompanhar alterações realizadas nos arquivos de um projeto.
```

---

# 5. Negrito

Utilize 2 asteriscos `**` antes e depois da palavra: `**texto em negrito**`

> O **Git** é um sistema de controle de versão.

---

# 6. Itálico

Utilize 1 asterisco `*` antes e depois da palavra: `*texto em itálico*`

> O comando *git status* permite verificar o estado do repositório. *(Nota: para representar comandos, o ideal é utilizar a formatação de código em linha com crases, como: `git status`).*

---

# 7. Negrito e Itálico

Utilize 3 asteriscos `***` antes e depois da palavra:

```markdown
***Texto em negrito e em itálico***
```

> ***Git add***

---

# 8. Listas Não Ordenadas

Utilize um hífen `-` ou asterisco `*` antes de cada item:

- Git 
- GitHub
- Visual Studio Code

### Criando subníveis (recue com 4 espaços ou 1 tabulação):
- Git
    - Commit
    - Branch
    - Merge
- GitHub
    - Repositório
    - Pull Request
    - Issues

## Boa Prática
Utilize listas para representar de forma clara:
- Conceitos
- Requisitos
- Tecnologias
- Etapas
- Recursos

---

# 9. Listas Numeradas

Utilize o número seguido de um ponto:

1. Criar o repositório
2. Adicionar os arquivos
3. Criar o commit
4. Enviar para o GitHub

*Ideal para procedimentos e tutoriais que precisam ser executados em uma ordem exata.*

---

# 10. Listas de Tarefas (Checklists)

O GitHub permite criar caixas de seleção interativas usando `- [ ]` para tarefas pendentes e `- [x]` para concluídas:

- [ ] Criar o repositório
- [ ] Criar o README.md
- [ ] Realizar a atividade 
- [ ] Criar o commit 
- [ ] Enviar para o GitHub

*Esse recurso é especialmente útil para acompanhar o progresso de atividades e projetos.*
