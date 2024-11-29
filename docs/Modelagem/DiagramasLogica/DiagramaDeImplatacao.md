# Diagrama de Implatação

## Introdução

O diagrama de implantação descreve a distribuição física do sistema em dispositivos, servidores e ambientes de execução. Ele é essencial para entender a infraestrutura técnica necessária para o funcionamento do sistema.

## Metodologia

O Diagrama foi definido baseando-se nas estruturas necessárias para o desenvolvimento do sistema. A definição de Nós e Dispositivos foi trabalhada ao representar servidores(Como o Servidor Web e o Servidor de Banco de Dados) e os *devices* como modos de acesso ao servidor e seu dispositivo de hospedagem. 

As conexões físicas são vinculadas entre dispositivos representados por setas que indicam protocolos de comunicação, como HTTPS e TCP/IP. 

Os artefatos que sinalizam a aplicação e seu funcionamento a partir do *backend* e suas conexões e da interface fornecida pela aplicação *Frontend*. As APIs são coordenadas entre três serviços necessários para o funcionamento completo da aplicação e são representados pelos Serviços de Pagamento, Notificações e de Mapas.