# Kernel Linux :penguin:



#### COMANDOS

1. (bcdedit), (bcdedit /set): Comando no cmd para checar se a virtualização está ativa no Windows, hypervisorlaunchtype.
2. (ip a): para ser exibido todos ips do computador.
3. (apt-get install): comando para instalar recursos.
4. (ssh nomedamáquina@ip): Comando para acesso remoto linux para outro sistema.
5. (ssh -i chave.pen nomedamaquina@ip): Comando para acesso remoto do linux para maquina na AWS.
6. (date): Exíbe data e hora.
7. (pwd):Endica onde você está dentro do terminal.
8. (cd ..) Volta um diretório atrás ou antes.
9. (cd ../nomedodiretório) comando para voltar um diretório já entrando dentro de outro arquivo específicado.
   (ls | more): lista de arquivos com barra de rolagem, para pesquisa.
10. (ls a*) Buscar o arquivo com a letra escolhida e suas subpastas.
11. (touch) criação de arquivos.
12. (find -name) Comando para busca de qualquer arquivo, pasta etc... 
13. (mkdir) Comando para criar diretórios.
14. (mkdir 'exemplo') Comando mkdir com nome entre aspas para criar diretórios com espaço exp: 'Meus Documentos'.
15. (rmdir) Comando para excluir diretórios.
16. (rm) Comando para excluir arquivos.
17. (rm -rf) Comando para forçar e excluir todo diretório e arquivos que estiverem lá dentro.
18. (ls -l) Formato de lista longa.
19. (ls -a) visualizar todos arquivos ocultos.
20. (ls -lh) verificar tamanho dos arquivos e diretórios.
21. (su) comando para entrar em outro usuário
22. (systemctl status) Comando para verificar log e status de algum programa.
23. (systemctl restart) reiniciar um serviço.
24. (cat) visualiza o conteúde de um arquivo.
25. (history) comando para visualizar todos os comandos usados recentemente.
26. (history | grep "exp") comando junto com grep para visualizar quais comando selecionados foram usando recentemente. Exp: history | grep "ls".





#### **FERRAMENTAS**

 [PuTTy] [PuTTygen]: Ferramenta para acesso remoto do Windows para Linux. (https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)



#### **RECURSOS**

1. Painel de controle>Programas>Ativar ou Desativar Recursos> Ativar plataforma do Hipervision do Windows.
2. (openssh) recurso instalado pelo terminal para abilitar o acesso remoto. Ex:(apt-get install openssh-server)
3.(nano) comando para edição de texto e arquivos.
4.(export HISTTIMEFORMAT="%c ") Comando para abilitar dentro do history hora e data de quando os comando foram usados





