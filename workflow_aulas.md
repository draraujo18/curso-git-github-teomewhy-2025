# Workflows

## Fluxo de trabalho - Aula 01 (USAR GIT STATUS APÓS QUALQUER PASSO ABAIXO DO 3)

1. criar o diretório do projeto (mkdir)
2. iniciar o git dentro do diretório criado (git init .)
3. edita ou cria arquivos
4. git status
5. adiciona os arquivos ao commit ('git add .' para todos os arquivos ou 'git add nome_arquivo' para adicionar um arquivo especifico)
6. commita os arquivos (git commit -m "mensagem para identificar facilmente à que se refere o commit)

## Fluxo de trabalho - Aula 02

1. Ao iniciar o trabalho, criar uma branch para mim					git branch -b <nome da branch>
2. Fazer merge com a main para puxar os arquivos disponíveis pra minha branch		git merge main
3. Fazer as alterações necessárias	 e commitar					git add .		git commit -m <"comentário sobre o commit">
4. Fazer merge da minha branch com a main para jogar as alterações lá			git checkout main	git merge <nome da branch>
5. Tratar erros, quando necessário.							abrir o arquivo, alterar o que for necessário, depois commitar normalmente.

## Fluxo de trabalho - Aula 03

### Git Local

1. git checkout -b <nova-branch>
2. cria ou atualiza arquivos
3. git status
4. git add *arquivos*
5. git status
6. git commit -m "mensagem para o commit"
7. git checkout main
8. git merge nova_branch

### GitHub Local (Projeto próprio ou da própria empresa)

1. git clone <endereço do projeto>
2. git checkout -b <nova_branch>
3. alterações de arquivos
4. git status
5. git add *arquivos*
6. git status
7. git commit -m "mensagem para o commit"
8. git push origin <nova_branch>
9. abrir Pull Request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

### GitHub Local (Projeto open)

0. fork do projeto
1. git clone <endereço do projeto fork>
2. git checkout -b <nova_branch>
3. alterações de arquivos
4. git status
5. git add *arquivos*
6. git status
7. git commit -m "mensagem para o commit"
8. git push origin <nova_branch>
9. abrir Pull Request no GitHub da branch fork para a main do projeto original 
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

