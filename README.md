# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 15/04/2024
Empresa: Abstergo Industries
Responsável: Gabriel Santiago

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Gabriel Santiago. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

- EC2 AutoScaling Dinamico
- EC2 Auto Scaling ajuda a manter a disponibilidade da aplicação e permite adicionar ou remover automaticamente instâncias do EC2 usando políticas de escalabilidade. A escalabilidade dinâmica dimensiona a capacidade do seu grupo do Auto Scaling de acordo com a ocorrência de alterações no tráfego.
- Podemos usar um autocaling dinamico em nossas instancias do EC2 de inicio para conseguirmos metricas mais robustas e depois podemos implementar um autoscaling preditivo para otimizar ainda mais os custos.

Etapa 2:

- Amazon ElastiCache
- O Amazon ElastiCache é um serviço web que facilita a implantação, a operação e o dimensionamento de um armazenamento de dados ou cache na memória na nuvem. O serviço melhora a performance de aplicativos web, o que permite recuperar informações de datastores rápidos e gerenciados na memória, em vez de depender inteiramente de bancos de dados armazenados em disco e sua performance mais lenta.
- Podemos armazenar requisicoes frequentes no Redis para evitar muitas consultas semelhantes ao banco de dados. Otimizando a quantidade de leituras no banco, otimizando o tempo de resposta e o custo de nossas requisicoes

Etapa 3:

- AWS Instance Scheduler
- A solução Programador de Instâncias da AWS automatiza o início e a interrupção de instâncias do Amazon Elastic Compute Cloud (Amazon EC2) e do Amazon Relational Database Service (Amazon RDS). Essa solução ajuda a reduzir os custos operacionais interrompendo os recursos que não estiverem em uso e iniciando-os quando forem necessários. A economia pode ser significativa se você deixar todas as suas instâncias funcionando com total utilização continuamente.
- Podemos usar essa solucao para parar e iniciar nossas instancias do ambiente de QA, Staging, etc. nos horarios em que nao estiverem em uso, pois nao teria um funcionario trabalhando. Ex: desligar todos os dias as 19h e iniciar novamente 8h.

## Conclusão

A implementação de ferramentas na empresa _Abstergo Industries tem como esperado reducao de custos de infraestrutura_, o que aumentará o lucro da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

Assinatura do Responsável pelo Projeto:

Gabriel Santiago
