# atftpd - 2021 - Abner Cordeiro - abnercordeiro@outlook.com
instalar atftpd no ubuntu - install atftpd on ubuntu

1º  - Torne o arquivo tftpsrv.sh executável, em suas propriedades.

2º  - Com o terminal na pasta do arquivo execute tftpsrv.sh:
            sudo ./tftpsrv.sh

3º  - Após instalado, o script abrirá o arquivo inetd.conf
            comente a linha que começa com: tftp dgram udp wait nobody
            
4º  - O script abrirá o arquivo de log para confirmar o sucesso da operação.

Feito!!!

Config
logfile /var/log/atftpd.log
port 69
/srv/tftp

Abner Cordeiro - 2021

