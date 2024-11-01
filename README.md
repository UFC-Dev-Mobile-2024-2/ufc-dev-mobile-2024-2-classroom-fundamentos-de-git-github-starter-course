[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Jp-8Am8F)
# :wave: Fundamentos Git e GitHub

## 🤓 Visão Geral do Curso e Resultados de Aprendizagem

O objetivo deste curso é oferecer uma breve introdução ao GitHub. Também forneceremos materiais para aprofundamento e algumas ideias para ajudá-lo a começar na nossa plataforma. 🚀

## :octocat: Git e GitHub

Git é um **sistema de controle de versão distribuído (VCS)**, ou seja, uma ferramenta útil para rastrear facilmente mudanças no seu código, colaborar e compartilhar. Com o Git, você pode rastrear as mudanças feitas em seu projeto, mantendo um registro do que foi trabalhado e permitindo reverter para uma versão anterior se necessário. Isso também facilita o trabalho em equipe, onde várias pessoas podem colaborar em um mesmo projeto e unir suas mudanças em uma fonte final!

O GitHub é uma forma de usar o poder do Git online, com uma interface fácil de usar. É amplamente utilizado no mundo do software e além, para colaborar e manter o histórico de projetos.

O GitHub abriga algumas das tecnologias mais avançadas do mundo. Seja para visualizar dados ou construir um novo jogo, há uma comunidade inteira e um conjunto de ferramentas no GitHub que podem ajudar você a dar o próximo passo. Este curso começa com o básico do GitHub, mas vamos explorar mais detalhes em breve.

## :octocat: Entendendo o fluxo do GitHub

O GitHub flow é um fluxo de trabalho leve que permite experimentar e colaborar em seus projetos facilmente, sem o risco de perder seu trabalho anterior.

### Repositórios

Um repositório é onde seu trabalho de projeto acontece – pense nele como a pasta do seu projeto. Ele contém todos os arquivos e o histórico de revisões do seu projeto. Você pode trabalhar em um repositório sozinho ou convidar outros para colaborar com você nesses arquivos.

### Clonagem 

Quando um repositório é criado no GitHub, ele é armazenado remotamente na ☁️. Você pode clonar um repositório para criar uma cópia local no seu computador e, em seguida, usar o Git para sincronizar os dois. Isso facilita a resolução de problemas, adicionar ou remover arquivos e realizar commits maiores. Você também pode usar a ferramenta de edição de sua preferência em vez da interface do GitHub. A clonagem de um repositório também baixa todos os dados do repositório que o GitHub possui naquele momento, incluindo todas as versões de cada arquivo e pasta do projeto! Isso pode ser útil se você quiser experimentar com seu projeto e depois voltar para uma versão anterior. Para saber mais sobre clonagem, leia ["Clonar um repositório"](https://docs.github.com/pt/repositories/creating-and-managing-repositories/cloning-a-repository). 

### Commit e Push

**Commit** e **push** são como você pode adicionar as mudanças feitas em sua máquina local ao repositório remoto no GitHub. Dessa forma, seu instrutor e/ou colegas de equipe podem ver seu trabalho mais recente quando você estiver pronto para compartilhar. Você pode fazer um commit quando tiver feito alterações no seu projeto e quiser fazer um "ponto de verificação". Também pode adicionar uma **mensagem de commit** para lembrar a si mesmo ou aos colegas de equipe sobre o que foi feito (por exemplo, “Adicionado README com informações sobre nosso projeto”).

Depois de ter um ou mais commits que você deseja adicionar ao repositório, você pode usar o comando push para adicionar essas mudanças ao repositório remoto. Comitar e fazer push podem parecer novos no início, mas prometemos que você se acostumará! 🙂

## 💻 Termos do GitHub para Conhecer

### Repositórios

Já mencionamos os repositórios, onde seu trabalho de projeto acontece, mas vamos falar mais sobre eles! À medida que você trabalha mais no GitHub, terá muitos repositórios, o que pode parecer confuso no começo. Felizmente, seu ["Painel do GitHub"](https://docs.github.com/pt/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) ajuda a navegar facilmente até seus repositórios e ver informações úteis sobre eles. Certifique-se de estar logado para visualizá-lo!

Repositórios também contêm **README**s. Você pode adicionar um arquivo README ao seu repositório para informar outras pessoas sobre a utilidade do seu projeto, o que podem fazer com ele e como usá-lo. Estamos usando este README para comunicar como aprender Git e GitHub com você. 😄
Para saber mais sobre repositórios, leia ["Sobre repositórios"](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/about-repositories) e ["Sobre READMEs"](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/about-readmes).


### Branches (Ramificações)

Você pode usar branches no GitHub para isolar o trabalho que você ainda não deseja mesclar ao projeto final. As branches permitem desenvolver recursos, corrigir bugs ou experimentar novas ideias em uma área separada do seu repositório. Tipicamente, você cria uma nova branch a partir da branch padrão do seu repositório – geralmente chamada de main. Isso cria uma nova cópia de trabalho do repositório para você experimentar. Depois que as novas alterações forem revisadas por um colega de equipe, ou quando você estiver satisfeito, poderá mesclar as mudanças na branch padrão do repositório.
Para saber mais sobre branches, leia ["Sobre Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks

Um fork é outra maneira de copiar um repositório, mas geralmente é usado quando você quer contribuir para o projeto de outra pessoa. O fork de um repositório permite que você experimente alterações sem afetar o projeto original, sendo muito popular ao contribuir com projetos de software de código aberto!
Para saber mais sobre forks, leia ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo).

### Pull Requests

Ao trabalhar com branches, você pode usar um pull request para informar aos outros sobre as mudanças que deseja fazer e solicitar feedback. Uma vez que o pull request é aberto, você pode discutir e revisar as possíveis mudanças com colaboradores e adicionar mais alterações, se necessário. Você pode adicionar pessoas específicas como revisores do seu pull request, indicando que deseja o feedback deles nas suas mudanças! Quando o pull request estiver pronto, ele pode ser mesclado na branch principal. Para saber mais sobre pull requests, leia ["Sobre Pull Requests"](https://docs.github.com/pt/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

### Issues (Problemas)

As issues são uma maneira de acompanhar melhorias, tarefas ou bugs no seu trabalho no GitHub. São ótimas para manter o controle de todas as tarefas que você quer realizar no seu projeto e informar aos outros sobre o que pretende trabalhar. Você também pode usar issues para informar um projeto de código aberto sobre um bug que encontrou ou sugerir um recurso interessante!

Para projetos maiores, você pode manter o controle de várias issues em um quadro de projeto. O GitHub Projects ajuda a organizar e priorizar seu trabalho. Você pode ler mais sobre isso em ["Sobre projects (classic)"](https://docs.github.com/pt/github/managing-your-work-on-github/about-project-boards). Provavelmente, você não precisará de um quadro de projeto para suas tarefas, mas ao avançar para projetos maiores, eles são uma ótima maneira de organizar o trabalho da equipe!
Você também pode vincular pull requests e issues para mostrar que uma correção está em andamento e fechar a issue automaticamente quando o pull request for mesclado.
Para saber mais sobre issues e vinculá-las aos seus pull requests, leia ["Sobre Issues"](https://docs.github.com/pt/github/managing-your-work-on-github/about-issues).

### Seu Perfil de Usuário

Sua página de perfil conta às pessoas a história do seu trabalho por meio dos repositórios de seu interesse, as contribuições feitas e as conversas em que participou. Você também pode dar ao mundo uma visão única sobre quem você é com seu README de perfil. Use seu perfil para informar potenciais empregadores sobre você!
Para saber mais sobre o perfil de usuário e como adicionar e atualizar o README do perfil, leia ["Gerenciar o README do seu perfil"](https://docs.github.com/pt/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).

### Usando Markdown no GitHub

Você já deve ter notado, mas é possível adicionar um pouco de estilo às suas issues, pull requests e arquivos. ["Markdown"](https://guides.github.com/features/mastering-markdown/) é uma maneira fácil de formatar seus conteúdos com uma sintaxe simples. Isso ajuda a organizar informações e torna mais fácil para outros lerem. Você também pode inserir gifs e imagens para expressar melhor o ponto que deseja transmitir!
Para saber mais sobre markdown no GitHub, leia ["Sintaxe básica de gravação e formatação no GitHub"](https://docs.github.com/pt/github/writing-on-github/basic-writing-and-formatting-syntax).

### Engajando com a Comunidade do GitHub

A comunidade GitHub é vasta. Há muitos tipos de pessoas que usam o GitHub no dia a dia, estudantes, como você, desenvolvedores profissionais, entusiastas que trabalham em projetos de código aberto e exploradores que estão começando no mundo do desenvolvimento de software. Existem várias maneiras de interagir com a comunidade GitHub, mas aqui estão três lugares onde você pode começar.

#### Favoritar repositórios

Se você encontrar um repositório interessante ou quiser acompanhá-lo, adicione uma estrela! Quando você estrela um repositório, isso também serve como um sinal para que o GitHub lhe forneça melhores recomendações em github.com/explore. Se quiser voltar aos seus repositórios estrelados, você pode fazer isso pelo seu perfil de usuário.
Para saber mais sobre favoritar repositórios, leia ["Salvar repositórios como favoritos"](https://docs.github.com/pt/github/getting-started-with-github/saving-repositories-with-stars).

#### Seguir usuários

Você pode seguir pessoas no GitHub para receber notificações sobre suas atividades e descobrir projetos em suas comunidades. Quando você segue um usuário, a atividade pública dele no GitHub aparecerá no seu painel para que você veja todas as coisas legais em que ele está trabalhando.
Para saber mais sobre seguir usuários, leia ["Seguir pessoas"](https://docs.github.com/pt/github/getting-started-with-github/following-people).

#### Navegar no GitHub Explore

O GitHub Explore é um ótimo lugar para fazer exatamente isso... explorar 😄 Você pode encontrar novos projetos, eventos e desenvolvedores com quem interagir.

Você pode acessar o site do GitHub Explore [em github.com/explore](https://github.com/explore). Quanto mais você interagir com o GitHub, mais personalizada será sua visualização no Explore.

## 📝 Passos da Tarefa

- [ ] Crie um novo arquivo markdown neste repositório. Compartilhe o que aprendeu e o que ainda causa dúvidas! Experimente estilos diferentes!
- [ ] Abra um pull request no seu repositório individual informando que concluiu este curso.

## 📝 Passos da Tarefa (para quem achou fácil a anterior)

- [ ] Resolver desafios do nível **Sequência Introdutória** de https://learngitbranching.js.org/?locale=pt_BR
- [ ] Resolver desafios do nível **Acelerando** de https://learngitbranching.js.org/?locale=pt_BR
- [ ] Resolver desafios do nível **Movendo trabalho por aí** de https://learngitbranching.js.org/?locale=pt_BR
- [ ] Resolver desafios do nível **Push & Pull -- repositórios remotos no Git!** de https://learngitbranching.js.org/?locale=pt_BR


## 📝 Atividades opcionais
- [ ] Crie o README do seu perfil. Mostre ao mundo um pouco mais sobre você! O que você está interessado em aprender? Em que está trabalhando? Qual o seu hobby favorito? Saiba mais sobre criar o README do perfil no documento, ["Gerenciar o README do seu perfil"](https://docs.github.com/pt/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
- [ ] Vá até o painel de usuário e crie um novo repositório. Experimente os recursos dentro desse repositório para se familiarizar com eles.
- [ ] Resolver desafios do nível **Sortidos** de https://learngitbranching.js.org/?locale=pt_BR&NODEMO=
- [ ] Resolver desafios do nível **Temas avançados** de https://learngitbranching.js.org/?locale=pt_BR&NODEMO=
- [ ] Resolver desafios do nível **Até a origin e além -- repositórios remotos avançados!** de https://learngitbranching.js.org/?locale=pt_BR&NODEMO=

## 📚 Recursos

* [Um vídeo curto explicando o que é o GitHub](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be)
* [Recursos de aprendizado sobre Git e GitHub](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources)
* [Entendendo o GitHub flow](https://guides.github.com/introduction/flow/)
* [Como usar branches no GitHub](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Materiais interativos de treinamento em Git](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Fórum da comunidade de Educação](https://education.github.community/)
* [Fórum da comunidade do GitHub](https://github.community/)

## 💻 Principais Comandos Git

`git clone <https://link-com-o-nome-do-repositório>` - clona um repositório

`git status` - verifica as alterações vigentes

`git add <arquivo>` ou `git add -A` ou `git add .` - adiciona arquivos

`git commit -m "mensagem do commit"`- commita as alterações prontas

`git push -u <local-remoto> <nome-da-branch>` - envia as alterações para um repositório remoto

`git push -u origin <nome-da-branch>`- normalmente o local reomoto é chamado de origin

`git pull <repositório-remoto>` - baixa as atualizações

`git merge` - mescla as alterações de duas branches

