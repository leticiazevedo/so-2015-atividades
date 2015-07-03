======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Letícia Nunes Azevedo  
:Matrícula: 20121144010060
:Data: 01/07/2015

cat
  Serve para criar um novo arquivo, concatenar e imprimir um conteúo na tela. Ex.: $ cat > arquivo (cria um novo arquivo); cat x.txt y.txt > z.txt (Coloca x e y juntos em um arquivo z)


cd
  Usado para acessar ou mudar de diretório. Ex.: cd /usr/bin


cowsay
  Exibe mensagem com desenhos variádos em ascii. Ex.: cowsay -f dragon "Olá"; cowsay -L (exibe todos os animais disponíveis)


echo
  A função deste comando é exibir mensagens na tela. Ex.: echo "$PATH" (exibe todos os nomes de arquivos de um diretório em ordem alfabética); echo "$PATH" (verifica o conteúdo da variável de ambiente PATH)



env
  Este comando é ultilizado para exibir as variáveis de ambiente. Ex.: env

exit
  Encerra sessão, a shell. Ex.: exit


help
  Mostra o arquivo de ajuda do comando que você digitou. Ex.: help


HISTTIMEFORMAT="%d/%m/%y
  Exibe o histórico com as datas. Ex.: $ echo 'export HISTTIMEFORMAT="%d/%m/%y %T "' >> ~/.bash_profile


hostname
  Comando que exibe o nome da máquina. Ex.: hostname


ifconfig
  Visualizar os ips da nossa máquina, entre outras funções relacionadas com ips. Ex.: ifconfig -a (exibe informações sobre todas as interfaces de rede)


last
  Exibe o ultimo login do usuário.


lastb
  Exibe todas asconexões já feitas pelo usuário.


ls
  Lista os arquivos existentes em um determinado diretório. Ex.: ls /usr/bin


mkdir
  Cria um novo diretório. Ex.:  mkdir $USER


nome="fulano
  Cira e atribui um valor a uma determinada variável. Ex.: nome="Leticia", echo $nome


passwd
  Este comando é ultilizado para mudar a senha do usuário ou do grupo. Ex.: passwd leticia -g (altera a senha do usuário, entretanto, somente o usuário root pode o fazer)


pwd
  Verifica em que diretório o usuário está.


set
  Define as variáveis da sessão.


tree
  Exibe a 'árvore' de processos que estão sendo executados.


tty
  Mostra o nome do arquivo conectado à entrada padrão.


vim
  Trata-se de um editor de texto, basicamente abre um arquivo e o edita.
  

wait
  Espera que um comando seja executado para que possa executar o restante.


wall
  Escreve uma mensagem para outros usuários. Ex.: wall /tmp/mensagem.txt, echo Testando|wall


which
  Exibe o caminho completo na hierarquia de diretorios para os comandos do sistema. Ex.: which sh


while
  Laço de repetição.


who
  Exibe os usuários logados na máquina.


whoami
  Mostra o nome do usuário atual.


    write
      Escreve para outros usuários que estejam logados no momento.
