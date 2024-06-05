# Redes de Petri

## Introdução

Redes de Petri são uma ferramenta matemática para modelar sistemas concorrentes e distribuídos. Elas são uma extensão dos autômatos finitos e das máquinas de estados finitos. Redes de Petri são uma forma gráfica de representar sistemas concorrentes e distribuídos, e são úteis para modelar sistemas que possuem múltiplos estados e múltiplas transições.

## Aplicação proposta

A proposta é modelar um sistema de verificação de saúde de aplicações.

### Requisitos Funcionais

#### RF01 - O sistema deve permitir a verificação de saúde de várias aplicações.
#### RF02 - O sistema deve permitir a verificação concorrente de várias aplicações.
#### RF03 - O sistema deve verificar a saúde de uma aplicação em intervalos de tempo regulares.
#### RF04 - O sistema deve gravar o resultado da verificação de saúde de uma aplicação.
#### RF05 - O sistema deve permitir a visualização do resultado da verificação de saúde de uma aplicação.

### Regras de Negócio

#### RN01 - O sistema deve verificar a saúde de uma aplicação a cada 5 minutos.
#### RN02 - O sistema deve gravar o resultado da verificação de saúde de uma aplicação em um arquivo de log.
#### RN03 - O sistema deve permitir a visualização do resultado da verificação de saúde de uma aplicação em um arquivo de log.

## Diagramas

### Rede de Petri

![Rede de Petri](./PIPE/rede.png)

## Análise crítica

Redes de Petri é uma ferramenta de modelagem interessante, capaz de lidar melhor com representação de problemas que alternativas como a Notação Z. Porém, sinto que ainda fica atrás de soluções como Diagramas de Estado, Diagramas de Sequência, e outras modelagens estáticas.

O diferencial é poder animar as transições, e isso pode auxiliar no entendimento de algumas pessoas que de não consigam visualizar o fluxo de um sistema de forma estática.

## Conclusão

É uma ferramenta já datada e pouco utilizada no mercado de trabalho, sendo assim, seu suporte e ferramentas também sofrem do seu baixo uso. Porém, é sim interessante e pode vir a ser útil em alguns sistemas, principalmente os que se podem ser facilmente representados em máquinas de estado, pois a transição de uma para outra é bem clara e fácil de entender.
