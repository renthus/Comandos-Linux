# Comandos-Linux <img align="center" alt="Renato-python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg">

### Comando `cd` <br>
> Ação: faz a mudança de diretório <br>
> Ex.: `root@comandoslinux:~# cd /`.

### Comando: `/` <br>
> Ação: é a raíz do sistema. <br>
> Ex.: `root@comandoslinux:~# cd /`.

### Comando: `whoami` <br>
> Ação: identifica quem é o usuário ativo. <br>
> Ex.: `root@comandoslinux:~# whoami`.

### Comando: `pwd` <br>
> Ação: exibe o caminho em que o usuário ativo está. <br>
> Ex.: `root@comandoslinux:~# pwd`.

### Comando: `ls` <br>
> Ação: listagem do conteúdo de um diretório. <br>
> Ex.: `root@comandoslinux:~# ls` | `root@comandoslinux:~# ls -lah`.

### Comando: `history` <br>
> Ação: mostra o histórico dos comandos digitados. <br>
> Ex.: `root@comandoslinux:~# history` <br>
> Aplicação: depois de exibir o histórico, vc digita ! + número do comando. <br>
> Ex.: `root@comandoslinux:~# !10`.

### Comando: `type` <br>
> Ação: identifica o tipo de comando. <br>
> Ex.: `root@comandoslinux:~# type whoami` <br>
> Aplicação: para saber se o comando é `embutido no núcleo (kernel)` ou do `Sistema Operacional`.

### Comando: `man` <br>
> Ação: mostra o manual do comando. <br>
> Ex.: `root@comandoslinux:~# man ls` <br>
> Aplicação: para ter acesso ao manual de um determinado comando. <br><br>
> Observação:<br>
> (1) Para instalação de pacotes no Debian: `root@comandoslinux:~# apt install man-db`.

### Comando: `info` <br>
> Ação: retorna alguns exemplos do comando. <br>
> Ex.: `root@comandoslinux:~# info whoami` <br>
> Instalação: `root@comandoslinux:~# sudo apt install info`.

### Comando: `help` <br>
> Ação: retorna uma ajuda rápida do comando. <br>
> Ex.: `root@comandoslinux:~# ls --help`.

### Comando: `locate` <br>
> Ação: localiza todas as ocorrências com um determinado nome pesquisado. <br>
> Ex.: `root@comandoslinux:~# locate <nome a ser pesquisado>`. <br>
> Instalação: `root@comandoslinux:~# sudo apt install locate`. <br>
> Atualização: `root@comandoslinux:~# sudo apt updatedb`.

### Comando: `.` <br>
> Ação: local **atual** do diretório onde você está. <br>
> Ex.: `root@comandoslinux:~# <comando> .`.

### Comando: `..` <br>
> Ação: local do diretório **anterior** onde você está. <br>
> Ex.: `root@comandoslinux:~# cd ..`.

### Comando: `-` <br>
> Ação: retornar ao último diretório onde você estava. <br>
> Ex.: `root@comandoslinux:~# cd -`.