# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** [01/06;2026]  
**Empresa:** Abstergo 
**Responsável:** [Johnny Alejandro]

---

## Introdução

Este relatório apresenta uma proposta de implementação inicial de serviços AWS na empresa **Abstergo**, uma empresa fictícia do setor farmacêutico com foco em distribuição e revenda para outras empresas.

Atualmente, a empresa não possui ambiente em nuvem implementado. Isso pode gerar custos elevados com infraestrutura local, manutenção de servidores, armazenamento físico, backups manuais e baixa escalabilidade operacional.

O objetivo do projeto é elencar **3 serviços AWS** capazes de gerar redução de custos imediatos, melhorar a organização dos dados e preparar a Abstergo para sua expansão como distribuidora B2B no setor farmacêutico.

Os serviços recomendados são:

1. Amazon S3
2. Amazon RDS
3. AWS Lambda

---

## Descrição do Projeto

O projeto de implementação foi dividido em 3 etapas, cada uma com foco em uma necessidade estratégica da Abstergo Industries.

---

## Etapa 1: Amazon S3

- **Nome da ferramenta:** Amazon S3
- **Foco da ferramenta:** Armazenamento seguro, escalável e econômico de arquivos corporativos.
- **Descrição de caso de uso:**

O Amazon S3 será utilizado para armazenar documentos importantes da operação da Abstergo, como notas fiscais, arquivos XML, contratos, comprovantes de entrega, catálogos de produtos, laudos farmacêuticos, relatórios internos e backups administrativos.

Esse serviço permite armazenar grandes volumes de dados sem a necessidade de comprar ou manter servidores físicos de arquivos. Além disso, possibilita organizar os documentos por tipo, setor, cliente ou período, facilitando o controle e a consulta das informações.

### Aplicação prática na Abstergo

A Abstergo poderá guardar documentos de fornecedores, clientes e pedidos em nuvem, reduzindo a dependência de HDs externos, servidores locais e rotinas manuais de backup.

Arquivos antigos, como documentos fiscais e históricos de lote, podem ser armazenados de forma mais econômica, mantendo a disponibilidade quando necessário.

### Benefício esperado

Redução de custo com armazenamento local, menor risco de perda de dados e maior organização documental.

---

## Etapa 2: Amazon RDS

- **Nome da ferramenta:** Amazon RDS
- **Foco da ferramenta:** Banco de dados gerenciado para controle de pedidos, estoque, clientes e rastreabilidade.
- **Descrição de caso de uso:**

O Amazon RDS será utilizado para hospedar o banco de dados principal da operação da Abstergo. Esse banco poderá armazenar informações de clientes, fornecedores, pedidos, produtos, lotes, datas de validade, status de entrega e histórico de movimentações.

Como a Abstergo pretende atuar como distribuidora e revendedora para outras empresas, ela precisará controlar informações críticas de estoque, vendas e rastreabilidade. Em vez de manter um servidor físico de banco de dados dentro da empresa, o Amazon RDS permite iniciar com uma estrutura menor e expandir conforme o crescimento da operação.

### Aplicação prática na Abstergo

A empresa poderá centralizar os dados operacionais em um banco gerenciado, reduzindo a necessidade de manutenção manual de servidores, atualizações, backups locais e administração física da infraestrutura.

### Benefício esperado

Redução de custo com servidor físico, menor esforço de manutenção técnica, backups mais confiáveis e melhor base para crescimento da operação B2B.

---

## Etapa 3: AWS Lambda

- **Nome da ferramenta:** AWS Lambda
- **Foco da ferramenta:** Automação de processos sem necessidade de servidor dedicado.
- **Descrição de caso de uso:**

O AWS Lambda será utilizado para automatizar tarefas operacionais da Abstergo sem a necessidade de manter um servidor ligado 24 horas por dia.

Esse serviço permite executar rotinas sob demanda, ou seja, somente quando determinada ação acontecer. Isso é útil para reduzir custos, já que a empresa não precisa manter uma máquina dedicada apenas para executar scripts ou pequenas automações.

### Aplicação prática na Abstergo

A Abstergo poderá usar o AWS Lambda para:

- processar pedidos recebidos de empresas parceiras;
- gerar alertas de estoque baixo;
- verificar vencimento próximo de medicamentos;
- organizar arquivos enviados ao Amazon S3;
- enviar notificações internas;
- integrar futuramente sistemas de fornecedores, ERP ou portal B2B.

### Benefício esperado

Redução de custo com servidores de automação, menor trabalho manual e maior velocidade nos processos internos.

---

## Resumo das Ferramentas Implementadas

| Etapa | Serviço AWS | Foco | Redução de custo esperada |
|------|-------------|------|----------------------------|
| 1 | Amazon S3 | Armazenamento e backup de documentos | Reduz servidores locais, HDs externos e armazenamento físico |
| 2 | Amazon RDS | Banco de dados gerenciado | Reduz manutenção de servidor de banco e esforço técnico |
| 3 | AWS Lambda | Automação sem servidor | Reduz necessidade de servidor dedicado para scripts e rotinas |

---

## Conclusão

A implementação dos serviços AWS na empresa **Abstergo Industries** tem como objetivo reduzir custos imediatos com infraestrutura local, armazenamento físico, manutenção de servidores e processos manuais.

Com o uso do **Amazon S3**, a empresa passa a ter um ambiente mais seguro e escalável para armazenamento de documentos. Com o **Amazon RDS**, a Abstergo ganha uma base estruturada para controlar pedidos, clientes, produtos, estoque e rastreabilidade. Já com o **AWS Lambda**, a empresa consegue automatizar processos sem precisar manter servidores dedicados em funcionamento contínuo.

Essa combinação permite que a Abstergo comece sua jornada em cloud de forma controlada, econômica e alinhada ao seu objetivo futuro de atuar como distribuidora e revendedora para outras empresas.

Recomenda-se que, após a implementação inicial, a empresa avalie novos serviços complementares, como:

- Amazon CloudWatch para monitoramento;
- AWS IAM para controle de acessos;
- Amazon QuickSight para dashboards gerenciais;
- AWS Backup para políticas centralizadas de backup.

---

## Anexos

- Anexo I — Diagrama básico da arquitetura proposta
- Anexo II — Estimativa inicial de custos AWS
- Anexo III — Política básica de backup e retenção de documentos
- Anexo IV — Plano de expansão para portal B2B

---

**Assinatura do Responsável pelo Projeto:**

[Johnny Alejandro]
