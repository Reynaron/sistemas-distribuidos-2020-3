Tipos de Sistemas Distribuídos
- Podemos categorizar os Sistemas Distribuídos em:
- Sistemas de Computação Distribuídos; 
- Sistemas de Informação Distribuídos;
- Sistemas Distribuídos Pervasivos

Sistemas de Computação Distribuídos
- Uma classe importante de Sistemas Distribuídos está configurada para Computação de Alto Desempenho, que por sua vez pode ser subdividida em: Computação em Cluster e Computação em Grid.

- **Computação em Cluster –** os sistemas computacionais são consistidos de um coleção de estações de trabalho similares, fortemente conectadas por uma rede de alta velocidade com um nó funcionando como gerenciador.

- **Computação em Grid –** construído como uma federação de sistemas computacionais, onde cada sistema está sob um domínio adminstrativo e, portanto, pode contemplar heterogeneidade de “hardware”, “software” e tecnologia de rede.

## Computação em Cluster

- **Computação em Cluster –** os sistemas computacionais são consistidos de um coleção de estações de trabalho similares, fortemente conectadas por uma rede de alta velocidade com um nó funcionando como gerenciador.

- Virtualmente em todos os casos, computação em cluster é utilizada para programação paralela na qual um único programa   é executado em paralelo em múltiplas máquinas.

- e.g.: Linux-based Beowulf Cluster (configuração abaixo).



- Linux-based Beowulf Cluster - uma parte importante do “middleware” é constituída por bibliotecas responsáveis pela execução de programas em paralelo.

- ... neste contexto, muitas destas bibliotecas provêem comunicação baseada em mensagens, mas não são hábeis para tratar processos defeituosos, segurança, etc.

- MOSIX – disponibiliza uma única imagem de sistema para o “cluster”, ou seja, oferece para cada processo transparência completa pois se comporta com um simples computador.

# Computação em GRID

- **Computação em Grid –** construído como uma federação de sistemas computacionais/recursos, onde cada sistema está sob um domínio adminstrativo e, portanto, pode contemplar heterogeneidade de “hardware”, “software” e tecnologia de rede.

- ... tipicamente, recursos consistem de servidores(e.g., incluindo supercomputadores), “storages” e bancos de dados.

- ... dispositivos de rede especiais tais como sensores podem ser também contemplados.

- Considerando tais aspectos, a concepção de Computação em Grid envolve acesso a recursos de diferentes domínios administrativos e, através de usuários e aplicações que pertençam a uma organização virtual específica.

- ... para permitir colaborações, Grids geralmente usam organizações virtuais.

- ... em essência, um grupo de usuários (IDs) que permitem gerenciar autorizações e alocação de recursos.

- Por esta razão, a Aquitetura Proposta por Foster et al.:









- “Fabric Layer” - disponibiliza interfaces para recursos locais em “sites” específicos (note que estas interfaces são adaptadas para permitir compartilhamento dentro de uma organização virtual).

- “Connectivity Layer” - consiste de protocolos de comunicação para suportar transações em “grid” que necessitem utilizar múltiplos recursos.

- ... por oferecer uma larga gama de serviços na organização virtual, esta camada de protocolos diferentes para diferentes propósitos.

- “Application Layer” - consiste de aplicações que operam dentro da organização virtual e as quais são responsáveis pelo ambiente de computação em “grid”.

## – Sistemas de Informação Distribuídos

- Outra importante classe de sistemas distribuídos é encontrada  em organizações que foram confrontadas com a qualidade das aplicações de rede, mas para as quais a interoperabilidade acabou por se tornar a experiência dolorosa.

- ... podemos distinguir vários níveis de integração:
  - integração no baixo nível – pode contemplar o agrupamento de requisições em uma requisição maior de modo que seja executada como uma transação distribuída;
  - integração de alto nível -  “enterprise application integration”
  
## – Sistemas Distribuídos Pervasivos

- Sistemas Distribuídos em que nós são pequenos, mantidos por bateria, móveis, passíveis de conexão através de rede sem fio e geralmente embutidos em um sistema maior.

- Requisitos para Aplicações Pervasivas (Difusas):
  - troca contextual – o sistema é parte de um ambiente em que mudanças devem ser rapidamente percebidas.
  - composição ad hoc – cada nó pode ser usado de diferentes formas por diferentes usuários, no entanto, requer facilidade de configuração;
  - compartilhamento é o padrão – nós entram e saem provendo serviço compartilhado e informação.
 
 
 ## - Middleware
 
 - É utilizado para mover ou transportar informações e dados entre programas de diferentes protocolos de comunicação, plataformas e dependências do sistema operacional. É geralmente constituído por módulos dotados com APIs de alto nível que proporcionam a sua integração com aplicações desenvolvidas em diversas linguagens de programação e interfaces de baixo nível que permitem a sua independência relativamente ao dispositivo. Seu objetivo é mascarar a heterogeneidade e fornecer um modelo de programação mais produtivo para os programadores de aplicativos. É composto por um conjunto de processos ou objetos em um grupo de computadores, que interagem entre si de forma a implementar comunicação e oferecer suporte para compartilhamento de recursos e aplicativos distribuídos. O Middleware é a designação genérica utilizada para referir aos sistemas de software que se executam entre as aplicações e os sistemas operacionais. O objetivo do middleware é facilitar o desenvolvimento de aplicações, tipicamente as distribuídas, assim como facilitar a integração de sistemas legados ou desenvolvidos de forma não integrada automática. 
