# wiki-study
Este é apenas um estudo sobre wiki e formatação de github.

A forma de editar o texto é o Markdown, o markdown é um tipo de formatação de texto e é usado no github.

Para o texto temos muitas coisas que podemos usar em um read me, você verá abaixo:

# Titles

Cada vez que você cria um título ele aparecerá nos três pontos no canto superior direito do readme como uma seção facilitando a navegação.
Nos títulos você pode usar # para transformar a palavra depois em um título. Você também pode usar ## ou ### para mudar o tipo de título, por exemplo:

# estudo

título com #

## wiki

título com ##

### github

título com ###

# Formatação do texto

## Formatação

Lembrando que os textos devem estar entre os sinais exemplo: * * (palavra) * *

### Negrito

Para o negrito se usa ** ** ou __ __	ou você pode usar Comando+B (Mac) ou CTRL+B (Windows/Linux) exemplo:

Este texto está em negrito - **This is bold text**

### Itálico

Para o itálico se usa * * ou _ _ ou você pode usar Comando+I (Mac) ou CTRL+I (Windows/Linux) exemplo:

Este texto está em itálico - _This text is italicized_

### Tachado

Para o tachado se usa ~~ ~~ exemplo:

Este texto contém um erro e está tachado - ~~This was mistaken text~~

### Negrito e itálico

Para colocar em negrito e itálico aninhado	** ** e _ _ nesse caso serve para deixar uma palavra ou frase do meio em itálico exemplo:

Este texto é extremamente importante - **This text is _extremely_ important**

### Tudo em negrito e itálico

Para colocar tudo em negrito e itálico	*** *** exemplo:

Todo este texto é importante - ***All this text is important***

### Subscrito

Subscrito	< sub> < /sub > (quando usar tire os espaços) exemplo:

text	Este é um texto subscrito - This is a <sub>subscript</sub>

### Sobrescrito

Sobrescrito	< sup> < /sup > (quando usar tire os espaços) exemplo:

text	Este é um texto sobrescrito - This is a <sup>superscript</sup>

### Sublinhado

Sublinhado	< ins> < /ins > (quando usar tire os espaços) exemplo:

Este é um texto sublinhado - This is an <ins>underlined</ins> text

## Citação

Para fazer um citação de usa (>) exemplo:

>Uma citação

# Listas

### Lista não ordenada

É possivel criar essa lista colocando -, * ou + antes das palavras, exemplo:

- Café
* Bacon
+ Ovos

### Lista ordenada

Para essa é só colocar um número e um ponto na frente de cada linha, exemplo:

1. alface
2. hamburguer
3. pão

### Lista aninhada

Na lista aninhada você usar outras listas e adicionar "objetivos extras" para ela, você cria dando um espaço na linha de baixo do objetivo pricipal e coloca um (-) (você pode criar um objetivo dentro de outro também) como exemplo:

1. começar o projeto
   - planejar a ideia
   - definir o genero
   - pensar na gameplay
     - desenvolver uma história
2. programar

### Lista de tarefas

Para criar uma lista de tarefas, coloque um hífen e um espaço seguidos de [ ] antes dos itens de lista. Para marcar uma tarefa como concluída, use [x]. Exemplo:

- [x] Idealizar o projeto
- [ ] Registrar momentos importantes
- [ ] começar a programar

# Créditos

Você pode mencionar uma pessoa ou uma equipe no GitHub digitando @ mais seu nome de usuário ou o nome da equipe. Exemplo:

@IsaqueDias1

# Emoji (não recomendado)

É possível adicionar um emoji à escrita digitando :EMOJICODE:, dois pontos e, em seguida, o nome do emoji.

@octocat :+1: This PR looks great - it's ready to merge! :shipit:

Link para mais emojis:https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md

# Alertas

São usados para destacar textos especificos para ajudar a compreensão e existem vários tipos de alertas como:

> [!NOTE]
> Usado para mostrar informações uteis ou pontos que valem ser citados.

> [!TIP]
> Dicas para ajudar a compreender o que está no read me.

> [!IMPORTANT]
> Pontos importantes sobre o projeto que os membros ou usuários precisam saber.

> [!WARNING]
> Passa uma mensagem de algo crucial para ser resolvido com urgencia ou fala sobre problemas presentes no projeto.

> [!CAUTION]
> Serve para avisar de possiveis problemas caso algo aconteça ou alguém mude algo.

# Comentários

Você pode dizer a GitHub para ocultar o conteúdo do markdown interpretado, colocando o conteúdo em um comentário HTML. Esse comentário não aparece no read me.

<!-- This content will not appear in the rendered Markdown -->

# Citar códigos

É usado para mostrar códigos principalmente sem executar eles e é usado `` (crase) para marcar.

Use `git status` to list all new or modified files that haven't yet been committed.

Para formatar código ou texto no próprio bloco distinto, use crase triplas.

```
git status
git add
git commit
```

# Tabelas

Você pode usar formatação, como links, blocos de código embutidos e estilo de texto na tabela:

```
| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |
```

Exemplo:

| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

Você pode alinhar o texto à esquerda, à direita ou no centro de uma coluna incluindo dois pontos : à esquerda, direita ou nos dois lados dos hifens que estão dentro da linha de cabeçalho.

```
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
```

Exemplo:

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

Para incluir uma barra vertical | como conteúdo dentro da célula, use \ antes da barra vertical:

```
| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |
```

Exemplo:

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

# Considerações finais

Obviamente eu não coloquei todos os conteúdos nesse read me, mas a grande maioria e com mais importancia está aqui por isso abaixo está o link do manual do github para acesso a mais coisas possiveis de se fazer:

https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#further-reading
