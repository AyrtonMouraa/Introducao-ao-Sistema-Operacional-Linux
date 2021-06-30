# Introdução ao Sistema Operacional Linux
***Linhas e Comandos Citados no Curso para Desenvolvimento Pesssoal***
  
# ***Ubuntu*** 

***Primeiros Comandos***
       
 **O Terminal Pode ser aberto de diversas formas, mas a sequência de teclas CTRL + ALT + T facilita seu acesso.**    

- *Para retornar rotacionar a sua tela:* **xrandr -o normal**
- *Para acessar o usuário root:* **sudo su**
- *Para saber a saida do caminho local:* **pwd**
- *Para listar arquivos:* **ls**
- *Para visualizar alguma arquivo que esteja dentro de uma pasta:* **ls (nome da pasta)**
  *ex:* **ls Documentos**
- *Para mudar de diretório:* **cd (nome do diretório)**
  *ex:* **cd Documentos**
- *Para criar novos pastas:* **Mkdir (nome da pasta)**
  *ex:* **Mkdir linux**
- *Para retorna um diretório anterior:* **cd ..**
- *Para retorna ao diretório raiz:* **cd /**
- *Para listar diretórios e arquivos com detalhes:* **ls -l**
- *Para listar o manual de algum comando:* **man (comando)**
     *ex:* **man ls**
- *Para o trazer o arquivo de ajuda em português:* **--help**
   *ex:* **ls -- help**
- *Para voltar ao diretório pessoal:* **cd ~**
- *Para exibir o histórico de programas e comandos utilizados no terminlal: history*
- *Para executar o ultimo comando utilizado no terminal:* **!!**
- *Repete o último comando:* **!!**
- *Faz o logout da sessão atual:* **Exit**
- *Lista diretórios e arquivos: ls
- *pção lista longa "com detalhes":* **ls-l**
- *Lista outro diretório que não o corrente:* **ls dir**
- *Histórico de comandos:* **history**
- *Cria diretórios:* **mkdir**
- *Remove diretórios com a opção -r:* **rm -r**
- *Muda o diretório atual para outro:* **cd dir**
  *EX:* **cd /Ayrton**
- *Muda para o diretório raiz:* **cd /**
- *Muda para o diretório pessoal(home):* **cd ~**
- *Retorna ao diretório anterior:* **cd ..**
- *Exibe o arquivo de ajuda de um comando:* **--help** 
  *EX:* **ls --help**
- *Exibe o manual do comando:* **man comando**
  *EX:* **man ls**
- *Renomea um diretório ou arquivo:* mv antigo novo
  *EX: **mv linux teste**
- *Move um diretório ou arquivo:* **mv dir/ ~**
- *Cria arquivos vazios no linux: **touch nomearquivo**
- *Faz uma cópia de um arquivo para outro diretório:* **cp arquivo diretório**
- *Especifico para remover diretórios:* **rmdir**
- *Remove um arquivo:* **rm nomearquivo**
  *EX:* **rm teste.txt**
- *Limpa o terminal:* **clear**
- *finaliza sessão do terminal:* **exit**

# ***Comandos para Manipulação de Arquivos e Textos e Redirecionamento***

- *Exibe Contéudos de arquivos no terminal:* **cat**
- *Exibe a ordem inversa dos contéudos no terminal:* **tac**
- *Editor de textos linux:* **nano**
- *Cria arquivos vazios:* **touch**
- *Busca arquivos:* **find**
- *Exibe o tipo de um arquivo:* **file**
- *Exibe as 10 primeiras linhas de um arquivo:* **head**
- *Exibe as 10 ultimas linhas de arquivo:* **tail**
- *Exibe a paginação em um arquivo de texto:* **more**
- *Exibe a paginação em um arquivo de texto:* **less**
- *Busca palavras em arquivos texto:* **grep**
- *Exibe calendário:* **cal**
- *Exibe a data atual:* **date**
- *Exibe uma explicação sobre um comando:* **whatis**
- *Envia a saída de um comando para entrada de outro comando permitindo a execução de dois comandos:* **|**
- *Redireciona a saída de um comando para outra comando ou arquivo:* **>**
- *Redireciona a saída e adiciona a mesma para um comando ou arquivo:* **>>**
- *Direciona a entrada de um arquivo para a saída de um comando:* **<**
- *Este operador permite usar dois comandos e separar suas saídas no terminal:* **&**
- *Usado para que dois comandos só sejam executado se o primeiro for executado com sucesso:* **&&**
- *Para remover todos os arquivos dentro de uma pasta:* **rm -r** 
                
# ***Comando de Diretórios do Linux e Comandos de Sistema***

- *Binários principais dos usuários:* **/bin/**
- *Arquivos do sistema de boot:* **/boot/**
- *Arquivos de dispositivos:* **/dev/
- *Arquivos de configuração do sistema:* **/etc**
- *Diretório dos usuários comuns do sistema:* **/home/**
- *Blibliotecas essenciais do sistema e os módulos do kernel:* **/lib/**
- *Diretório de montagem e dispositivos:* **/media/**
- *Diretório de montagem de dispositivos - mesmo que "media":* **/mnt/**
- *Instalação de programas não oficiais da distribuição ou por conta do usuário:* **/opt/**
- *Armazena arquivos executáveis que representam comandos administrativos. exemplo: Shutdown:* **/sbin/**
- *Diretório para dados de serviços fornecidos pelo sistema:* **/srv/**
- *Diretório para arquivos temporários:* **/tmp/**
- *Segunda hierarquia do sistema, onde ficam os usuários comuns do sistema e programas:* **/usr/**
- *Diretório com arquivos variáveis gerados pelos programas do sistema. exemplo: logs, historico da impressora, e-mail e cache.:* **/
- *Diretório do usuário root - o usuário root tem o total poder sobre o sistema. podendo instalar, desinstalar e configurar.:* **/root/
- *Diretório virtual controlado pelo kernel:* **/proc/**
- *Arquivo de informação do processador:* **cat/proc/cpuinfo**
- *Exibe informações do processador:* **lscpu**
- *Arquivo de informações da memória:* **cat/proc/meminfo**
- *Exibe informações da memória física o virtual:* **free**
- *Exibe informações detalhadas sobre hardware:* **lshw**
- *Exibe informações sobre hardware:* **lshw -short**
- *Exibe o nome do kernel do sistema:* **uname**
- *Exibe a versão do kernel:* **uname -r**
- *Exibe a arquitetura do kernel:* **arch**
- *Exibe todas as placas PCI conectadas:* **lspci**
- *Exibe todos os dispositivos usb conectados:* **lsusb**
- *Exibe o espaço que cada arquivo e pasta no diretório pessoal consome no hd:* **du -h ~
- *Renicia o sistema:* **reboot**
- *Renicia o sistema:* **shutdown -r**
- *Desliga o sistema rapidamente:* **shutdown -h now**
- 


# ***Atalhos*** 

- *Cancela o comando atual em funcionamento:* **Ctrl+C**
- *Pausa o comando atual, em primeiro plano ou segundo plano:* **Ctrl+Z**
- *Faz o logout da sessão atual:* **Ctrl+D**
- *Apaga uma palavra na linha atual:* **Ctrl+W**
- *Apaga linha inteira:* **Ctrl+U**
- *Busca um comando recente:* **Ctrl+R**

# ***Site***
- *Guia foca:* https://www.guiafoca.org/guiaonline/

