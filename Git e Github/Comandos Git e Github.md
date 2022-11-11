# GIT/GITHUB :exclamation:

### Comandos:

1. openssl sha1 "conteúdo": Comando para criar um hash do arquivo em "sha1", garantindo que o conteúdo não sofreu alterações.
2. echo 'conteúdo' | git hash-object --stdin:
3. ssh-keygen -t ed25519 -C "e-mail": Comando para criar par de chave pública e privada.
4. cat "id_ed25519.pub": Comando Cat mais a chave pública para abrir a chave e depois copiar e colar ela no GIT HUB.
5. eval $(ssh-agent -s): Comando para habilitar o agente para usar as key de criptografia.
6. ssh-add "id_ed25519": Comando para adicionar no agente a chave privada.
7. git init: Comando para criar e inicializar o git dentro do repositório
8. git config --global user.email "e-mail": Comando para configurar o e-mail dentro do git.
9. git config --global user.name "Nick": Comando para configurar nick dentro do git.
10. git status: mostra os status
11. git add "nome do arquivo": Adiciona um arquivo que estava Untracked para Staged.
12. git add *: Adiciona todos os arquivos para Staged.
13. git commit -m "msg..": passa todos os arquivos do Staged criando um Commit.
14. git config --list: lista toda configuração do git.
15. git config --global --unset user.email: para remover associado ao git.
16. git config --globak --unset user.nickname: para remover o nick associado ao git.
17. git clone (link https do github): para criar um repositório dentro do GIT

