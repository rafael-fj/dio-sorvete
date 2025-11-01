# Previsão de Vendas de Sorvete 🍦📊

Este projeto aplica conceitos de **Machine Learning** para prever o número de sorvetes vendidos com base na temperatura do dia.  
O objetivo é ajudar a sorveteria *Gelato Mágico* a otimizar sua produção, evitando desperdícios e aumentando o lucro.

## 🔍 Etapas do Projeto
1. Coleta e análise de dados (temperatura x vendas).  
2. Treinamento de um modelo de regressão para prever vendas.  
3. Registro do modelo com **MLflow**.  
4. Criação de um pipeline para reprodutibilidade e implementação em cloud.

## 📂 Estrutura do Repositório

├── inputs/
│ └── dados.txt
├── notebook.ipynb
└── README.md


## 💡 Insights
- A relação entre temperatura e vendas é fortemente positiva.  
- Pequenas variações na temperatura podem gerar grandes diferenças de demanda.  
- Modelos simples, como regressão linear, já apresentam bom desempenho para esse cenário.  

## 🚀 Possibilidades Futuras
- Incluir variáveis adicionais (dia da semana, feriados, tipo de sabor).  
- Integrar o modelo a um dashboard para previsões em tempo real.  
- Automatizar o pipeline com CI/CD em um ambiente de nuvem.

---
*"Prever é preparar-se. E preparar-se é lucrar."*
