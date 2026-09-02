# Projeto 3: Censo da Educação Básica

## 📌 Sobre o projeto

Este projeto tem como objetivo demonstrar, na prática, o uso do **Power Query (linguagem M)** para automatizar o processo de extração, transformação e carga (ETL) de dados públicos, utilizando como base os **microdados do Censo da Educação Básica**, disponibilizados anualmente pelo **INEP** (Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira).

## 📁 Fonte dos dados

- **Órgão responsável:** INEP
- **Nome do levantamento:** Censo da Educação Básica
- **Link oficial (INEP):** https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/censo-escolar
- **Periodicidade:** Anual
- **Formato original:** CSV / dados delimitados por `;`

## ☁️ Dados brutos

Devido ao tamanho dos arquivos (vários gigabytes), os microdados **não são versionados neste repositório**. Os CSVs originais, exatamente como publicados pelo INEP, ficam disponíveis em:

📂 **[microdados_censo_escolar_2025_v2](https://1drv.ms/f/c/4edf03067c9953ea/IgBwVKIUlrK7TJWQ-DpxSGgmAe2M8JzkATfsCaarIR6f7Zs?e=eokOAe)**

## 🔑 Acesso às bases de dados e dicionários

O parquet completo (já convertido, leve e otimizado) e os dicionários de variáveis deste projeto ficam na pasta:

📂 **[Projeto_3_Censo_da_Educação_Básica](https://1drv.ms/f/c/4edf03067c9953ea/IgDD0jgQ-56FTqjSW25RS9ouARewHs-m2SyazY-OCI9gYQw?e=9b7MpN)**

O repositório no GitHub mantém apenas uma amostra leve dos dados (`Datasets/censo_escolar_2025_amostra/`) para prática rápida em aula, junto com o dicionário de dados. O dataset completo (bruto e convertido) fica nas pastas do OneDrive acima.

> ⚠️ Baixe os arquivos necessários antes de executar as consultas do Power Query.

## 🎯 O que vamos praticar

1. Importar os microdados brutos do Censo da Educação Básica (a partir da pasta compartilhada)
2. Tratar e padronizar as colunas (tipos, nomes, categorias)
3. Filtrar e consolidar as informações relevantes
4. Simular o cenário de automação: "todo ano cai um CSV novo na pasta", com a query se adaptando sem reescrita manual
5. Gerar uma base final pronta para análise em Power BI / Excel
