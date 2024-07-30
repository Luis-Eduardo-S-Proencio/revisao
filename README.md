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

#### FUNÇÕES/MÉTODOS ####

Uma função evita a repetição de código, pois sempre que aquele código é necessário, ele pode ser invocado/chamado a partir da função. Deixa o código mais organizado e significativo.

Um bloco de código nomeado, que pode ou não conter parâmetros/argumentos e pode ou não conter um retorno.

# Parâmetro

É a variável que quem invoca a função dispõe para ela, o parâmetro/argumento modifica o comportamento da função.

# Retorno

É o resultado (valor) que função retorna para quem a invocou

# function declaration

f1() //invoco a função antes de declará - la/ funciona

function f1(<os parametros vem aqui>){
    //qualquer código
    return //O retorno sempre é opcional, e pode ser de qualquer tipo 
}

# function expression

f2() //vai quebrar o código, acessando umaa variavel antes de defini la 

//funcao anonima
const f2 = function(<os parametros vem aqui>){
    //qualquer código
    return // o retorno sempre é opcional, e pode ser de qualquer tipo
}

f3()

//arrow function
const f3 = (<os parametros vem aqui>) => {
    //qualquer código
    return// o retorno sempre é opcional e pode ser de qualquer tipo 
}

// se apenas houver um parametro, pode se remover os parentes
//também se houver apenas uma linha de código, pode se remover a declaração do bloco

const f4 = arg => console.log(arg)

# MÓDULOS
Módulo é um arquivo que contém código. Utilizado para organizar a aplicação/software em uma estrutura mais lógica e significativa.

Os módulos/arquivos por padrão nçao se comunicam entre si, deve-se utilziar funções para exportar e importar o código de outro arquivo.

# Importar

//coloca o código exportado do arquivo modulo.js na variável mod
const mod = require(" ./modulo.js") // o .js em node é opcional

# Exportar

module.exports = {
    //exportando a função/variavel f1, onde outros arquivos poderão utiliza la agora f1,
}

# NPM 

Gerenciador de pacotes do Node

# Pacote 

Código javascript externo













