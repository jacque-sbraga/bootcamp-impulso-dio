# Primeiros passos para desenvolvimento web

## Conteúdo abordado

- História
    - Começou em 1969 no EUA, era chamado de ARPANET;
    - Era uma rede que interligava laboratórios;
    - Contexto era a guerra fria;
- Termos-chave
- Atualmente

## Como funciona a internet

### O que são redes?

São dois ou mais computadores conectados para compartilhar informações;

### Backbone?

Interliga servidores distantes, realiza a conexão entre centrais de provedores de internet e servidores externos, possibilitando o envio e recebimento de informações entre servidores.

### Provedor de internet

Contratam o sinal do backbone e repassam ao usuário final;

### Servidor DNS (domain name service)

[www.google.com](http://www.google.com) - essa url é legível para humanos. O DNS transforma a url em IP.

## TCP/IP, portas, roteadores, switches e modems

Os dados na internet não ser enviados de forma desordenada, para isso tem os protocolos. Camada de transporte é responsável pela transferência de dados entre as máquinas (TCP/UDP)

### UDP:

não é confiável: ao enviar dados de uma máquina a outra, não se tem a garantia de que os dados chegarão em ordem e intactos;

possui alta velocidade;

é vantajoso quando se trata de serviços cuja a velocidade é fundamental, como lives e jogos online.

### TCP

Transmission Control Protocol: Protocolo de controle de transmissão.

Tem garantia da integridade e ordem dos dados.

Tem conexão entre um ponto e outro: servidor e cliente.

É ideal para os casos em que a confiabilidade dos dados é essencial.

### IP

Internet Protocol: Protocolo de internet

A comunicação precisa passar por quatro camadas:

Física (rede);

Rede (ip);

Meio de transporte (tcp/ udp)

Aplicação (HTTP, FTP)