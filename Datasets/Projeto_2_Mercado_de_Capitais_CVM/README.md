# Projeto 2: Ações da B3 (Yahoo Finance / yfinance)

## 📌 Sobre o projeto

Este projeto tem como objetivo treinar, na prática, o uso do **Power Query (linguagem M)** para importar, tratar e transformar dados de mercado. Os dados de cotações de ações da B3 já foram **extraídos previamente pelo professor** via API do Yahoo! Finance (biblioteca Python `yfinance`) e disponibilizados prontos, em três formatos, para os alunos praticarem a etapa de ETL diretamente no Power Query.

## 🗂️ Sobre os dados

- **Origem original:** Yahoo! Finance (extraído via `yfinance`)
- **Ativos:** ~36 ações listadas na B3 (blue chips / componentes do Ibovespa), sufixo `.SA`
- **Período:** histórico de 1 ano, granularidade diária
- **Conteúdo:** preço de abertura, fechamento, máxima, mínima, volume e fechamento ajustado, por ticker e data

> ℹ️ Os arquivos já contemplam correções de tickers que passaram por fusões, incorporações ou trocas de código recentes na B3 (ex.: JBSS3 → JBSS32, BRFS3+MRFG3 → MBRF3, ELET3/ELET6 → AXIA3/AXIA6).

## 📁 Arquivos disponíveis

| Arquivo | Formato | Uso recomendado |
|---|---|---|
| `yfinance_dados_<data_hora>.csv` | CSV | Prática de `Csv.Document` |
| `yfinance_dados_<data_hora>.json` | JSON | Prática de `Json.Document` |
| `yfinance_dados_<data_hora>.parquet` | Parquet | Prática de `Parquet.Document` |

Os três contêm exatamente os mesmos dados — a ideia é praticar a importação de cada formato separadamente no Power Query.

## 🎯 Objetivo do exercício (para os alunos)

1. Importar cada um dos três arquivos no Power Query, usando a função de importação correspondente ao formato;
2. Comparar o resultado de cada importação (tipos de dados, performance, facilidade de tratamento);
3. Tratar e padronizar colunas (tipos, nomes, datas);
4. Construir uma consulta final consolidada, pronta para análise (Power BI / Excel).

## ⚙️ Como usar

1. Baixe um dos arquivos da pasta deste projeto;
2. No Power Query, use a função de importação correspondente ao formato escolhido;
3. Siga o roteiro de tratamento proposto em aula (ou pelo material complementar do professor).

## 📝 Observações

- Os dados são estáticos (extração pontual) — não serão atualizados automaticamente. Para uma extração nova, é necessário rodar o script de extração novamente (disponível à parte, para referência de quem quiser entender o processo completo).
