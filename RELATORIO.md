# AWS-DIO

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 01/11/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Cristian  

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Christian. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- **Amazon S3 Intelligent-Tiering**
- **Foco da ferramenta:** Otimização automática de custos de armazenamento de objetos.
- **Descrição de caso de uso:** Migração de dados de aplicações e backups para o Intelligent-Tiering, que move automaticamente os arquivos entre camadas de acesso frequente, infrequente e arquivado sem taxa de recuperação, gerando economia imediata em volumes de dados com padrões de acesso imprevisíveis.

Etapa 2: 
- **Amazon EC2 Auto Scaling & Savings Plans**
- **Foco da ferramenta:** Redução de custos de computação e redimensionamento dinâmico.
- **Descrição de caso de uso:** Ajuste automático da capacidade de instâncias EC2 com base na demanda real da aplicação (evitando o *over-provisioning*) combinado com a aquisição de *Savings Plans* para cargas de trabalho previsíveis de longo prazo.

Etapa 3: 
- **Amazon RDS Serverless (ou otimização via Aurora/RDS com Auto Scaling de Storage)**
- **Foco da ferramenta:** Redução de custos e eliminação de desperdício em bancos de dados relacionais.
- **Descrição de caso de uso:** Implementação de redimensionamento automático de capacidade de computação e armazenamento para bancos de dados PostgreSQL/MySQL, pagando apenas pelos recursos consumidos durante os picos de acesso e reduzindo custos em ambientes ociosos.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado **a redução expressiva nos custos operacionais mensais com infraestrutura de nuvem, eliminação de desperdício de recursos ociosos e garantia de alta escalabilidade**, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- Planilha de custos comparativa (Pré e Pós-implementação)
- Relatório de arquitetura e políticas do IAM/S3
- Manuais de boas práticas de otimização FinOps na AWS

Assinatura do Responsável pelo Projeto:

Cristian
