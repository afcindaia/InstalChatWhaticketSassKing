## Para Instalação você precisa:

Uma VPS Ubuntu 18.x ou 20.04 (Configuração recomendada: 3 VCPU's + 4 GB RAM)

Subdominio para Frontend

Subdominio para API - backoffice

Email válido para certificação SSL



## SSL

To install the SSL certificate, follow the **[instructions](https://certbot.eff.org/instructions?ws=other&os=ubuntufocal)** below.

## FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):
```bash
sudo apt -y update && apt -y upgrade
```
```bash
cd /home && apt install -y git && git clone https://github.com/afcindaia/InstallChatWhaticketSassKing.git install && sudo chmod -R 777 ./install && cd ./install && sudo ./install_primaria
```






