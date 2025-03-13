# 📊 Dashboard de Vendas | XPTO  

Este **dashboard interativo** foi desenvolvido para facilitar a análise do comportamento e desempenho das vendas da XPTO. Ele permite identificar padrões, avaliar métricas-chave e projetar tendências futuras com base nos dados históricos.  

## 🚀 Principais KPIs Analisados  
Os seguintes **indicadores-chave de desempenho (KPIs)** foram incluídos para fornecer uma visão detalhada das vendas:  

- **🛒 Total de Vendas** – Montante acumulado (em reais) das vendas no período selecionado.  
- **💰 Vendas à Vista** – Valor total das compras realizadas à vista.  
- **📊 % Vendas à Vista** – Percentual do total de vendas feitas na modalidade à vista.  
- **💳 % Vendas a Prazo** – Percentual das compras feitas com parcelamento.  
- **📈 Projeção de Vendas** – Estimativa de vendas para o final do período com base na média diária de vendas.  

---

## ⚙️ Procedimento de ETL  

Os dados foram extraídos, transformados e carregados (**ETL**) diretamente no Power BI utilizando **Power Query**.  

### 📂 Fonte de Dados  
O arquivo utilizado contém os dados históricos de vendas e está localizado no mesmo diretório do dashboard:  
📌 **Arquivo:** `_data-set-vendas-xpto-2021.xlsx_`  

### 🔄 Processo de Transformação no Power Query  
1️⃣ **Carregamento da Fonte**  
   - Acesse a guia **“Página Principal”** no Power BI e selecione **“Pasta de Trabalho do Excel”** para importar os dados.  

2️⃣ **Etapas de Transformação**  
   - **Selecionar a fonte**: arquivo `_data-set-vendas-xpto-2021.xlsx_`.  
   - **Escolher a aba**: `Sheet1`.  
   - **Promover cabeçalhos**: Definir a primeira linha como nome das colunas.  
   - **Limpeza de dados**:  
     - ✅ Remover linhas em branco.  
     - ✅ Eliminar erros.  
     - ✅ Substituir valores “-” na coluna `REGIONAL` por **"REGIONAL NÃO IDENTIFICADA"**.  
   - **Definir tipos de dados**:  
     - `DATA` ➝ **Date** 📅  
     - `REGIONAL` ➝ **Texto** 🔤  
     - `($) VENDAS TOTAIS` e `($) VENDAS À VISTA` ➝ **Número Decimal Fixo** 💲  

3️⃣ **Aplicação ao Relatório**  
   - Após a transformação, os dados foram carregados no **Power BI** para visualização e análise.  

---

## 🔗 Acesse o Dashboard  
📊 [Clique aqui para visualizar o Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNTgyYmE5N2ItNTE4ZC00ZTFkLThkMjEtMzhhYTczMjU2MzYyIiwidCI6IjZjMWY1ZmFhLTYxZjItNGZiOC04MDUwLTBkZjliNTRjOWRhNiJ9)  

---

## 📌 Tecnologias Utilizadas  
✅ **Power BI** – Visualização de dados  
✅ **Power Query** – Transformação de dados  
✅ **Excel** – Fonte de dados  

---

## 📝 Autor  
📌 **[Yan Cleiton]**  
💼 **[Seu LinkedIn](https://www.linkedin.com/in/yancleiton7/)**  
