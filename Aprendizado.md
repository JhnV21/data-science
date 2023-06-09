## Git e Versionamento

### Comandos Git

- Nome de Usuário: `git config --global user.name "NOME"`
- Email: `git config --global user.email SEUEMAIL@EMAIL.com`
- Clonar Repositório: `git clone LINK REPOSITÓRIO`
- Criar Repositório: `git init`, dentro da pasta que deseja iniciar o repositório.
- Status: `git status`, para saber o status dos arquivos.
- Stage: `git add ARQUIVO`, para preparar o arquivo para commit.
- Mudanças: `git diff`, para saber quais foram as mudanças no código.
- Commit: `git commit -m "MENSAGEM"`
- Histórico: `git log` / pressionar a tecla "q" para sair do Git Log
- Remover mudanças após git add: `git restore NOME ARQUIVO`
- Voltar arquivo de Staged para Changes: `git restore --staged NOME ARQUIVO` ou `git restore -s NOME ARQUIVO`
- Saber o "remote": `git remote`
- Enviar ao Repositório Remoto: `git push`, depois de push colocar o resultado de `git remote` e a branch que esta trabalhando.
- Puxar coisas do Repositório Remoto: `git pull`, atualiza meu repositório local com as modificações feitas do repositório remoto.
- Verificar atualização: `git fetch`, usando `git diff NOME DO REMOTE/BRANCH QUE ESTA TRABALHANDO` após git fetch, voce consegue verificar oque vai ser mudado, antes do git pull.
- Criar nova Branch: `git branch NOME BRANCH`
- Saber a branch que esta: `git log --oneline --decorate`, olhar aonde HEAD esta apontando.
- Mudar a branch: `git checkou NOME BRANCH`
- Juntar os códigos de branch separadas: `git merge BRANCH QUE QUERO JUNTAR`