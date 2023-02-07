# ☕ Desafio de Git e GitHub NA PRÁTICA 

## ✒️ Sobre este repositório

Este repositório foi criado com objetivo de ser como um treino de Git e GitHub, o foco é a prática de recursos básicos como Branch e Pull Request que são utilizados em trabalho em equipe em desenvolvimento de grandes projetos.

> "Bota o casaco, Tira o casaco" _- Karate Kid_

### 🎓 Para quem se destina o desafio?

Qualquer um que está no início de carreira de desenvolvimento de sistemas e pretende treinar as tecnologias Git e GitHub.

### 📎 O que precisa?

É importante ter instalado o Git em sua máquina local e possuir uma conta no GitHub, ao final deste documento tem a seção de Links úteis tem o link do site oficial do Git e também o GitHub Desktop caso queira utilizar.  
Ter feito curso não é obrigatório, mas é importante principalmente para quem ainda não está familiarizado com os conceitos de Git e GitHub. Aqui o foco é a prática, não terá os comandos para copiar e colar, a ideia é que caso não lembre o comando saiba onde pesquisar, se tiver alguma dúvida ou problema é só ir até o final do documento para saber como entrar em contato.

------

## 💪 Passos do desafio

### 💾 Passo 1 - Fork

Crie um fork deste repositório.  
_Isto irá criar um cópia deste repositório em sua conta para que possa fazer sua manipulação sem afetar o repositório base._

### 💻 Passo 2 - Clone
  
Faça um clone deste repositório que já estará vinculado com sua conta do GitHub para sua máquina local.  
_Muitas vezes para facilitar a edição de código, baixamos os arquivos localmente para usar editar com seu programa favorito. E aqui é importante que já tenha instalado o Git em sua máquina local para continuar._

### ⤵️ Passo 3 - Branch
  
Após o clone realizado, crie uma nova branch antes de fazer qualquer alteração. O nome da branch é livre.
_É comum que em desenvolvimento em equipe, a branch principal não seja editada diretamente, criar uma branch nova antes da edição facilita a visibilidade da mudança, verificação e até mesmo a evitar conflitos de alterações._

### 📂 Passo 4 - Edição

Na máquina local, em sua nova branch, procure pelo arquivo `propriedades-sistema.txt`, abrá-o e insira uma nova linha com o conteúdo: `USUARIO_GITHUB: DATA_ADICAO`, onde:

- `USUARIO_GITHUB` é o seu nome de usuário no github, exemplo: didifive;
- `DATA_ADICAO` é a data em que inseriu a linha, por exemplo: 06/02/2023 (formato dd/mm/aaaa)  

**É importante que a adição da linha possua os dois elementos acima, afinal se fosse um arquivo de código, tem que respeitar a sintaxe e propriedades.**  
Salve o arquivo e faça seu commit na sua branch. Aproveite para pensar sobre commits semânticos, onde é aproveitada a mensagem para descrever o que, aqui a mensagem de commit é livre.

_Aqui é apenas para simular a edição de um arquivo, como exemplo, um arquivo de propriedades de um sistema._

### ⤴️ Passo 5 - Push 
  
Após a edição, faça um Push para atualizar seu repositório remoto.
_Este é um passo natural após um commit, garante que o repositório remoto está no mesmo ponto que o repositório local._

### ↩️ Passo 6 - Pull Request
  
Após seu repositório remoto estar atualizado é possível perceber no GitHub que existe uma branch nova, a mesma que criou no Passo 3, nela será possível verificar que o arquivo editado está atualizado remotamente também. Então agora inicie um novo Pull Request para enviar a atualização realizada na sua branch criada do seu repositório diretamente para a branch master do repositório base "[didifive/desafio-git-github]".  
**Importante ter atenção com o "base repository" e a branch "base" e o "head repository" e "compare".**

- **O que está em "base" é o repositório e respectiva branch que será atualizada e,**
- **O que está em "head" e "compare" é o repositório e respectiva branch que contém a atualização.** 

_O processo de Pull Request acontece quando vai atualizar uma branch com o conteúdo de outra de maneira que fique registrado e visível para a equipe com a transparência de outra pessoa checar, também é o processo que vai utilizar para atualizar o código de um projeto já existe, tudo o que atualizou irá aparecer para o(s) dono(s) do projeto para revisar e aceitar, ou não, a alteração._  

Este passo irá gerar uma demanda para que eu, Luis Zancanela, possa verificar e aceitar, se a alteração estiver consistente com o que foi solicitado no passo 4, o Pull Request será aceito, senão será recusado com o devido feedback para que possa ser corrigido e refeito.  
Não se preocupe, após este passo, o desafio ainda vai continuar para que você também possa conhecer o lado de receber uma Pull Request para aprovação.

### ↪️ Passo 7 - Chegamos ao fim!?

Finalmente chegamos ao fim, mas como dito no passo anterior, após aprovar o Pull Request, eu, Luis Zancanela, irei criar uma Pull Request com um arquivo de congratulações por ter concluído com êxito o desafio, ou seja, ainda não é totalmente o fim, você terá a oportunidade de experimentar também como é receber um pull request de outra pessoa para verificar e aprovar, ou não!

> "O fim é o começo!"

------

## ☎️ Contato

Segue meu perfil do LinkedIn para conexão: https://www.linkedin.com/in/luis-carlos-zancanela/.  
Em caso de dúvidas, problemas ou sugestões é só entrar em contato no perfil acima.

## 👂 Feedback

Gostou? Não esqueça de deixar sua Star ⭐ no repositório e também não hesite em enviar sua opinião, se chegou até o último passo, pode aproveitar e aprender a abrir uma nova Issue, pense como um desafio bônus.

## 💎 Links úteis

Git: https://git-scm.com/downloads  
GitHub Desktop: https://desktop.github.com/  
Padrões para commits: https://medium.com/prolog-app/nossos-padr%C3%B5es-de-nomenclatura-para-branches-e-commits-fade8fd17106
Padrões para commits 2: https://dev.to/renatoadorno/padroes-de-commits-commit-patterns-41co

_Dica de segurança: Sempre verifique se a URL é do domínio correto antes de baixar qualquer aplicativo._
>"Não espere, ponha em prática!"

[didifive/desafio-git-github]: https://github.com/didifive/desafio-git-github