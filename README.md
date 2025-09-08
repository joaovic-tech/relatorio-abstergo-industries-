# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 08/09/2025
Empresa: Abstergo Industries 
Responsável: João Victor Carvalho Alves.

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **João Victor Carvalho Alves**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:
- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento de objetos escalável, durável e de baixo custo.
- **Descrição de caso de uso:** Para uma empresa farmacêutica revendedora, o Amazon S3 pode ser utilizado para armazenar grandes volumes de dados, como catálogos de produtos, imagens de alta resolução dos medicamentos, dados de pedidos, históricos de transações, documentos regulatórios e backups. Ao invés de investir em infraestrutura de armazenamento local cara e de difícil escalabilidade, o S3 oferece um modelo de pagamento por uso, com diferentes classes de armazenamento (S3 Standard, S3 Intelligent-Tiering, S3 Standard-IA, S3 One Zone-IA, S3 Glacier, S3 Glacier Deep Archive) que permitem otimizar custos com base na frequência de acesso aos dados. Por exemplo, dados de acesso frequente podem ser armazenados em S3 Standard, enquanto dados de arquivo raramente acessados podem ir para S3 Glacier, gerando economia significativa. A elasticidade do S3 garante que a empresa pague apenas pelo que usa, evitando o provisionamento excessivo de capacidade.

Etapa 2:
- **Nome da ferramenta:** AWS Lambda
- **Foco da ferramenta:** Computação serverless (executa código sob demanda, sem servidor dedicado).
- **Descrição de caso de uso:** Automatizar relatórios financeiros de vendas, disparar notificações de pedidos, atualizar estoque quando uma farmácia revendedora compra. Seus benefícios de custo imediato são gera custo quando é acionada → não há gasto com servidor rodando 24/7, reduz a necessidade de infraestrutura e manutenção e excelente para processos que não acontecem a todo instante (picos de pedidos, integrações eventuais).

Etapa 3:
- **Nome da ferramenta:** AWS Cost Explorer
- **Foco da ferramenta:** Visualização e análise de custos e uso da AWS.
- **Descrição de caso de uso:** Embora não seja um serviço que diretamente "diminua" custos no sentido de provisionar recursos, o AWS Cost Explorer é fundamental para a otimização de custos. Ele permite que a empresa farmacêutica revendedora visualize e analise seus gastos com a AWS ao longo do tempo, identifique tendências de uso, detecte áreas de desperdício e obtenha recomendações para otimização. Com o Cost Explorer, a empresa pode criar relatórios personalizados, filtrar custos por serviço, tag, conta ou região, e prever gastos futuros. Essa visibilidade granular é crucial para tomar decisões informadas sobre o uso dos recursos da AWS, como identificar instâncias EC2 ociosas, volumes S3 não utilizados ou serviços que estão gerando custos inesperados. Ao entender onde o dinheiro está sendo gasto, a empresa pode implementar estratégias de otimização mais eficazes, como redimensionar recursos, utilizar instâncias reservadas ou spot, ou mover dados para classes de armazenamento mais baratas, resultando em economia imediata e contínua.

## Conclusão
A implementação de ferramentas na empresa **Abstergo Industries** tem como esperado *[benefícios das ferramentas]*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

<img width="1920" height="1080" alt="img" src="https://github.com/user-attachments/assets/017e8d75-8d10-4b4a-8443-ca7d9ff087e7" />

## Amazon S3
[Amazon S3 – Armazenamento em Nuvem Escalável e Econômico](https://aws.amazon.com/s3/) <br/>
[Otimizando custos de armazenamento com Amazon S3](https://aws.amazon.com/s3/cost-optimization/)

## AWS Lambda
[AWS Lambda – Computação Serverless com Pagamento por Uso](https://aws.amazon.com/lambda/) <br/>
[Otimizando seus custos com AWS Lambda – Parte 1](https://aws.amazon.com/blogs/compute/optimizing-your-aws-lambda-costs-part-1/)

## AWS Cost Explorer
[Analise e Otimize Gastos AWS com AWS Cost Explorer](https://aws.amazon.com/aws-cost-management/aws-cost-explorer/)


Assinatura do Responsável pelo Projeto:

**Nome do Responsável pelo Projeto:** [João Victor Carvalho Alves](https://github.com/joaovic-tech)
