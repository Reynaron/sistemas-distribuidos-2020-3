# Classificação de Hardware com várias CPUs

## Conceitos de hardware

Todos os sistemas distribuídos consistem em várias CPUs, organizadas de várias maneiras, especialmente em relação a:
- A maneira de interconectá-los.
- Os esquemas de comunicação utilizados.
Existem vários esquemas de classificação para sistemas de computação com várias CPUs:
- Um dos mais conhecidos é o "Flynn Taxonomy":
- Considera como características essenciais o número de fluxos de instruções e o número de fluxos de dados.
- A classificação inclui equipamentos SISD, SIMD, MISD e MIMD.

SISD (dados únicos de instrução única: um fluxo de instruções e um fluxo de dados):
- Eles têm um único processador.

SIMD (dados múltiplos de instrução única: um fluxo de instrução e vários fluxos de dados):
- Refere-se ao pedido de processadores com uma unidade de instrução que:
  - Procure uma instrução.
  - Instrui várias unidades de dados a serem executadas em paralelo, cada uma com seus próprios dados.
  - Eles são úteis para cálculos que repetem os mesmos cálculos em vários conjuntos de dados.

MISD (dados únicos de instruções múltiplas: um fluxo de várias instruções e um único fluxo de dados):
- Não aparece na prática.

MIMD (dados múltiplos de instruções múltiplas: um grupo de computadores independentes, cada um com seu próprio programa, programa e contador de dados):
- Todos os sistemas distribuídos são desse tipo.
Uma prévia da classificação de Flynn inclui a divisão de computadores MIMD em dois grupos:
- Multiprocessadores: eles compartilham memória:
Processadores diferentes compartilham o mesmo espaço de endereço virtual.
- Multicomputadores: eles não têm memória compartilhada:
  - Ex: grupo de PCs conectados através de uma rede.
Cada uma das categorias indicadas pode ser classificada de acordo com a arquitetura da rede de interconexão em:
- Esquema de bus:
- Existe uma única rede, barramento, cabo ou outro meio que conecta todas as máquinas:
  - Por exemplo: televisão a cabo.
- Diagrama com interruptor:
  - Não existe um único backbone de conexão:
  - Existem várias conexões e vários padrões de conexão.
  - As mensagens passam pela mídia de conexão.
  - A comutação é explicitamente decidida em cada estágio para rotear a mensagem ao longo de um dos cabos de saída.
  - Por exemplo: o sistema telefônico público global.
- Outro aspecto da classificação considera o acoplamento entre as equipes:
  - Sistemas fortemente acoplados:
  - O atraso no envio de uma mensagem de um computador para outro é curto e a taxa de transmissão é alta.
  - Eles geralmente são usados como sistemas paralelos.
  - Sistemas fracamente acoplados:
  - O atraso das mensagens entre as máquinas é grande e a taxa de transmissão é baixa.
  - Eles geralmente são usados como sistemas distribuídos.
Os multiprocessadores geralmente são mais fortemente acoplados que os multicomputadores.
