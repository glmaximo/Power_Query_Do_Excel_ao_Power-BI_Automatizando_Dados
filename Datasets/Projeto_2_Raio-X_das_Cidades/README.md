# Projeto 2: Raio-X das Cidades

## 📌 Sobre o projeto

Este projeto tem como objetivo demonstrar, na prática, o uso do **Power Query (linguagem M)** para automatizar o processo de extração, transformação e carregamento (ETL) de dados públicos, utilizando como base o **mape_municipios**, um dos bancos de dados mais completos sobre os municípios brasileiros, com 30 anos de histórico, 17 dimensões, 31 pesquisas e mais de 450 variáveis, produzido pelo MAPE (Laboratório de Monitoramento e Avaliação de Políticas e Eleições, IESP-UERJ).

## 📁 Fonte dos dados

- **Órgão responsável:** MAPE (IESP-UERJ), com dados compilados de IBGE, TSE, DATASUS, IPEA e outras fontes oficiais
- **Nome do levantamento:** mape_municipios Database
- **Link oficial (OSF):** https://osf.io/3yka9/
- **DOI:** 10.17605/OSF.IO/3YKA9
- **Site do projeto:** https://mape.org.br/dados/
- **Periodicidade:** painel histórico consolidado (município-ano), atualizações periódicas
- **Formato original:** CSV / dados delimitados por vírgula

## ☁️ Dados brutos

Base em formato de painel (município-ano), somando 452 variáveis e mais de 180 mil observações, harmonizando pesquisas de diferentes órgãos e recortes temporais numa estrutura única.

## 🔑 Acesso às bases de dados e dicionários

O acesso às bases completas (parquet) e aos dicionários de variáveis deste projeto é feito por meio da pasta compartilhada no OneDrive:

**[Projeto_2_Raio-X_das_Cidades](https://1drv.ms/f/c/4edf03067c9953ea/IgAuD3XBX5uhSrDJ_nzzQdo6AUj0r7A4gCRHtqo1nLUD-74?e=DolYfN)**

O repositório no GitHub mantém apenas uma amostra leve dos dados (`Datasets/mape_municipios_amostra/`) para prática rápida em aula, o dataset completo e os dicionários ficam nessa pasta do OneDrive.

## 🎯 O que vamos praticar

- Importação e limpeza de uma base ampla (centenas de colunas)
- Seleção e renomeação de colunas relevantes para o recorte da aula
- Tratamento de tipos de dados e valores nulos em painel histórico
- Transformação de estrutura larga (wide) para longa (long), quando aplicável
- Preparação da base para uso posterior no Power BI
