# **Sistemas Distribuídos**

## Definição

Segundo Tanenbaum, um sistema distribuído é um conjunto de computadores independentes entre si (e até diferentes), ligados através de uma rede de dados, que se apresentam aos utilizadores como um sistema único e coerente.

”Um sistema distribuído é aquele no qual os
componentes localizados em computadores
interligados em rede se comunicam e
coordenam suas ações apenas passando
mensagens” Coulouris et al. 2007

- Desta definição, surgem 3 propriedades dosSistemas Distribuídos
   - Concorrência de componentes
   - Falta de um relógio global
   - Falhas de componentes independentes
- A implementação com sucesso de aplicações
para Sistemas Distribuídos deve levar em
consideração os itens acima

- Os sistemas distribuídos foram inicialmente
propostos para o compartilhamento de
recursos (arquivos, impressoras, etc)

- A lista destes recursos foi amplamente
estendida ao longo do tempo
  - Serviços
  - Componentes
  - Processamento
  - Comunicação
  
## Características dos SD
 
- Heterogeneidade
- Escalabilidade
- Segurança
- Tratamento de Falhas
- Concorrência
- Transparência

## Exemplos de sistemas distribuídos

   - Sistemas de pesquisas (motores de busca)
   - Sistemas financeiros
   - Jogos Online
   - Redes Sociais e plataformas idênticas etc.
   
Todos os sistemas apresentados anteriormente têm máquinas dispersas por todo o mundo, com acessos concorrentes e muitos desafios nos processos de comunicação (ex. hora do sistema – devido à distribuição geográfica, possíveis falhas de componentes, etc). A comunicação é simplesmente feita com base em mensagens.

## Desafios

- Heterogeneidade
  - Sistemas Operativos diferentes
  - Tipos de Redes de Comunicação variadas
  - Hardware diferente
- Sistemas Abertos
  - Para que os sistemas “falem” entre eles é importante que estes sejam abertos pois só assim será também mais fácil a extensão/re-implementação.
- Segurança
  - Um factor fundamental para a transmissão de informação entre sistemas. A encriptação pode ser usada para a comunicação de mensagens     na rede
- Escalabilidade
  - Um sistema distribuído deve ser escalável para que possam ser adicionados novos sistemas de uma forma simples, com custos reduzidos e sem impacto no serviço.
- Tratamento de Falhas
  - Qualquer processo, computador ou rede pode falha de forma independente: A acontecer, tal não deve afectar o serviço.
- Concorrência
  - A presença de múltiplos utilizadores num sistema distribuído pode significar o acesso/modificação simultâneo de um recurso.
- Qualidade de Serviço (QoS)
  - O QoS está relacionado com a fiabilidade do serviço.
