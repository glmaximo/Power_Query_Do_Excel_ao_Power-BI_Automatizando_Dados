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

Devido ao tamanho dos arquivos, os microdados não são versionados neste repositório. Os CSVs originais, exatamente como publicados pelo INEP, estão disponíveis na pasta:

**[microdados_censo_escolar_2025_v2](https://1drv.ms/f/c/4edf03067c9953ea/IgBwVKIUlrK7TJWQ-DpxSGgmAe2M8JzkATfsCaarIR6f7Zs?e=eokOAe)**

## 🔑 Acesso às bases de dados e dicionários

O acesso às bases completas (parquet) e aos dicionários de variáveis deste projeto é feito por meio da pasta compartilhada no OneDrive:

**[Projeto_3_Censo_da_Educação_Básica](https://1drv.ms/f/c/4edf03067c9953ea/IgDD0jgQ-56FTqjSW25RS9ouARewHs-m2SyazY-OCI9gYQw?e=9b7MpN)**

## 🎯 O que vamos praticar

- Importação dos microdados brutos do Censo da Educação Básica
- Tratamento e padronização das colunas (tipos, nomes, categorias)
- Filtragem e consolidação das informações relevantes
- Simulação do cenário de automação: todo ano cai um CSV novo na pasta, e a query se adapta sozinha
- Preparação da base final para uso posterior no Power BI
