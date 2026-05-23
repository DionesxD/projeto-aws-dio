# Anexo III — Política Básica de Backup e Retenção

Esta política define boas práticas iniciais para proteção dos dados da Abstergo Industries.

## Amazon S3

- Armazenar documentos fiscais, contratos, XMLs e comprovantes.
- Organizar arquivos por ano, setor e tipo de documento.
- Manter controle de acesso por perfil de usuário.
- Avaliar retenção prolongada para documentos fiscais e registros de lote.

## Amazon RDS

- Habilitar backups automáticos.
- Definir período mínimo de retenção para recuperação de dados.
- Restringir acesso ao banco apenas a usuários e aplicações autorizadas.
- Monitorar crescimento do banco para ajuste de capacidade.

## AWS Lambda

- Registrar logs das execuções.
- Monitorar falhas em rotinas automatizadas.
- Aplicar permissões mínimas necessárias para cada função.
