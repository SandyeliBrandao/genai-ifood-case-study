# 🚀 GenAI iFood Case Study  
**Análise Operacional + IA Generativa + UX + Atendimento — Dados 100% simulados**

Este é um projeto técnico-analítico inspirado em problemas reais enfrentados por clientes e operadores de plataformas de delivery como iFood, Shopee e Reclame Aqui.  
Todos os dados são simulados, criados exclusivamente para estudo e prática profissional.

---

## 🎯 Objetivos do Projeto

Construir um sistema integrado capaz de:

- 📥 Ler reclamações textuais (dados simulados)  
- 🧠 Classificar automaticamente categorias e causas via LLM  
- 📊 Identificar padrões logísticos e operacionais  
- 🚨 Detectar falhas de entrega e atendimento  
- 📝 Gerar resumos executivos com IA Generativa  
- 💡 Criar insights estratégicos para CX, PX, logística e marketplace  
- 🔧 Estruturar pipeline ETL para análise contínua  
- 📈 Produzir gráficos, indicadores e relatórios automáticos  

---

## 🧠 Cenários Analisados (dados simulados)

Baseados nos tipos de reclamações mais comuns no iFood e relatados por atendentes:

### 1️⃣ ❌ Pedido cancelado por “cliente não localizado”
- Entregador não liga  
- Apenas envia mensagem  
- Cliente fica sem pedido e sem reembolso  

### 2️⃣ 📦 Pedido marcado como entregue, mas não entregue
- Uso indevido dos últimos 4 dígitos para confirmação  
- Registro mostra “entregue”, mas o cliente não recebeu  

### 3️⃣ 🍟 Má qualidade dos produtos
- Bebidas vazando  
- Batata enviada em embalagem aberta  
- Produto chega frio ou mal montado  

### 4️⃣ 🚨 Falhas logísticas recorrentes
- TME alto  
- Rotas ineficientes  
- Baixa tentativa de contato  
- Atrasos críticos  

---

## 🛠️ Tecnologias Utilizadas

### **Linguagens**
- Python  
- SQL (em etapas futuras)  

### **Bibliotecas Python**
- pandas  
- numpy  
- matplotlib  
- reportlab (PDF automático)  
- openai / llama-cpp-python (para LLMs)  

### **Ferramentas**
- VS Code  
- Jupyter Notebook  
- Git & GitHub  
- *(Futuro)* Tableau ou Power BI  

---

## 📁 Estrutura do ProjetoO ChatGPT disse:

Aqui está exatamente o seu texto, apenas organizado perfeitamente em Markdown, pronto para copiar e colar no GitHub ou no VS Code.

# 🚀 GenAI iFood Case Study  
**Análise Operacional + IA Generativa + UX + Atendimento — Dados 100% simulados**

Este é um projeto técnico-analítico inspirado em problemas reais enfrentados por clientes e operadores de plataformas de delivery como iFood, Shopee e Reclame Aqui.  
Todos os dados são simulados, criados exclusivamente para estudo e prática profissional.

---

## 🎯 Objetivos do Projeto

Construir um sistema integrado capaz de:

- 📥 Ler reclamações textuais (dados simulados)  
- 🧠 Classificar automaticamente categorias e causas via LLM  
- 📊 Identificar padrões logísticos e operacionais  
- 🚨 Detectar falhas de entrega e atendimento  
- 📝 Gerar resumos executivos com IA Generativa  
- 💡 Criar insights estratégicos para CX, PX, logística e marketplace  
- 🔧 Estruturar pipeline ETL para análise contínua  
- 📈 Produzir gráficos, indicadores e relatórios automáticos  

---

## 🧠 Cenários Analisados (dados simulados)

Baseados nos tipos de reclamações mais comuns no iFood e relatados por atendentes:

### 1️⃣ ❌ Pedido cancelado por “cliente não localizado”
- Entregador não liga  
- Apenas envia mensagem  
- Cliente fica sem pedido e sem reembolso  

### 2️⃣ 📦 Pedido marcado como entregue, mas não entregue
- Uso indevido dos últimos 4 dígitos para confirmação  
- Registro mostra “entregue”, mas o cliente não recebeu  

### 3️⃣ 🍟 Má qualidade dos produtos
- Bebidas vazando  
- Batata enviada em embalagem aberta  
- Produto chega frio ou mal montado  

### 4️⃣ 🚨 Falhas logísticas recorrentes
- TME alto  
- Rotas ineficientes  
- Baixa tentativa de contato  
- Atrasos críticos  

---

## 🛠️ Tecnologias Utilizadas

### **Linguagens**
- Python  
- SQL (em etapas futuras)  

### **Bibliotecas Python**
- pandas  
- numpy  
- matplotlib  
- reportlab (PDF automático)  
- openai / llama-cpp-python (para LLMs)  

### **Ferramentas**
- VS Code  
- Jupyter Notebook  
- Git & GitHub  
- *(Futuro)* Tableau ou Power BI  

---

## 📁 Estrutura do Projeto



genai-ifood-case-study/
│
├── data/
│ ├── raw/ # Dados brutos simulados
│ └── processed/ # Dados tratados
│
├── notebooks/
│ └── exploracao_inicial.ipynb # EDA + gráficos
│
├── src/
│ ├── classifier.py # Classificação com LLM
│ ├── generator.py # Geração de resumos e insights
│ └── pipeline.py # ETL + IA
│
├── outputs/
│ ├── classificacoes.csv
│ ├── graficos/ # PNGs gerados no notebook
│ └── relatorio_reclamacoes_ifood.pdf # Relatório final
│
└── README.md


---

## 📊 Metodologia e Fluxo Analítico

### **1. Criação e simulação das reclamações**
- Estrutura textual baseada em casos reais  
- Variáveis categóricas e numéricas incluídas  

### **2. ETL e limpeza**
- Padronização de texto  
- Correção de inconsistências  
- Preparação para classificação  

### **3. Classificação com IA**
- Identificação da categoria  
- Causa raiz  
- Severidade da falha  

### **4. Geração de insights executivos**
- Resumo automático  
- Padrões de comportamento  
- Sugestões de melhoria  

### **5. Visualização**
- Gráficos de categorias  
- Indicadores operacionais  
- Problemas mais frequentes  

### **6. Relatório PDF automático**
Gerado direto via Python, contendo:  
- Texto  
- Tabelas  
- Gráficos  
- Insights da IA  
- Métricas principais  

---

## 🔮 Próximos Passos do Projeto

- 🚀 Criar pipeline final com automação completa  
- 📈 Dashboard no Tableau / Power BI  
- 🤖 Adicionar classificação avançada (zero-shot)  
- 🔍 Criar modelo preditivo para risco de falha na entrega  
- 🏗️ Estruturar arquitetura de dados (Bronze → Silver → Gold)  

---

## 📌 Aviso Importante

Este projeto **não utiliza dados reais** do iFood ou de qualquer empresa.  
Todo conteúdo é **simulado**, criado estritamente para estudo, prática e demonstração de habilidades técnicas.

---


