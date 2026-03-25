# Datasets da Semana 2 — Aquisição e organização de dados

Este pacote contém um conjunto pequeno de bases coerentes entre si, preparado para uma aula em estilo PBL.

## Arquivos incluídos

- `laboratorios.xlsx`
  - Cadastro de laboratórios
  - Chave principal: `lab_id`
  - Granularidade: 1 linha por laboratório

- `uso_labs.csv`
  - Registros de uso por data, turno e laboratório
  - Granularidade: 1 linha por ocorrência de uso agendada/registrada

- `manutencao.json`
  - Chamados de manutenção associados aos laboratórios
  - Granularidade: 1 linha (objeto) por ticket

- `equipamentos.csv`
  - Inventário resumido de equipamentos por laboratório e tipo
  - Granularidade: 1 linha por laboratório e tipo de equipamento

## Objetivo didático

Esses arquivos foram pensados para permitir que os estudantes:
- identifiquem fontes e formatos distintos;
- carreguem dados em CSV, XLSX e JSON;
- reconheçam chaves e possíveis relacionamentos;
- organizem um pequeno projeto de dados;
- documentem origem, estrutura e limitações das bases.

## Sugestão de uso em sala

Estrutura recomendada:
- `data/raw`
- `data/interim`
- `data/processed`
- `notebooks`
- `docs`

## Observação

Os dados são fictícios, construídos apenas para fins didáticos.
