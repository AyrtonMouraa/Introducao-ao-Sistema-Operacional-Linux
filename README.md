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
 
# ***Fudamentos de Redes e Comandos de Rede***

- *Exibe informações sobre interface de rede e IP:* **ifconfig**
- *Exibe informações sobre o host:* **hostname**
- *Exibe o número de endereços loopback do host:* **hostname -i**
- *Exibe endereço de IP na rede:* **hostname -l**
- *Exibe informações sobre o DNS de um host:* **dig host**
- *Exibe o numero de IP de um host:* **dig host +short** 
- *Exibe informações detalhadas sobre o usuário do computador na rede:* **w**
- *Exibe informações curtas sobre o usuário do computador na rede:* **who**
- *Exibe o numero de usuários do computador na rede:* **whoami**
- *Exibe informações sobre a rota da sua rede até o host desejado:* **traceroute host**
- *Testa um host:* **ping host**
- *Exibe informações sobre o usuário do computador na rede:* **finger**

# ***Comandos Diversos do Linux***
 
 - *Exibe arquivos e diretórios ocultos:* **ls-a**
 - *Exibe os diretórios com / no fim:* **ls-f**
 - *Exibe um arquivo com seus números de linhas:* **nl** 
 - *Conta o número de linhas de um arquivo incluindo as em branco e exibe no terminal:* **wc -l**
 - *Conta o número de palavras de um arquivo e exibe no terminal: **wc -c**
 - *Organiza um arquivo em ordem alfabética ou númerica:* **sort**
 - *Exibe o tempo do processamento de um comando para o sistema, para o usuário e real:* **time**
 - *Exibe informações de carregamento do sistema:* **uptime**
 - *Compara dois arquivos:* **cmp**
 - *Imprime uma sequência de números com inicio e fim:* **seq**
 - *Exibe a tabela de roteamento IP do kernel:* **route -n**
 - *Permite trocar o nome de um comado:* **alias**
 - *Exibe informações sobre reinicializações do sistema:* **fast reboot**
 - *Limpa o histórico de comandos:* **history -c**
 - *Desliga o sistema:* **init 0**
 - *Desliga o sistema:* **telinit 0**
 - *Desliga o sistema:* **halt**
 - *Exibe o caminho do programa e seu manual:* **whereis**
 - *Exibe o caminho de um programa:* **which**
 - *Finaliza sessão:* **logout**
 - *Comando para animação da vaquinha:* **cowsay "linux é bom"**
 - *Comando para animação da vaquinha:* **cowsay -d**
 - *Comando para animação da vaquinha:* **cowsay -g**
 - *Comando para animação da vaquinha:* **cowsay -f**
 - *Comando para animação do pinguim:* **cowsay -f tux**
 - *Comando para animação do pinguim:* **cowsay -f vader**
 - *Comando para animação do pinguim:* **cowsay -f vader-koala**
 - *Comando para animação do pinguim:* **cowsay -f dragon**
 - *Comando para animação "3D":* **xcowsay "linux"**
 - *Comando para animação do matrix:* **cmatrix**
 - **OBS:** *As Letras com cor azul é diretório e com as letras são arquivos*

# ***Controle de Usuários, Grupos e Permissões***

- *Adiciona um usuário:* **adduser***
- *Troca para o usuário root:* **sudo su**
- *Troca para outro usuário:* **su usuario**
- *Troca senha do usuário:* **passwd**
- *Exibe informações de login dos usuários:* **lastlog**
- *Exibe uma listagem de entrada e saída do usuário no sistema:* **last**
- *Exibe o nome do usuário atual logado no sistema:* **logname**
- *Exibe todos os identificados do usuário:* **id**
- *Exibe todos os usuários:* **cat /etc/passwd:**
- *Remove o usuário e sua pasta pessoal:* **userdel -r nomedousuario:**
- *Exibe todos os grupos do sistema:* **cat /etc/group**
- *Adiciona um usuário a um grupo:* **adduser usuario grupo**
- *Adiciona um usuário a um grupo:* **gpasswd -a usuario**
- *Remove um usuário de um grupo:* **gpasswd -d usuario grupo**
- *Remove um grupo:* **groupdel grupo**
- *Exibe detalhes na listagem de um diretório como permissões:* **ls -lh**
- *Permite a modificação de permissões:* **chmod**

# ***Compactação, Descompactalção e Arquivamento***

- *Cria um arquivo compactado do tipo gz:* **gzip**
- *Descompacta um arquivo do tipo gz:* **gunzip**
- *Cria um arquivo compactado do tipo zip:* **unzip**
- *Cria um arquivo compactado do tipo rar:* **rar**
- *Descompactada um arquivo do tipo rar:* **rar -x**
- *Cria um arquivo compactado do tipo bz2:* **bzip2**
- *Descompacta um arquivo do tipo bz2:* **bzip2 -d**
- *Arquiva um ou mais arquivos:* **tar**
- *Descompacta um arquivo compactado e arquivado:* **tar -xvf** 
- *Apagar um arquivo compactado com o nome repetido:* ** rm -r nomedoarquivo* **
- *Apagar um arquivo compactado que tenha zip:* **rm -r *zip** *OBS:PODE FAZER ISSO PARA TODOS*

# ***Atalhos*** 

- *Cancela o comando atual em funcionamento:* **Ctrl+C**
- *Pausa o comando atual, em primeiro plano ou segundo plano:* **Ctrl+Z**
- *Faz o logout da sessão atual:* **Ctrl+D**
- *Apaga uma palavra na linha atual:* **Ctrl+W**
- *Apaga linha inteira:* **Ctrl+U**
- *Busca um comando recente:* **Ctrl+R**

# ***Site***
- *Guia foca:* https://www.guiafoca.org/guiaonline/
- *JSLinux:* https://bellard.org/jslinux/
- *PKGS Search:* https://pkgs.org/
- *Rpm search:* https://rpm.org/
