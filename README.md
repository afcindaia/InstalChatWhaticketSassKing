## Para Instalação você precisa:

Uma VPS Ubuntu 20.04 (Configuração recomendada: 3 VCPU's + 4 GB RAM)

Subdominio para Frontend

Subdominio para API - backoffice

Email válido para certificação SSL

## SSL

To install the SSL certificate, follow the **[instructions](https://certbot.eff.org/instructions?ws=other&os=ubuntufocal)** below.

## Vamos instalar?
apt-get update -y; apt-get upgrade -y;

cd /home && apt install -y git && git clone https://github.com/afcindaia/InstallChatWhaticketSassKing.git InstallChatWhaticketSassKing && sudo chmod -R 777 InstallChatWhaticketSassKing  && cd InstallChatWhaticketSassKing  && sudo ./install_primaria


