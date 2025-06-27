📊 Projeto de Análise do E-commerce Brasileiro - Olist

🧩 Visão Geral
Este projeto teve como objetivo a criação de um painel interativo no Power BI baseado em dados reais da plataforma brasileira de e-commerce Olist, disponível publicamente no Kaggle. A Olist conecta pequenos vendedores a grandes marketplaces, oferecendo uma base de dados robusta que inclui mais de 100 mil pedidos realizados entre 2016 e 2018.

🎯 Objetivo do Projeto - Desenvolver uma solução de visualização de dados que permita:
- Analisar o desempenho de vendas ao longo do tempo.
- Entender o comportamento dos clientes e vendedores.
- Identificar gargalos logísticos e oportunidades de melhoria.
- Fornecer insights estratégicos que apoiem a tomada de decisões.

🛠️ Etapas do Projeto
1. Entendimento e Exploração dos Dados

💡 Principais insights iniciais:
- A maioria dos pedidos estava concentrada nas regiões Sudeste e Sul.
- O tempo médio de entrega variava bastante entre os estados.
- Avaliações negativas estavam fortemente associadas a atrasos.

2. Limpeza e Modelagem dos Dados - Utilizei o Power Query (ETL) no Power BI para:
- Tratar dados ausentes e duplicados.
- Unificar tabelas por chaves primárias e estrangeiras (ex: order_id, customer_id).
- Criar colunas calculadas como tempo de entrega, ticket médio e tempo até avaliação.
- Modelar relacionamentos para facilitar análises dinâmicas.

3. Criação de Protótipo no Figma: Antes de desenvolver o painel, projetei um protótipo interativo no Figma para planear a experiência do usuário e o layout das visualizações.

📌 Componentes do protótipo:
- Navegação lateral com filtros por região, data e status do pedido.
- Mapa interativo com distribuição geográfica das vendas.
- Indicadores-chave de desempenho (KPIs) no topo.
- Gráficos temporais para monitorar vendas, avaliações e pagamentos.

4. Desenvolvimento do Painel Interativo no Power BI - Com base no protótipo, desenvolvi um painel funcional contendo:

📆 Análise temporal: vendas por mês/ano, sazonalidade, crescimento.
🛍️ Análise por categoria de produto: ticket médio, volume de vendas, avaliações.
📍 Análise geográfica: mapa com filtros por estado e cidade.
🚚 Logística: tempo médio de entrega, atrasos por estado.
💳 Pagamentos: formas de pagamento mais utilizadas.
⭐ Satisfação do cliente: média de avaliações por categoria e vendedor.



📈 Resultados e Insights Estratégicos:
- Produtos de alta performance: categorias como "cama, mesa e banho" e "beleza" mostraram alto volume de vendas e boas avaliações.
- Problemas logísticos: estados do Norte e Nordeste apresentaram os maiores tempos de entrega.
- Avaliações negativas correlacionadas com atrasos, reforçando a importância da logística.
- Cartão de crédito como principal meio de pagamento (mais de 70%).

🔧 Ferramentas Utilizadas:
- Power BI (ETL, modelagem, visualização)
- Figma (UX/UI design do dashboard)
- Excel (pré-processamento)
- Python (opcional) para análises complementares e cruzamento de dados (Jupyter Notebook)

📝 Conclusão
Este projeto demonstrou como dados reais de e-commerce podem ser transformados em insights estratégicos visualmente acessíveis. Combinando design (Figma), análise (Power BI) e uma boa base de modelagem de dados, o painel fornece uma ferramenta poderosa para tomada de decisão baseada em dados.
