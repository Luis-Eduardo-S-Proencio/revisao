# revisao
revisao para

# repositorio

A pasta do projeto imbuida com o software git, que contem os arquivos e o historico do projeto de alteração de projeto

# GitHub

Hospedagem de repositório (GitHub,GitLab e BitBucket).

# Branches (Galhos ou Ramificações)

Linha de desenvolvimento paralela/independente do projeto/repositório, (existe apenas em um projeto git), muito utilizada para o desenvolvimento em equipe, para um não afetar ou alterar o trabalho do outro.

# Git

ferramenta de software para versionamento/controle de versões de um projeto qualquer, quando se cria um projeto git, se cria automaticamente um repositório.

# comandos do git
`git clone`: clona um repositório remoto (nesesse curso, no GitHub) e cria uma pasta local (inicializado um repositório local copm o git)

`git add <nome-do-arquivo> `: Seleciona os arquivos que vão ser salvos nos próximos.

`git commit -m "<mensagem-do-commit>"`:  É a forma de salvar as alterações feitas no repositório/branch onde o usuário está trabalhando (modificando arquivos), i gut cinnut aiebas sakva as alterações selecionadas pelo git commando git add.

`git status`: Mostra para o usuário o estado atual (as mudanças feitas/selecionadas) do galho onde o usuário está trabalhando.

`git branch <nome-do-galho>`: Cria um novo galho de desenvolvimento no repositório atual.

`git branch`: Lista os galhos do repositório, e também mostra em qual galho você está.

`git checkout <nome da branch>`: Mudar para o galho escolhido.

`git branch - d <nome da branch>`: Remove o galho escolhido do repositório que o usuário está trabalhando.

`git push -u origin <nome-da-branch>`: Envia as alterações do local para o repositório remoto.

`git pull origin <nome-da-branch>`: Faz o download das alterações do galho indicado no comando, as alterações são realizadas no galho atual do usuário.

`git init`: Cria um repositório local (repo inicial denominado master, não é igual ao GitHub que cria como main).(não é tão utilizado)

`git merge <nome-do-galho>`: "Junta as alterações do galho indicado no galho atual".

# Pull Request

ele é um pedido de merge dentro do repositório remoto (GitHub), se caso esse pedido de merge for aceito, resultará no merge dos galhos envolvidos.