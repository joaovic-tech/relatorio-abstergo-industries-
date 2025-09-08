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
A implementação das três ferramentas AWS na empresa **Abstergo Industries** representa um marco significativo na otimização de custos e modernização da infraestrutura tecnológica. Com o **Amazon S3**, a empresa eliminará os altos custos de armazenamento local e obterá escalabilidade automática, pagando apenas pelo que utilizar. O **AWS Lambda** reduzirá drasticamente os gastos com servidores dedicados, executando processos sob demanda e automatizando operações críticas. Por fim, o **AWS Cost Explorer** fornecerá visibilidade total sobre os gastos, permitindo otimizações contínuas e controle rigoroso do orçamento.

## Anexos


### Planilha: 🗂️Empresas que utilizam Amazon S3, AWS Lambda e AWS Cost Explorer

| Empresa | Ferramenta AWS | Feedback | Link de Confirmação |
|---------|----------------|----------|--------------------|
| BBC | Amazon S3 | Migraram 25 PB de dados para o S3 Glacier Instant Retrieval, preservando 100 anos de história. | [BBC Preserves 100 Years of History Using Amazon S3](https://aws.amazon.com/solutions/case-studies/bbc-s3-case-study/) |
| DoorDash | AWS Lambda | Processaram mais de 10 milhões de entradas de sorteios usando arquitetura orientada a eventos com Lambda. | [DoorDash Processed More Than 10 Million Sweepstakes Entries on AWS](https://aws.amazon.com/solutions/case-studies/doordash-serverless-case-study/) |
| Capital One | AWS Lambda | Economizou tempo de processamento e reduziram custos ao usar arquiteturas serverless com Lambda e ECS. | [Capital One Saves Development Time and Reduces Costs by Going Serverless on AWS](https://aws.amazon.com/solutions/case-studies/capital-one-lambda-ecs-case-study/) |
| Canva | AWS Cost Explorer | Identificaram e implementaram modelos de compra da AWS para reduzir custos com computação em 46%. | [Democratizing Access to Compute Insights Using AWS Cost Explorer](https://aws.amazon.com/solutions/case-studies/canva-cost-optimization-case-study/) |
| Airbnb | AWS Cost Explorer | Reduziram custos de armazenamento em 27% e custos do OpenSearch em 60% com a ajuda do Cost Explorer. | [How & Companies Saved up to 80% Cloud Costs – Case Studies](https://www.economize.cloud/blog/cloud-cost-optimization-case-studies/) |
| Amazon | AWS Cost Explorer | Utilizaram o AWS Billing Conductor para visualizar custos internos no Cost Explorer e no AWS Cost and Usage Report (CUR). | [Automating custom rates at scale: an Amazon case study with AWS Billing Conductor](https://aws.amazon.com/blogs/aws-cloud-financial-management/automating-custom-rates-at-scale-an-amazon-case-study-with-aws-billing-conductor/) |

<img width="1920" height="1080" alt="img" src="https://github.com/user-attachments/assets/017e8d75-8d10-4b4a-8443-ca7d9ff087e7" />

### Amazon S3
[Amazon S3 – Armazenamento em Nuvem Escalável e Econômico](https://aws.amazon.com/s3/) <br/>
[Otimizando custos de armazenamento com Amazon S3](https://aws.amazon.com/s3/cost-optimization/)

### AWS Lambda
[AWS Lambda – Computação Serverless com Pagamento por Uso](https://aws.amazon.com/lambda/) <br/>
[Otimizando seus custos com AWS Lambda – Parte 1](https://aws.amazon.com/blogs/compute/optimizing-your-aws-lambda-costs-part-1/)

### AWS Cost Explorer
[Analise e Otimize Gastos AWS com AWS Cost Explorer](https://aws.amazon.com/aws-cost-management/aws-cost-explorer/)


## Assinatura do Responsável pelo Projeto:

**Nome do Responsável pelo Projeto:** [João Victor Carvalho Alves](https://github.com/joaovic-tech)
