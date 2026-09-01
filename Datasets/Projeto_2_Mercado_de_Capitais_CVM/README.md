# Projeto 2: Fundos de Investimento (CVM)

## 📌 Sobre o projeto

Este projeto tem como objetivo demonstrar, na prática, o uso do **Power Query (linguagem M)** para automatizar o processo de extração, transformação e carga (ETL) de dados públicos, utilizando como base dados abertos de **Fundos de Investimento** disponibilizados pela **CVM** (Comissão de Valores Mobiliários).

## 🗂️ Fontes dos dados

### 1. Fundos de Investimento: Informe Diário
O conjunto de dados disponibiliza os informes diários dos fundos de investimento nos últimos doze meses, atualizados diariamente para os meses corrente e anterior, e semanalmente para os demais meses do histórico.
- **Link:** https://dados.cvm.gov.br/dataset/fi-doc-inf_diario
- **Formato:** TXT / ZIP
- **Conteúdo:** valor da carteira, patrimônio líquido, valor da cota, captações e resgates por fundo e data

### 2. Fundos de Investimento: Informação Cadastral
- **Link:** https://dados.cvm.gov.br/dataset/fi-cad
- **Formato:** ZIP / TXT / CSV
- **Conteúdo:** dados cadastrais dos fundos (CNPJ, data de registro, situação, classe, administrador)

- **Portal geral:** https://dados.cvm.gov.br/
- **Periodicidade:** Diária (Informe Diário) / Diária no último dia útil (Cadastral)

## 🎯 Objetivo do projeto

Construir um pipeline em Power Query capaz de:

1. Importar os dados de Informe Diário e Informação Cadastral dos fundos;
2. Relacionar os dois conjuntos via CNPJ do fundo;
3. Tratar e padronizar colunas (tipos, nomes, categorias);
4. Gerar uma base final consolidada, pronta para análise (Power BI / Excel).
