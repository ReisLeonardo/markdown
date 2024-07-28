# markdown.md - do que se trata?
[English](https://github.com/ReisLeonardo/markdown/blob/main/ENGLISH.md) | [中文](https://github.com/ReisLeonardo/markdown/blob/main/%E4%B8%AD%E6%96%87.md)

Markdown é uma linguagem simples de marcação originalmente criada por John Gruber e Aaron Swartz. Markdown converte seu texto em [HTML](https://github.com/ReisLeonardo/html-css/blob/main/html.md) válido. Markdown é frequentemente usado para formatar arquivos README, para escrever mensagens em fóruns de discussão online e para criar rich text usando um editor de texto simples.

![image](https://user-images.githubusercontent.com/89877899/153759851-7dde4771-2ce5-4086-a392-5739a9e6f1df.png)
## markdown - como usá-lo?
> É bastante simples, o arquivo precisa ter terminação .md, portanto quando você ver um arquivo terminado em .md ele com certeza é um arquivo de markdown! Quando isso vem para o uso no GitHub, você pode criar um README.md.

## markdown - vamos escrevê-lo!
### Títulos
Para criar um título, adicione um a seis símbolos ```#``` antes do texto do título. O número de ```#``` que utilizar determinará o nível hierárquico e o tamanho do tipo de letra do título.

``` markdown
# Um título de primeiro nível
## Um título de segundo nível
### Um título de terceiro nível
#### Um título de quarto nível
##### Um título de quinto nível
###### Um título de sexto nível
```

![image](https://github.com/user-attachments/assets/9ddc48c9-5208-4ca2-bd4f-f9ff6d375979)

>[!WARNING]
> Embora os títulos se tornem visualmente menores à medida que você adiciona mais jogos da velha, isso não significa que você pode manipular os tamanhos dessa forma. Geralmente, as [CSS (Folhas de Estilo em Cascata)](https://github.com/ReisLeonardo/html-css/blob/main/css.md) são usadas para estilizar e manipular o tamanho e a aparência em linguagens de marcação.

>[!NOTE]
> Quando você usa dois ou mais cabeçalhos, GitHub gera automaticamente um índice que você pode acessar clicando no cabeçalho do arquivo. Cada título de cabeçalho é listado no índice e você pode clicar em um título para navegar para a seção selecionada.

### Estilizando texto ou palavras.
Pode indicar ênfase com texto a negrito, itálico, riscado, subscrito ou sobrescrito em campos de comentários e ficheiros .md.

Estilo | Sintaxe | Atalho no teclado | Saída (resultado)
--- | --- | --- | ---
Negrito | ``** **`` or ``__ __`` | ```Command``` + ```B``` (Mac) or ```Ctrl``` + ```B``` (Windows/Linux) | **Olá, mundo!**
Itálico | ``* *`` or ``_ _`` | ```Command``` + ```I``` (Mac) or ```Ctrl``` + ```I``` (Windows/Linux) | Olá, *world*!
Riscado | ``~~ ~~`` | | ~~HTML4~~ 
Negrito e itálico aninhado | ``** **`` and ``_ _`` | | **Esse texto foi escrito em _English_.**
Tudo em negrito e em itálico | ```*** ***``` | | ***This text was written in English.***
Subscrito | ```<sub> </sub>``` | | H<sub>2</sub>O
Sobrescrito	| ```<sup> </sup>``` | | ax<sup>2</sup>+bx+c=0

>[!NOTE]
> Você pode combinar diferentes estilos para criar combinações ainda mais complexas!

>[!IMPORTANT]
> Se você digitar *** e não escrever nada depois, uma linha horizontal será criada.

### Citar texto
Você pode citar texto com um ```>```.

``` markdown
Este texto não é uma citação

> Este texto é uma citação
```

O texto citado é recuado, com uma cor de texto diferente.

![image](https://github.com/user-attachments/assets/24d787ec-b370-42ad-a341-46d472bcf121)

### Citar linhas de código
Você pode chamar o código ou um comando dentro de uma frase com pontos finais simples. O texto dentro das reticências não será formatado. Também pode premir o atalho de teclado ```Command``` + ```E``` (Mac) ou ```Ctrl``` + ```E``` (Windows/Linux) para inserir os remates de um bloco de código numa linha de Markdown.

Para formatar o código ou o texto num bloco distinto, utilize três acentos graves ``(```)``.

``` python
print("Olá, mundo!\n")
print("Esta frase foi escrita em linguagem Python!")
```

>[!NOTE]
> Se você adicionar o nome da linguagem após as três aspas invertidas (```), o código dentro delas será formatado de acordo com essa linguagem.

### Modelos de cores
Em issues, pull requests e discussões, você pode chamar as cores dentro de uma frase usando acentos graves. Um modelo de cor suportado dentro dos acentos graves exibirá uma visualização da cor.

``` A cor de fundo é `#ffffff` para o modo claro e `#000000` para o modo escuro. ```

### Criar uma lista
É possível criar uma lista não ordenada precedendo uma ou mais linhas de texto com -, * ou +.
- 你好，我是李在中国!
* Olá, eu sou Leonardo do Brasil!
+ Hello, I am Joe from the USA!

Para listas ordenadas, preceda cada linha com um número.
1. Primeiro
2. Segundo
3. Terceiro

### Lista de afazeres
Para criar uma lista de tarefas, coloque um hífen e um espaço no início dos itens da lista, seguidos de ``[ ]``. Para marcar uma tarefa como concluída, utilize ``[x]``.

- [X] Levar o João a escola 
- [ ] Estudar um idioma

``` markdown
### Adicionando imagens e criando endereços eletrônicos:
Para adicionar uma imagem ou criar um endereço eletrônico. Basta arrastar/anexar a imagem para o repositório ou digitar (não faça envio de imagens muito grandes).

![image](https://user-images.githubusercontent.com/89877899/153758712-d76ebde7-747d-4695-8501-4d828c5709b5.png)

>[!NOTE]
> Note que a única diferença é que as imagens possuem um sinal de exclamação, já os links não!

### Tabelas (matrizes)
Uma matriz é feita da seguinte forma:

![image](https://user-images.githubusercontent.com/89877899/153759106-21540a9b-2f32-4089-9923-4fdfe05f291d.png)

Nome | País | Idade
---|---|---
Leonardo | Brasil | 17
Tanaka | Japão | 26
Joe | EUA | 36
Isabella | Colombia | 27
```

### Adicionar emojis/figuras :smile:
Pode adicionar emoji à sua escrita escrevendo ``:CÓDIGODOEMOJI:``, dois pontos seguidos do nome do emoji.

Se escrever ``:``, aparece uma lista de emojis sugeridos. A lista é filtrada à medida que escreve, por isso, quando encontrar o emoji que procura, prima Tab ou Enter para completar o resultado realçado.

Para obter uma lista completa dos emojis e códigos disponíveis, clique [aqui](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).
