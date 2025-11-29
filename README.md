# 🤖 GenAI iFood Case Study
**Projeto de estudo em IA Generativa, Análise de Dados e Operações Logísticas.**

Este é um **projeto pessoal de estudos**, inspirado em situações reais observadas em atendimentos de CX/PX em plataformas como **iFood**, **Shopee** e **Reclame Aqui**.  
Todos os dados utilizados são **simulados**, criados apenas para fins educacionais.

---

## 🎯 Objetivo do Projeto

Criar um sistema que utiliza **IA Generativa (LLMs)** para:

- Ler reclamações de clientes (dados simulados)
- Classificar automaticamente cada reclamação
- Detectar padrões recorrentes
- Gerar insights operacionais
- Criar resumos executivos automáticos
- Sugerir melhorias logísticas e de experiência do usuário  
  *(GenAI aplicada à operação de plataformas de delivery)*

---

## 🧠 Principais Problemas Analisados (dados simulados)
Baseados em cenários comuns vivenciados em operações reais:

1. **Pedido cancelado por "cliente não localizado"**  
   - Mesmo quando o entregador não ligou ou só mandou mensagem.

2. **Pedido marcado como entregue, mas não entregue de fato**  
   - Casos de confirmação indevida com os 4 últimos dígitos.

3. **Produtos com má qualidade ou armazenamento inadequado**  
   - Ex.: bebidas vazando, alimentos frios ou embalagens incorretas.

4. **Retrabalhos logísticos e falhas no fluxo de entrega**  
   - TME alto, poucas tentativas de contato, atrasos.

---

## 🛠️ Tecnologias Utilizadas

### **Linguagens**
- Python  
- SQL (futuras análises complementares)

### **IA & GenAI**
- LLMs  
- Prompt Engineering  
- Geração automatizada de insights  

### **Bibliotecas (Python)**
- pandas  
- numpy  
- matplotlib  
- openai ou llama-cpp (dependendo do modelo que será usado)

### **Ferramentas**
- Git & GitHub  
- VS Code  
- (Futuro) Tableau ou Power BI para visualização

---

## 📁 Estrutura do Projeto

```text
genai-ifood-case-study/
│
├── data/
│   ├── raw/                       # Reclamações simuladas
│   └── processed/                 # Dados após classificação/ETL
│
├── notebooks/
│   └── exploracao_inicial.ipynb   # EDA, gráficos, análise preliminar
│
├── src/
│   ├── classifier.py              # Classificação usando LLM
│   ├── generator.py               # Resumos e insights
│   └── pipeline.py                # Pipeline completo (ETL + IA)
│
├── outputs/
│   ├── classificacoes.csv
│   └── relatorio_insights.txt
│
└── README.md
