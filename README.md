# Curso TMW Git & GitHub 2026 

Um curso para iniciantes aprenderem a trabalhar co versionamento de código e repositórios remostos com GitHub.


## Fluxo de trabalho Git local

1. git checkout -b <nova-branch>
2. cria ou atualiza arquivos
3. git status
4. git add "arquivos"
5. git status
6. git commit -m "minha mensagem"
7. checkout main
8. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)
1. git clone <endereço do projeto>
2. git checkout -b <nova_branch>
3. alterações de arquivos
4. git stauts
5. git add "arquivos"
6. git status
7. git commit -m "nova mensagem"
8. git push origin <nova_brach>
9. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

