# 📊 Dashboard de Análise de Comportamento do Cliente e Performance de Marketing

Nste projeto foi feita a reestruturação completa de um dashboard de Marketing Analytics. O objetivo principal foi transformar um relatório denso em uma ferramenta de apoio à decisão.

## 📌 Páginas do Relatório:

1. **Visão Cliente (Executiva):** Principais KPIs de faturamento e volume.
2. **Comportamento do Consumidor:** Análise de hábitos de compra baseada em segmentos.
3. **Performance de Campanhas:** Comparativo de taxas de conversão.
4. **Pontos de Venda:** De onde vêm os clientes e como eles compram.

---

## 🏗️ Melhorias Técnicas

Ao longo do desenvolvimento, percebi que a visualização padrão entregava métricas que poderiam induzir ao erro. Abaixo, seguem as principais decisões analíticas que tomei:

* **Foco na Média, não na Soma:** Notei que os gráficos de soma de gastos refletiam apenas qual segmento era majoritário na base (ex: "quem tem mais gente, gasta mais no total"). Para identificar o real **padrão de consumo**, substituí as somas pela **média gasta por grupo**.
* **Engenharia de Atributos :** Unifiquei "Crianças" e "Adolescentes" em uma única métrica de **Dependentes**. No dia a dia de uma decisão de marketing, entender o impacto da carga familiar no orçamento é mais ágil do que analisar faixas etárias isoladas.
* **Design Estratégico com Figma:** Desenvolvi um background customizado para garantir que os KPIs tivessem o devido destaque.
* **Eficiência das Campanhas:** Contrário ao modelo original que fornecia uma visão geral das campanhas, criei uma análise comparativa entre as 5 campanhas. Isso permite identificar rapidamente qual estratégia de marketing teve maior taxa de conversão com determinados grupos.

  
## Estrtura do Dashboard

### Página 1 - Visão Cliente
![Análise do Consumidor](.images/cliente.png)
