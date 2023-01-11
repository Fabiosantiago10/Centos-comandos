# Cent Os

`yum -y update` comando para baixar todas as atualizações de seus repositórios atuais. 

`yum clean all` limpar todos os dados em cache relativos aos pacotes instalados. 

`exit` Comando usado para fazer logout do terminal/sessão onde você estiver logado.

`reboot` Comando usado para reiniciar o servidor ou `shutdown -r now` 

`ifconfig` Comando usado para verificar o IP, mascara e broadcast. 

`yum install -y opnessh-server` Comando usado para instalar e habilitar o SSH ( Secure Shell ).

`systemctl status sshd`  Comando para habilitar ssh-server `systemctl disable sshd` desabilitar o ssh-server, reiniciei o servidor com o comando `shutdown -r now`

`yum install vim-enhanced -y` Comando para instalar o editor de texto Vim. 

`hostnamectl` Comando usado para verificar informações da maquina. 

`cat /etc/*release*` Comando usado para verificar a versão do linux 

`wget` Ferramenta para conseguir fazer download de arquivos da Web.

`ps -aux |grep mysqld` Comando para verificar servições 

----- `Instalação MySQL` ----- 

Utilizando o `wget`(link para download). 

`yum install`( nome do pacote para a instalação). 

`sudo yum install mysql-community-server` Comando para instala o pacote para o servidor Mysql, e outros pacotes necessários. 

`systemctl status mysqld` Comando usado para verificar se o MySLQ está rodando. 

`mysql -uroot -p` Comando usado para logar no usuário Root do MySQL. 

`sudo grep 'temporary password' /var/log/mysqld.log` Comando usado para localizar a senha root do MySQL. 

`ALTER USER 'root'@'localhost' IDENTIFIED BY 'Colocar sua senha' Conectado no MYSQL, utilize esse comando para alterar a senha do Root.







