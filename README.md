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

## 📬 Como criar um repositório?

Já com o Git em seu computador e sua conta no GitHub, basta agora criarmos um repositório, onde você pode ter vários e salvar seus trabalhos ou projetos nele. Para isso acesse seu perfil no GitHub e acesse a aba de Repositórios.


![](https://cdn.discordapp.com/attachments/576875163686010911/661637887829344276/unknown.png)


Já na aba de repositórios, iremos criar um novo repositório para nosso tutorial:


![](https://cdn.discordapp.com/attachments/576875163686010911/661639336218984508/unknown.png)

Criando um repositório, devemos dar um nome para ele, após informar se ele será público ou privado e por fim, podemos marcar a opção de vir com um README.md, que no caso é um documento de texto para exibição e explicação para alguem que não conhece o projeto. Feito isso, podemos clicar no botão verde no fim da tela e criar o nosso repositório:


![](https://cdn.discordapp.com/attachments/576875163686010911/661640471973462046/unknown.png)


Com repositório em mãos, iremos clonar esse repositório em nosso computador, é como se tivessemos uma pasta em nosso computador que envia e salva as informações na nuvem, ou melhor em nosso GitHub. Para fazer o clone, precisamos copiar essa URL que aparece ao clicarmos no botão verde:


![](https://cdn.discordapp.com/attachments/576875163686010911/661642037476720661/unknown.png)


Com a URL em mãos, iremos clonar o repositório em nosso computador, para isso, encontre o melhor local para salvar sua pasta, no meu caso a minha área de trabalho, feito isso, clicar com o botão direito do mouse, e clicar na opção "Git Bash Here", onde irá abrir uma tela escura ao lado de onde clicamos:


![](https://cdn.discordapp.com/attachments/576875163686010911/661643508494630921/unknown.png)


O Git Bash foi intalado junto com o Git, é possível fazer os mesmos comandos que iremos rodar via terminal, sendo assim, questão de gosto 🍕x🍔.

Com o Git Bash aberto, iremos rodar o seguinte comando...

```
git clone [sua url]
```
Em meu caso:


![](https://cdn.discordapp.com/attachments/576875163686010911/661646377071149081/unknown.png)


E então, em seu local onde desejou salvar seu repositório, no meu caso, em minha área de trabalho irá aparecer a pasta TesteGit 🗂, meu repositório, com o arquivo README.md

Usaremos mais dois comandos, para que nosso usuário git seja identificado...

```
git config --global user.name "Seu nome"
git config --global user.email "seuemail@email.com"
```

![](https://cdn.discordapp.com/attachments/576875163686010911/661653663411994645/unknown.png)

## 💻 Comandos do Git

Com nosso repositório já em nossa máquina, irei criar um documento de texto para exemplificar um projeto ou código...

![](https://cdn.discordapp.com/attachments/576875163686010911/661652644321820707/unknown.png)

Feito isso, iremos utilizar um comando para acessar dentro do nosso repositório...

```
cd [nome do repositório/pasta]
```

![](https://cdn.discordapp.com/attachments/576875163686010911/661963765239119903/unknown.png)

Feito isso, estamos dentro do nosso repositório. Agora vamos rodar um comando para validarmos o que foi feito dentro do nosso repositório, se modificamos, adicionamos ou deletamos algum documento...

```
git status
```

![](https://cdn.discordapp.com/attachments/576875163686010911/661964993654423603/unknown.png)

Podemos ver que foi adicionado em nosso repositório um documento de texto e que ele está vermelho, isso significa que ele não foi adicionado em nenhum commit. Commit é a meneira que adicionamos algo para o repositório que está na hospedagem, por meio dos commits, vamos adicionando lá

Para adicionarmos o nosso documento de texto iremos rodar o seguinte comando...

```
git add .
```

Nesse comando, adicionamos todos os documentos que foram modificados, adicionados ou deletado, caso queira adicionar algum arquivo específico ou adicionar arquivo por arquivo, basta rodar o seguinte comando...

```
git add [local onde está o arquivo... ex: docs/teste/classA.txt]
```

Feito o comando, se rodarmos novamente o comando ``` git status ```, veremos que o nome do arquivo está verde, representando que ele foi adicionado... 

![](https://cdn.discordapp.com/attachments/576875163686010911/661966752548388864/unknown.png)

Feito isso, sabemos que nosso arquivo adicionado de teste, foi adicionado em nosso commit, agora vamos enfim rodar o comando para fazer o commit em si...

```
git commit -m "sua mensagem"
```

Em sua mensagem, existem diversos padrões de commit, dependendo de cada projeto, empresa ou equipe, o importante é sempre seguir um padrão. Em meu caso, sigo o [Semantic Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)...

![](https://cdn.discordapp.com/attachments/576875163686010911/662005818455228467/unknown.png)

Feito o commit, rodei o comando ```git status```, onde podemos ver que não aparece o nosso arquivo modificado, pois, agora ele está no commit, mas o commit não está no GitHub ainda, está apenas localmente em seu computador OBS: Podem ser feitos vários commits localmente.

Para enviar nossos commits que estão apenas localmente em seu computador precisamos rodar o comando...

```
git push
```

Depois disso, o seu hospedador irá fazer algum tipo de autenticação com seu email e senha por exemplo, em meu caso eu informo meu email e após isso, aparece um campo na tela para que eu possa informar minha senha do GitHub... Mas isso não significa que será exatamente assim, pode mudar dependendo das versões da máquina por exemplo...

![](https://cdn.discordapp.com/attachments/576875163686010911/662009940352958474/unknown.png)

![](https://cdn.discordapp.com/attachments/576875163686010911/662010282524147714/unknown.png)

Feito isso, nosso commit já está no GitHub, acessando novamente nossa tela do repositório no GitHub, podemos acessar nossos commits...

![](https://cdn.discordapp.com/attachments/576875163686010911/662010810033373205/unknown.png)

![](https://cdn.discordapp.com/attachments/576875163686010911/662011022047051816/unknown.png)

Onde teremos dois commits, sendo o primeiro quando damos o nosso ```git clone [sua url]``` e último o nosso que fizemos agora... Ainda podemos ver o que foi feito no commit, basta apenas acessa-lo...

![](https://cdn.discordapp.com/attachments/576875163686010911/662011716015620116/unknown.png)

### 🙂🙃🙂 E se eu estiver em Dupla ou mais pessoas?

É muito comum trabalharmos em um projeto em mais pessoas, "Então eu vou ter que rodar ```git clone``` toda vez que meu colega adicionar um commit novo dele?". Nada disso, para isso temos o comando...

```
git pull
```

Com esse comando, atualizamos a nossa branch "Tá Rhian, denovo essa palavra? O que é isso?", calma lá estamos chegando nela. Mas voltando, podemos atualizar com esse comando, em nosso caso, se rodarmos esse comando, não será adicionado nada...

![](https://cdn.discordapp.com/attachments/576875163686010911/662013309326721030/unknown.png)

E finalmente chegamos no termo ```branch```, na tradução literal "Ramo" ou "Galho". No git, podemos trabalhar em tempos diferentes, imagine que você trabalha em um projeto com mais outras 3 pessoas, cada um pega uma tarefa e depois de terminar todos adicionam ao mesmo tempo as suas tarefas, mas caso você modificar o mesmo arquivo que um outro colega modificou, isso gera um conflito, pois, em cada um dos commits existe uma linha diferente para a mesma linha.

Então as branchs vieram para nos ajudar com isso, sendo assim, o nosso versionamento. Na maioria dos projetos, temos algumas branchs padrão, sendo assim a branch ```master``` que é a branch principal, ela normalmente é a que está com código que está "Em Produção", termo usado para denominar o código que já está sendo usado por usuários e rodando em um servidor...

Depois temos a branch ```develop``` que é a branch que está em desenvolvimento, sendo assim, a branch principal para os desenvolvedores. A branch ```develop``` possui o mesmo código que a master mais todos os códigos que foram desenvolvidos pelos desenvolvedores e depois será adicionado na branch ```master```, onde as novas funcionalidades ou soluções de Bugs da branch ```develop``` irão para a branch ```master```. Como a brach ```develop``` é exatamente igual a master, mas adicionada de mais código desenvolvido, não irá gerar conflito com a ```master``` caso ela seja atualizada com a ```develop```.

🧪
```
o --> master
|  o --> develop
|  |
|  |o --> a branch de feature/user-login é adicionada na develop
|  | \
|  |  | --> feature/user-login
|  | /
|  |/
|  o  --> é criada uma branch chamada feature/user-login com base na develop
|  |
| /
|/
o
``` 

Como foi dito antes... A branch ```develop``` é a branch principal para os desenvolvedores, então caso você queira criar uma uma nova ```feature``` para o usuário fazer seu login, você deve como desenvolvedor criar uma branch a partir da ```develop``` e criar a nova funcionalidade e por fim, atualizar sua branch com a ```develop``` caso algum colega seu tenha adicionado código que possa gerar conflito, caso isso aconteça, basta resolver o conflito e por fim adicionar sua branch na ```develop```

### ♻ Como criar uma branch?

Para criar uma branch é simples, como exemplo, vamos criar a branch ```develop``` a partir, em nosso caso já estamos na branch master, pois ela é criada automaticamente com o commit inicial... 

```
git checkout -b develop
```

O comando ```git checkout [sua branch]``` nos possibilita acessarmos outras branchs e navegar entre as branchs, já o comando ```git checkout -b [sua branch]``` cria uma nova branch...

![](https://cdn.discordapp.com/attachments/576875163686010911/662021668218077214/unknown.png)

Na imagem, podemos ver que criei a branch ```develop``` com o comando ```git checkout -b develop``` e automaticamente acessei ela, após isso voltei para a branch ```master``` com o comando ```git checkout master```... Nesse momento, a branch ```develop``` possui exatamente o mesmo conteúdo que a branch ```master```

Para exemplificar irei criar uma nova branch a partir da ```develop``` e alterar nosso texto de teste, commitar e após isso adicionar as modificações feitas nessa nova branch para a develop...

![](https://cdn.discordapp.com/attachments/576875163686010911/662024146061885442/unknown.png)

Voltei para a branch ```develop``` e criei uma nova branch chamada ```feature/new-line``` a partir da branch ```develop```, nesse caso, minha nova branch é exatamente igual a ```develop```...

![](https://cdn.discordapp.com/attachments/576875163686010911/662027713581809724/unknown.png)

Mas a branch ```develop``` ainda não estava no GitHub, então rodei o comando...

```
git push --set-upstream origin develop
```

Para adicionar a branch ```develop``` no GitHub

![](https://cdn.discordapp.com/attachments/576875163686010911/662024842844831815/unknown.png)

![](https://cdn.discordapp.com/attachments/576875163686010911/662025379577462795/unknown.png)

Fiz a modificação em nosso documento de texto e após fiz o commit, mas na hora do commit apareceu uma mensagem, explicando essa nossa nova branch ainda não está no GitHub, para adicionarmos essa nova branch, basta rodar o commando informado na mensagem...

```
git push --set-upstream origin feature/new-line
```

![](https://cdn.discordapp.com/attachments/576875163686010911/662026340358160421/unknown.png)

Após rodarmos o comando, enfim, adicionamos nosso commit na nova branch, podemos vizualizar esse commit via GitHub...

![](https://cdn.discordapp.com/attachments/576875163686010911/662028278499901473/unknown.png)

![](https://cdn.discordapp.com/attachments/576875163686010911/662028508607807488/unknown.png)

Podemos ver nossas ambas branchs, ao lado da branch ```feature/new-line``` podemos criar um novo Pull Request, ele serve para passar tudo o que existe de uma branch para outra. Mas antes de fazermos isso, iremos atualizar nossa branch ```feature/new-line``` com base na branch develop, imaginando o caso de um outro colega tenha alterado a branch develop, para atualizar iremos usar o comando...

```
git pull origin develop
```

O comando ```git pull``` já haviamos conhecido, mas o ```git pull origin develop``` eu referencio que ele deve atualizar com a ```origin develop``` no caso ele irá atualizar com base na branch da develop que está no GitHub... Feito isso, não temos nenhum conflito, entrão iremos criar um Pull Request...

![](https://cdn.discordapp.com/attachments/576875163686010911/662028508607807488/unknown.png)

![](https://cdn.discordapp.com/attachments/576875163686010911/662030661376278530/unknown.png)

No caso iremos adicionar as modificações da branch ```feature/new-line``` para a branch ```develop```, então devemos modificar isso como mostra a imagem acima...

![](https://cdn.discordapp.com/attachments/576875163686010911/662031099660337172/unknown.png)

No Pull Request, podemos ver todos os commits e todos os arquivos modificados, adicionados ou deletados... Após conferirmos que é os arquivos corretos que modificamos e iremos adicionar na ```develop```, podemos clicar no botão verde e criar o pull request para adicionar na ```develop```.

![](https://cdn.discordapp.com/attachments/576875163686010911/662032027356495892/unknown.png)

Criado o Pull Request, nossa branch ainda não está na branch ```develop```, nesse momento, montamos a request apenas, agora o correto é nossos colegas revisarem nossas modificações, realizando assim o [Code Review](https://medium.com/trainingcenter/qual-o-real-valor-do-code-review-para-uma-equipe-de-desenvolvimento-f43f894c0a04), que resumidamente é um momento onde um colega seu revisa seu código e pode te ajudar com sua solução propondo alguma outra solução ou te lembrar de algo que faltou em sua solução... Isso pode gerar uma troca de conhecimento para ambos os lados e aumentando o nível de qualidade e conhecimento da equipe...

Após revisado e aprovado o Pull Request, podemos vizualizar que nossa branch develop possui nossas modificações...

![](https://cdn.discordapp.com/attachments/576875163686010911/662033715010076714/unknown.png)

![](https://cdn.discordapp.com/attachments/576875163686010911/662033837630423070/unknown.png)

![](https://cdn.discordapp.com/attachments/576875163686010911/662034005243461669/unknown.png)

![](https://cdn.discordapp.com/attachments/576875163686010911/662034103910137887/unknown.png)

![](https://cdn.discordapp.com/attachments/576875163686010911/662034218637066268/unknown.png)

![](https://cdn.discordapp.com/attachments/576875163686010911/662034340246716426/unknown.png)

Feito isso... finalizo aqui esse README para iniciantes na ferramenta, existem outros diversos comandos que podem ser adicionados aqui, então esse README ainda pode ser modificações, estou aberto á críticas, dúvidas e melhorias, basta entrar em contato 🙃.

O repositório feito nas prints está público e disponível para consulta, basta acessar [TesteGit](https://github.com/RhianLopes/TesteGit).

