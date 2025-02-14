# COMANDOS BÁSICOS DO GIT 
`git config --global user.name "Seu nome"` -> Inclui a credencial do seu nome 
`git config --global user.email "seu_email@EXAMPLE.COM"` -> Inclui a credencial do seu e-mail.
`git init` -> inicializa o repositório local.
`git status` -> Exibe se os arquivos ou pastas estão adicionados ao repositório.
`git add nome_do_arquivo` -> Você adiciona o arquivo ao repositório local.  
`git add` . -> Você adiciona todos os arquivos modificados/criados no repositório local
`git branch -M main` -> Altera o nome da branch principal de Master para Main.
`git commit -m "Mensagem de atualização"` -> Cria um commit para que seja realizado um novo versionamento.
`git log` -> Lista todos os commits que foram realizados.
`git log` --oneline --graph --decorate -> Forma compacta de exibir os commits
`git remote add origin https://github.com/clarabizoni/senacshoes.gi`t -> Realiza a sincronização do repositório local com o remoto.
git push -u origin main -> Envia as informações do repositório local para o remoto