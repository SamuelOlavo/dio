##Comandos básicos do GIT                  [Manual](https://gist.github.com/leocomelli/2545add34e4fec21ec16 )

Iniciando um repositório:
git clone
git init

Checando o estado dos seus arquivos:
git status

Checando o que foi alterado nos arquivos:
git diff
git diff <arquivo>
git diff --check(checa por espaços em branco)

Adicionando arquivos para a área de seleção (salva mudanças feitas ):
git add . (adiciona todos os arquivos modificados)
git add <arquivo> (adiciona arquivo específico)

Move arquivos da área de seleção para a área de envio:
git commit -m "<mensagem>"

Muda de branch ao mesmo tempo que cria um:
git checkout -b <nome-do-branch>

Enviar arquivos/diretórios para o repositório remoto
O primeiro push de um repositório deve conter o nome do repositório remoto e o branch.
git push -u origin master

Os demais pushes não precisam dessa informação
git push
