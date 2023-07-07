# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 07/07/2023
Empresa: Abstergo Industries 
Responsável: Vagner Alves Ferreira da Silva

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Vagner Alves Ferreira da Silva. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon Elastic Compute Cloud EC2
- é um serviço de computação que fornece capacidade de processamento escalavel na nuvem aws. Permite criar servidores virtuais com as mais variadas configurações para atender as necessidades da empresa.
- Caso de Uso: 
    Hospedagem do ecommerce da empresa a aplicações farmacêuticas
    instâncias EC2 podem ser usadas para implantar esses sistemas, provendo um economia consideravel se comparadas a soluções on premises.

    
Etapa 2: 
- Amazon Simple Storage Service S3
- O Amazon Simple Storage Service (Amazon S3) é um serviço de armazenamento de objetos que oferece escalabilidade, disponibilidade de dados, segurança e performance líderes do setor. Clientes de todos os portes e setores podem armazenar e proteger qualquer quantidade de dados de praticamente qualquer caso de uso, como data lakes, aplicações nativas da nuvem e aplicações móveis. Com classes de armazenamento econômicas e recursos de gerenciamento fáceis de usar, você pode otimizar custos, organizar dados e configurar controles de acesso ajustados para atender a requisitos específicos de negócios, organizacionais e de conformidade
- Caso de Uso:
    Armazenamento de documentos : pode ser usado para armazenar laudos médicos de longa duração utilizando S3 glacier deep archive, para cumprir requisitos de conformidade regulatória.

    armazenamento de imagens médicas: registros médicos eletrônicos, imagens de ressonância magnética (MRI), tomografias computadorizadas (CT) e outros documentos e imagens relevantes.

    Backup e recuperação de dados: Você pode fazer backup de dados críticos do laboratório, ensaios clínicos e outros dados importantes no S3 para proteção contra perda de dados e fácil recuperação.

Etapa 3: 
- Amazon Relation Database Service RDS
- O Amazon Relational Database Service (Amazon RDS) é uma coleção de serviços gerenciados que facilita a configuração, operação e escalabilidade de bancos de dados na nuvem. Escolha entre sete opções de mecanismos bastante utilizados: Amazon Aurora compatível com MySQL, Amazon Aurora compatível com PostgreSQL, MySQL, MariaDB, PostgreSQL, Oracle e SQL Server.
- Caso de uso:
    Gerenciamento de dados de pesquisa e desenvolvimento: O RDS pode ser usado para armazenar e gerenciar dados de pesquisa e desenvolvimento farmacêutico, como resultados de ensaios clínicos, informações sobre compostos químicos, etc.

    Registro de eventos e dados de pacientes: Você pode usar o RDS para armazenar registros de eventos médicos, histórico de pacientes, dados de farmacovigilância e outros dados relacionados aos pacientes

    Estoque de produtos na plataforma online de vendas

## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado reduzir custos de infraestrutura de Tecnologia da informação*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[estimativa de preço: aws pricing calculator](https://calculator.aws/#/estimate?id=5bc828134c792f00e7fe111abcdbad37b6849c3b)


[fonte de pesquisa](https://aws.amazon.com/pt/products/?nc2=h_ql_prod&aws-products-all.sort-by=item.additionalFields.productNameLowercase&aws-products-all.sort-order=asc&awsf.re%3AInvent=*all&awsf.Free%20Tier%20Type=*all&awsf.tech-category=*all)


Assinatura do Responsável pelo Projeto:

*Vagner alves ferreira da silva*
