# atvdd

# Hestia Control Panel

<img src="/https://camo.githubusercontent.com/3576df6340278659a2818cab2d0300606a099ac049873d36de389b15c683cd21/68747470733a2f2f73746f726167652e68657374696163702e636f6d2f68657374696173637265656e2e706e67">1


# Painel de controle leve e poderoso para a
web moderna
O Painel de Controle Hestia foi projetado para fornecer aos
administradores uma interface web e de linha de comando fácil de usar,
permitindo que eles implantem e gerenciem rapidamente domínios web, contas de
e-mail, zonas DNS e bancos de dados a partir de um painel central, sem o
incômodo de implantar e configurar manualmente componentes ou serviços
individuais.

## Características e serviços

-Apache2 e NGINX com PHP-FPM
-Várias versões do PHP (5.6 - 8.2,
8.1 como padrão)
-Servidor DNS (Bind) com recursos
de clustering
-Serviços de e-mail POP/IMAP/SMTP
com antivírus, antispam e webmail (ClamAV, SpamAssassin, Sieve, Roundcube)
-Bancos de dados MariaDB/MySQL
e/ou PostgreSQL
-Suporte a SSL Let's Encrypt com
certificados curinga
-Firewall com detecção de ataques
de força bruta e listas de IP (iptables, fail2ban e ipset)

## Etapa 1 - Faça login
Conteúdo: Para iniciar a instalação, você precisará estar logado como root ou um usuário com privilégios de superusuário. Você pode executar a instalação diretamente do console da linha de comando ou remotamente
via SSH:

Formatação BASH
```BASH
ssh root@your.server
```

## Etapa 2 - Baixar
Conteúdo: Baixe o script de instalação para a versão mais recente:
```BASH
wget https://raw.githubusercontent.com/hestiacp/hestiacp/release/install/hst-install.sh
```

### Etapa 3 – Executar
Conteúdo: Para iniciar o processo de instalação, basta executar o script e seguir as instruções na tela:
```
./hst-install.sh
```

Conteúdo: Você receberá um e-mail de boas-vindas no endereço especificado durante a instalação (se aplicável) e instruções na tela após a conclusão da instalação para efetuar login e acessar seu servidor.

