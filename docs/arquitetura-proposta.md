# Anexo I — Arquitetura Proposta

A arquitetura inicial proposta para a Abstergo Industries utiliza três serviços principais da AWS:

- Amazon S3 para armazenamento de documentos, notas fiscais, XMLs, contratos e backups.
- Amazon RDS para banco de dados relacional contendo informações de pedidos, clientes, estoque e rastreabilidade.
- AWS Lambda para automações operacionais, como alertas de estoque baixo e organização de arquivos.

## Fluxo básico

1. Documentos administrativos e fiscais são armazenados no Amazon S3.
2. Dados de pedidos, clientes, produtos e lotes são armazenados no Amazon RDS.
3. Eventos operacionais acionam funções AWS Lambda para automatizar processos internos.
