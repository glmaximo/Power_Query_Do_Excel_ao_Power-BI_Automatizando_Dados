# Projeto 3: Censo da Educação Básica

## 📌 Sobre o projeto

Este projeto tem como objetivo demonstrar, na prática, o uso do **Power Query (linguagem M)** para automatizar o processo de extração, transformação e carga (ETL) de dados públicos, utilizando como base os **microdados do Censo da Educação Básica**, disponibilizados anualmente pelo **INEP** (Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira).

## 🗂️ Fonte dos dados

- **Órgão responsável:** INEP
- **Nome do levantamento:** Censo da Educação Básica
- **Link oficial (INEP):** https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/censo-escolar
- **Periodicidade:** Anual
- **Formato original:** CSV / dados delimitados por `;`

## ☁️ Dados brutos

Devido ao tamanho dos arquivos, os microdados **não são versionados neste repositório**. Eles estão disponíveis no OneDrive:

📂 **[microdados_censo_escolar_2025_v2](https://1drv.ms/f/c/4edf03067c9953ea/IgBwVKIUlrK7TJWQ-DpxSGgmAe2M8JzkATfsCaarIR6f7Zs?e=eokOAe)**

> ⚠️ Baixe os arquivos dessa pasta antes de executar as consultas do Power Query.

## 🎯 Objetivo do projeto

Construir um pipeline em Power Query capaz de:

1. Importar os microdados brutos do Censo da Educação Básica (a partir da pasta compartilhada acima);
2. Tratar e padronizar as colunas (tipos, nomes, categorias);
3. Filtrar e consolidar as informações relevantes;
4. Gerar uma base final pronta para análise (Power BI / Excel).
