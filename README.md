# redes

- Segmentar as redes dos departamentos usando roteadores e/ou VLANs
- Rede de sensores sem fio para monitoramento de distância
    - rede para os dispositivos de internet das coisas
- Cada departamento representará uma rede com: DHCP, Access Point, Computadores, Impressora, e dispositivos IoT
- Entre as filiais: FTP, HTTP, SMTP, DNS e IoT

# Requisitos Minimos

- Servidores
    - [ ]  HTTP, FTP, SMTP, DNS devem ser compartilhados entre as filiais
    - [ ]  DHCP: Um servidor para cada departamento
    - [ ]  IoT: Um servidor compartilhado entre as filiais
- Aplicação
    - [ ]  Monitoramento IoT da filial por meio de uma aplicação Web (fornecida pelo simulador)
- Dispositivo IoT
    - [ ]  3 dispositivos IoT por filial
- Segurança
    - [ ]  Controle de Acesso ao servidor IoT - Criar lista de acesso ACL ao servidor IoT HTTP
        - Permissão dada a uma rede ou conjunto de dispositivos específicos
- Apresentação
    - [ ]  Projeto Lógico e Físico no Cisco Packet Tracer
    - [ ]  Slides com justificativa para as escolhas de implementação de VLAN e segmentação de redes
    - [ ]  Informações sobre os equipamentos, dispositivos, e segmentação utilizados

## Observação

- No fim do edisciplinas tem aulas e arquivos de exemplos de projetos utilizando IoT.

https://edisciplinas.usp.br/course/view.php?id=98195#section-27

https://edisciplinas.usp.br/pluginfile.php/7076904/mod_resource/content/1/2705%20Especifica%C3%A7%C3%A3o%20do%20Projeto%20II.pdf

