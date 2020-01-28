# Guia de aula

## Acessar material de aula

Os materiais utilizados na aula estão neste repositório com os nomes `AulaKotlin.pdf`, 
correspondente ao material de aula do primeiro dia (30/01), e `AulaAndroid.pdf`, 
correspondente ao material de aula do segundo dia (31/01). Os arquivos serão disponibilizados 
conforme o decorrer do curso. É possível baixar os arquivos clicando em 
**Clone and download > Download ZIP**.

![](https://i.imgur.com/S7Kis1Z.png)

## Acessar compilador do Kotlin

É possível acessar o compilador da linguagem Kotlin por meio de duas formas: online e pelo 
Android Studio.

### Acessando via online

A desenvolvedora da linguagem criou o site [Try Kotlin](https://try.kotlinlang.org/) para 
usuários conseguirem utilizar os recursos da linguagem.

![](https://i.imgur.com/6Gp2rMM.png)

É possível digitar o código em Kotlin na caixa de texto e clicar em **Run** no canto superior 
direito da tela para rodar o código.

![](https://i.imgur.com/mfKSHeP.png)

Após rodar o código, caso o programa tenha algum erro ou você queira visualizar a saída do 
programa, é possível utilizar a caixa de saída no canto inferior da tela.

![](https://i.imgur.com/4Jq6Bbe.png)

Existe também uma forma mais interativa de o compilador melhorar seu código, fornecendo dicas ou 
erros na caixa de saída sem que você clique em **Run**, mas em tempo real enquanto você digita, 
que é a caixa de seleção no canto inferior direito, em **On-the-fly type checking**.

![](https://i.imgur.com/W3luVbg.png)

A única forma de fornecer entrada para o compilador online é por meio dos argumentos de linha de 
comando, uma caixa de texto localizada no canto superior da tela. Você pode digitar os argumentos 
separados por vírgulas e recebê-los no código por meio do parâmetro `args` da função `main`. 
Segue um exemplo de como somar dois números recebidos como entrada pelo usuário:

![](https://i.imgur.com/jS2dAy4.png)

### Acessando via Android Studio

O Android Studio também possui um compilador de Kotlin embutido, parecido com a IDLE do Python.

Para acessá-lo, ao abrir o Android Studio:

- Crie um novo projeto em **Start a new Android Studio project**.

![](https://i.imgur.com/frrtccb.png)

- Crie uma activity vazia em **Add No Activity** e clique em **Next**.

![](https://i.imgur.com/rP8268N.png)

- Dê um nome qualquer a seu projeto em **Name** e clique em **Finish**.

![](https://i.imgur.com/hHT0ZJw.png)

- Aguarde o Android Studio construir o projeto. Isso pode ser verificado no canto inferior da tela, 
quando todas as marcações estiverem verdes.

![](https://i.imgur.com/I89jHyp.png)

- No canto superior da tela, clique em **Tools > Kotlin > Kotlin REPL**. Ao aparecer uma tela perguntando 
o contexto do módulo, selecione o nome do seu projeto.

- O compilador do Kotlin irá aparecer no canto inferior da tela.

![](https://i.imgur.com/qR1s5uG.png)

- Digite o programa na caixa de texto e pressione <kbd>CTRL</kbd>+<kbd>Enter</kbd> para executar. Segue um 
exemplo de como somar dois números recebidos como entrada pelo usuário (após inserir cada valor,
deverá pressionado <kbd>CTRL</kbd>+<kbd>Enter</kbd> para que os valores sejam aceitos como entrada
pelo programa).

![](https://i.imgur.com/rnFOcrl.png)