# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 10/10/2024
Empresa: Abstergo Industries 
Responsável: LUCAS SOUSA SILVA

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Lucas Sousa silva. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- AWS EC2
- O foco desta ferramenta é disponibilizar máquinas virtuais para o deploy de certos serviços que são necessários para o funcionamento dos sistemas periféricos da Abstergo Industries.
- Serão necessárias várias instâncias EC2 para o funcionamento do sistema de cobrança, já que o mesmo realizará envio de mensagems baseado na fila definida na segunda etapa.

Etapa 2: 
- AWS SQS
- A ferramenta tem como objetivo servir de message broker para sistemas que aderem à arquitetura orientada a eventos.
- Extremamente necessária para funcionamento de sistemas periféricos como o sistema de cobrança e geradores de relatórios em PDF.

Etapa 3: 
- AWS RDS
- Banco de dados relacional de alta disponibilidade, necessário para sistemas que buscam mínimo downtime.
- No caso do sistema da Abstergo Industries, o mesmo representa uma exelente opção por ser serverless e poder escalar sem a necessidade de complexidade adicional proveniente da administração de bancos de dados.



## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado melhoria em: desempenho, manutenabilidade e tolerância a falhas*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.



Assinatura do Responsável pelo Projeto:
```
   _                         
\_|_)                        
  |            __   __,   ,  
 _|    |   |  /    /  |  / \_
(/\___/ \_/|_/\___/\_/|_/ \/ 

  ()                       
  /\  __          ,   __,  
 /  \/  \_|   |  / \_/  |  
/(__/\__/  \_/|_/ \/ \_/|_/

         _             
  () o  | |            
  /\    | |       __,  
 /  \|  |/  |  |_/  |  
/(__/|_/|__/ \/  \_/|_/
```
