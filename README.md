# Instalation
https://git-scm.com/download

# Enviroment
- [x] Iniciar linha do tempo de seu projeto. (Init)

- [x] Criar arquivos direto no seu projeto. (Touch)

- [x] Criar pontos na história da produção do seu projeto. (Add; Commit)

- [x] Verificar mudanças feitas no seu projeto. (Status; Log; Show)

- [x] Criar nova funcionalidade no seu projeto, sem alterar original. (Branch)

- [x] Adicionar novas funcionalidades ao seu projeto em produção. (Merge)

- [x] Deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

- [x] Colocar seu projeto na nuvem "GitHub". (Criar repositorio)

- [x] Pegar um projeto já iniciado, para trabalhar com o time. (Fork; Clone)

- [x] Resolver um conflito.

- [x] Antes de enviar a resolução, precisamos atualizar o projeto local.

- [x] Voltar um arquivo para um determinado momento da linha do tempo.

- [x] Recuperar algo deletado.


# General
- `git init` // inicia a linha do tempo
- `touch` // cria arquivos na pasta do projeto local
- `git add` // adiciona ou atualiza mudanças para irem para a linha do tempoo
- `git commit` // adiciona um ponto na linha do tempo
- `git log` // visualiza os pontos na linha do tempo / commit
- `git status` // informa o estado das alterações do nosso projeto
- `git show` // apresenta determinado ponto na história
- `git branch` // gerenciar novas linhas do tempo
- `git checkout` // manipula as linhas do tempo
- `git merge` // unir linhas do tempo
- `git push` // envia alterações locais para o repositório remoto
- `git clone "LINK DO REPOSITÓRIO"` // clonar um projeto / repositório
- `git pull` // puxa do repositório remoto
- `git remote add origin "LINK DO REPOSITÓRIO"` // subir projeto na nuvem "GitHub"
- `git remote -v` // verifica os repositorios ativos
- `git vim` // acessa codigo do arquivo para editar
- `git diff` // mostra o que foi alterado
- `cat "Arquivo"` // mostra o conteudo do arquivo
- `rm -rf "Arquivo/Pasta"` // deleta o arquivo ou pasta

# Detailed
- `add "File"` // prepara arquivo para adicionar na branch "Linha do Tempo"
- `add .` // prepara TODOS arquivos para adicionar na branch "Linha do Tempo"
- `git commit "Arquivo" -m "Mensagem"` // adiciona o arquivo especifico na branch "Linha do Tempo"
- `git commit . -m "Mensagem"` // adiciona o arquivo especifico na branch "Linha do Tempo"
- `git commit -am "Mensagem"` // prepara e adiciona o arquivo especifico na branch "Linha do Tempo"
- `q` // sair do comando "git log"
- `clear` // limpar terminal git
- `ls -al` // lista todos arquivos dentro da branch "Linha do Tempo"
- `git log -"NUMERO"` // lista uma quantidade especifica de commit realizado
- `git branch -d "Branch"` // deletar as linhas do tempo
- `git push -u origin master` // enviar arquivos para o repositorio "GitHub"
- `git config credential.helper store` // salva o login do GitHub toda vez que executa um "git push"
- `git checkout -b "NOME DA BRANCH"` // cria a branch e faz sai da branch que está automático
- `git checkout "ID LOG" -- "NOME DO ARQUIVO"` // recupera arquivos naquela determinada linha do tempo
- `Shift + Arrow Down + :wq` // sair da edição do arquivo 


# Libraries
- `yarn add "NOME DA BIBLIOTECA"` // instala uma biblioteca especifica
- `touch .gitignore"` // ignora as pastas rastreadas adicionando o caminho delas que foram criadas pela instalação da biblioteca