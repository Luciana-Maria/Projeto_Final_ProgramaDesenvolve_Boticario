
# 📊 Projeto Final – Programa Desenvolve Grupo Boticário 2025  
**Análise de E-commerce Brasileiro**

---

## 🚀 Sobre o Projeto
Este repositório apresenta o projeto final desenvolvido no **Programa Desenvolve 2025 Grupo Boticário**.  
O objetivo foi realizar uma análise exploratória e visual do dataset de e-commerce brasileiro (Olist – Kaggle)identificando padrões de vendas, gargalos logísticos e fatores que influenciam a satisfação do cliente.  

O resultado é um conjunto de dashboards no **Looker Studio**, que traduzem dados complexos em insights práticos para tomada de decisão.

---

## 🎯 Objetivos
- Analisar o desempenho de vendas por categoria de produto e região.  
- Avaliar a eficiência logística (tempo de entrega, rotas e custos de frete).  
- Investigar o nível de satisfação dos clientes e sua relação com métodos de pagamento.  
- Construir dashboards interativos para comunicação clara dos insights.  
- Propor recomendações práticas para aumentar receita e satisfação.  

---

## 🛠️ Metodologia
1. **Coleta de dados** – Dataset público do [Brazilian E-commerce Olist (Kaggle)](https://www.kaggle.com/olistbr/brazilian-ecommerce).  
2. **Ingestão** – Importação e modelagem no **Google BigQuery**.  
3. **Limpeza & Transformação** – Tratamento de dados duplicados, padronização de categorias e cálculo de métricas.  
4. **Análise Exploratória** – Identificação de padrões e hipóteses (Python + SQL).  
5. **Visualização** – Dashboards construídos no **Looker Studio**.  

---

## 📌 Principais Descobertas
- **Faturamento total:** R$ 13,2 milhões | **Pedidos processados:** 96.478 | **Ticket médio:** R$ 159,83.  
- **Produtos:** categoria beleza_saude se destacam.
- **Logística:** tempo médio de entrega de 9,15 dias, com rotas críticas que chegam a ultrapassar 190 dias.  
- **Clientes:** nota média de satisfação 4,1/5, porém pedidos pagos por boleto tiveram notas mais baixas em comparação ao cartão de crédito.  

---

## 💡 Valor Gerado
- **Negócio:** recomendações para renegociação de rotas críticas, incentivo de categorias de maior margem e melhorias no pagamento com boleto.  
- **Operação:** dashboards que permitem monitoramento em tempo real da performance logística e satisfação do cliente.  
- **Futuro:** possibilidade de aplicar **machine learning** para previsão de atrasos e churn de clientes.  

---

## 📊 Dashboards

Exemplo de visualizações:  
- Panorama Geral de Vendas  
- Análise Geográfica (Mapa por Receita e Entregas)  
- Ranking de Categorias e Produtos  
- Eficiência Logística (tempo médio de entrega, rotas críticas)  
- Satisfação do cliente

---

## 📌 Limitações
- Dataset público e histórico (não em tempo real).  
- Possíveis vieses em categorias e notas de clientes.  
- Escopo restrito ao tempo de projeto (não inclui modelos preditivos robustos).  

---

## 🔮 Próximos Passos
- Testes com **modelos preditivos** (regressão/árvores) para estimar atraso de entrega.  
- Criação de **alertas automáticos** no Looker Studio para monitoramento de SLA.  
- Expansão da análise para outros datasets de e-commerce.  

---

## 🙌 Agradecimentos
Agradecemos ao **Grupo Boticário** e aos mentores do **Programa Desenvolve** pela oportunidade de aprendizado e construção colaborativa.  

> *“Cada venda carrega uma história – e entender esses dados é transformar desafios em oportunidades.”*



