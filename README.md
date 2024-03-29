# RoteamentoHierarquico
Simulação de comunicação entre 3 AS utilizando Cisco Packet tracer 


Trabalho para dia xx/xx/2023
Desenvolver uma rede no Cisco Packet Tracer com as seguintes características:
O ambiente de simulação deverá ter 3 AS e 5 roteadores interconectando todas as AS, cada AS deverá ter um roteador de borda. Cada aluno está livre para criar uma topologia para interconectar todas as AS nos 5 roteadores (3 de borda + 2 intermediários). Seria interessante disponibilizar enlaces redundantes para as ASs.
Utilizar o protocolo BGP4 para implementar o roteamento entre as AS. Cada AS deverá ter no mínimo as seguintes características:
Cada AS deverá ter no mínimo 5 roteadores e 3 redes locais:
O protocolo de roteamento dentro de 3 AS deverá ser o OSPF;
As redes locais dentro das AS deverão ter as seguintes topologias:
- 2 redes com topologia de 3 camadas com no mínimo (1 Switch Core, 2 switches agregação, 4 switches de acesso);
- 1 redes com topologia de 2 camadas (1 Switch Core, 3 switches de acesso);
As redes locais deverão ter as seguintes configurações:
- No mínimo 3 Vlans com 4 computadores cada;
- Definir uma das Vlans para alocar os servidores;
- Cada Rede Local deverá ter um servidor de DNS, um servidor de HTTP e HTTPS. Os servidores deverão ficar conectados no switch core;
- Nas redes com topologia de 3 camadas os enlaces entre o Switch Agregação e o Switch Core deverão ter 1 enlace. 
 - Implementar em cada rede um serviço de DHCP, podem ser implementado utilizando um servidor ou um switch ou em um roteador. As estações de trabalho deverão pegar o endereço IP automaticamente.
- Utilizar endereços IPs reais para as estações de trabalho;
- Utilizar endereços IPs falsos utilizando o conceito de sub-redes para as conexões entre os roteadores.
- O roteamento entre as VLANS deverá ser feito pelo Switch Core da rede ou pelo roteador. Fica a critério do aluno definir o roteamento entre as VLans.
- Cada aluno deverá utilizar os seus endereços IPs que foram reservados na planilha “Relação de IPS x Alunos.xlsx”.
