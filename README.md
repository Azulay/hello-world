# hello-world
Mais uma vez fazendo um tutorial de Git para lembrar como funciona isso ...

# use GIT STATUS a qualquer momento para saber o que há no Staged Area
0. git status

# Clonar o repositório remoto
1. git clone https://github.com/Azulay/hello-world.git

# Acessar o diretório criado
2. cd hello-world/

# Nesse momento vai aparecer como se estivesse na branch "Master" (não é o ideal), então
3. git checkout -b issue01 # isso cria uma branch (-b) já com checkout, chamada "issue01"

# ADICIONAR coisas modificadas ao Staged Area
4. git add README.md

# Commitar as alterações
5. git commit -m "Primeiro commit com alterações"

#
6. git push

# SE não houver a branch no origin vai dar erro e terá que fazer
6. git push --set-upstream origin issue01 (Se não estiver logado vai aparecer a tela de login - no Windows)