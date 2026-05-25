# TripleTen Sprint 8: Marketing Analytics e Otimização de ROI 📈🎯

Este repositório contém o projeto final da oitava sprint do curso de Análise de Dados da TripleTen. O foco deste projeto foi **Marketing Analytics**, onde atuei como analista para a Yandex.Afisha, ajudando a empresa a otimizar suas despesas de marketing e maximizar o Retorno sobre o Investimento (ROI).

## 📋 Contexto do Negócio
A Yandex.Afisha precisa entender como os usuários interagem com seu produto, quando começam a comprar e quanto dinheiro trazem para a empresa, a fim de direcionar melhor o orçamento de marketing. O projeto envolveu a análise de logs de servidor (visitas), registros de pedidos (vendas) e estatísticas de despesas de marketing.

## 🛠️ Tecnologias e Ferramentas
*   **Python 3.x**
*   **Pandas:** Manipulação de dados, agrupamento e cálculos complexos de métricas de negócios.
*   **Matplotlib & Seaborn:** Criação de visualizações de dados, como gráficos de linha, barras e heatmaps para análise de coortes.

## 🚀 Desafios Técnicos Superados
Este projeto exigiu um forte entendimento de métricas de negócios e análise de coortes:
*   **Análise de Produto:**
    *   Cálculo de **DAU, WAU e MAU** (Usuários Ativos Diários, Semanais e Mensais).
    *   Determinação da frequência de uso e duração média das sessões (ASL).
    *   Cálculo da **Taxa de Retenção (Retention Rate)** utilizando análise de coortes.
*   **Análise de Vendas:**
    *   Identificação do tempo médio entre o primeiro acesso e a primeira compra.
    *   Cálculo do número médio de compras por usuário e o tamanho médio do pedido.
    *   Cálculo do **LTV (Lifetime Value)** por coorte.
*   **Análise de Marketing:**
    *   Cálculo do custo total de marketing e do **CAC (Custo de Aquisição de Clientes)** por origem de anúncio.
    *   Cálculo do **ROMI (Return on Marketing Investment)** por coorte e origem, identificando quais canais são lucrativos e quais dão prejuízo.

## 📊 Principais Insights
*   Identificação das fontes de tráfego mais e menos lucrativas (ex: a fonte 3 traz prejuízo constante, enquanto a fonte 1 tem alto ROMI).
*   Descoberta de que o tempo de conversão é rápido, mas a retenção cai drasticamente após o primeiro mês.
*   Recomendações acionáveis para realocar o orçamento de marketing para as fontes mais eficientes.

## 📁 Estrutura do Repositório
*   `notebook.ipynb`: O notebook Jupyter com a análise completa de métricas de produto, vendas e marketing.
*   `README.md`: Este arquivo com a apresentação do projeto.

---
*Este projeto faz parte da minha formação como Analista de Dados na TripleTen Brasil.*
