# 🐱‍👤 Git

## 💡 Ideia

Git é um repositório focado em ajudar e ensinar iniciantes na programação ou na ferramenta a entenderem como usar e aprender alguns comandos. Tive a ideia de criar esse repositório depois de realizar o Integrador 2019, no IFSul - campus Sapucaia do Sul, organizado pelo professor Rodrigo Remor, para saber mais sobre o projeto acesse [MyPet](https://github.com/RhianLopes/MyPet).

A ideia veio quando vi que a grande maioria dos meus colegas não conheciam a ferramenta e tiveram problemas com seus projetos, como por exemplo esquecer o Pen Drive que trouxe de casa, corromper algum arquivo, alguem apagar o seu projeto no computador da escola, foram motivos como estes que me fizeram tomar essa iniciativa. Esse tutorial é focado para iniciantes no Git.

## 🤔 Mas o que é Git?

Git é um controlador de versionamento [open-source](https://canaltech.com.br/produtos/O-que-e-open-source/), ou seja, você consegue controlar a versão do seu código, projeto ou trabalho "Tá... Rhian. Mas pra quê vou usar isso?"

Digamos que você está em sua casa, fazendo seu integrador, quando sua amigo chega para te convidar pra caçar pokemon, sem conseguir recusar, você vai e sai com ele. Ao voltar, sua mãe logo fala que foi em seu computador ver uma receita e apareceu uma tela azul, você se lembra "Minha nossa! Meu trabalho! Eu tinha salvado?", caso você não tenha salvado, terá que esperar seu computador ir para o concerto, que demora em torno de 2 semanas, e só depois disso poderá continuar seu projeto, sendo que falta apenas 1 dia para entregar.

Com o Git, você pode fazer o versionamento de seu projeto, salvando ele em alguma plataforma grâtis ou paga e poder acessar ele de qualquer computador ou até mesmo vizualizar seu código on-line. Outra situação, é poder recuperar algum código que tenha apagado por algum motivo, mas lá na frente acaba precisando dele, com o git, você pode voltar em seus commits ou branchs e encontrar seu código perdido. "Mas Rhian, o que é commmit? Branch?", calma amigos, é o que veremos em seguida 😜.

## 💸 O que eu preciso para ter um Git?

Existem duas necessidades básicas para utilizar a ferramenta, sendo elas, intalar o git e ter uma plataforma de hospedagem de repositórios git, "Tá mas isso é caro? hospedagem de servidor?". Para instalar, basta acessar o [Git](https://git-scm.com) e seguir o esse [tutorial para intalação do git no windows](https://dicasdeprogramacao.com.br/como-instalar-o-git-no-windows).

Já com o Git instalado, temos que hospedar um repositório git, "Isso é Pago? Qual indica?", pode ser pago e gratuito, na maioria das empresas, elas possuem uma conta paga na plataforma escolhida, tendo assim, maiores funcionalidades etc... Mas existem muitas plataformas gratuitas e que oferecem diversas funcionalidades, que é o caso do [GitHub](https://github.com), onde você pode fazer um [cadastro](https://github.com/join?source=header-home) rápido e fácil e ter onde hospedar seus repositórios.

## Como criar um repositório?

Já com o Git em seu computador e sua conta no GitHub, basta agora criarmos um repositório, onde você pode ter vários e salvar seus trabalhos ou projetos nele. Para isso acesse seu perfil no GitHub e acesse a aba de Repositórios.

![](https://cdn.discordapp.com/attachments/576875163686010911/661637887829344276/unknown.png)

Já na aba de repositórios, iremos criar um novo repositório para nosso tutorial

![](https://cdn.discordapp.com/attachments/576875163686010911/661639336218984508/unknown.png)

Criando um repositório, devemos dar um nome para ele, após informar se ele será público ou privado e por fim, podemos marcar a opção de vir com um README.md, que no caso é um documento de texto para exibição e explicação para alguem que não conhece o projeto. Feito isso, podemos clicar no botão verde no fim da tela e criar o nosso repositório.

![](https://cdn.discordapp.com/attachments/576875163686010911/661640471973462046/unknown.png)

Com repositório em mãos, iremos clonar esse repositório em nosso computador, é como se tivessemos uma pasta em nosso computador que envia e salva as informações na nuvem, ou melhor em nosso GitHub. Para fazer o clone, precisamos copiar essa URL que aparece ao clicarmos no botão verde.

![](https://cdn.discordapp.com/attachments/576875163686010911/661642037476720661/unknown.png)

Com a URL em mãos, iremos clonar o repositório em nosso computador, para isso, encontre o melhor local para salvar sua pasta, no meu caso a minha área de trabalho, feito isso, clicar com o botão direito do mouse, e clicar na opção "Git Bash Here", onde irá abrir uma tela escura ao lado de onde clicamos.

![](https://cdn.discordapp.com/attachments/576875163686010911/661643508494630921/unknown.png)

O Git Bash foi intalado junto com o Git, é possível fazer os mesmos comandos que iremos rodar via terminal, sendo assim, questão de gosto 🍕x🍔.

Com o Git Bash aberto, iremos rodar o seguinte comando

```
git clone [sua url]
```
Em meu caso

![](https://cdn.discordapp.com/attachments/576875163686010911/661646377071149081/unknown.png)

E então, em seu local onde desejou salvar seu repositório, no meu caso, em minha área de trabalho irá aparecer a parta TesteGit, meu repositório, com o arquivo README.md


## Comandos do Git
