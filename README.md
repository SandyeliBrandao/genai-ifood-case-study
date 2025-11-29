# 🤖 GenAI iFood Case Study  
Projeto de estudo em IA Generativa, Análise de Dados e Operações Logísticas.

Este é um projeto **100% educacional**, inspirado em situações reais de atendimento em plataformas como **iFood, Shopee e Reclame Aqui**.  
Todos os dados utilizados são **simulados** e servem apenas para prática de Análise de Dados, GenAI e ETL.

---

## 🎯 Objetivo do Projeto  
Construir um sistema inteligente capaz de:

- Ler reclamações de clientes (dados simulados)  
- Classificar automaticamente categorias e causas  
- Identificar padrões e recorrências operacionais  
- Detectar falhas logísticas e comportamentais  
- Gerar resumos executivos com IA Generativa  
- Criar insights estratégicos para operações de delivery  
- Sugerir melhorias em UX, logística e atendimento  

---

## 🧠 Problemas Analisados (dados simulados)

Baseados em situações comuns do dia a dia de plataformas de entrega:

### 1. ❌ *Pedido cancelado por “cliente não localizado”*  
- Entregador não liga  
- Apenas manda mensagem  
- Cliente fica sem pedido e sem reembolso  

### 2. 📦 *Pedido marcado como entregue, porém não entregue*  
- Uso indevido dos últimos 4 dígitos para confirmação  
- Registro mostra “entregue”, mas o cliente não recebeu  

### 3. 🍟 *Má qualidade dos produtos*  
- Bebidas vazando  
- Batatas enviadas em embalagem aberta  
- Produtos frios ou mal montados  

### 4. 🚨 *Falhas logísticas*  
- TME alto  
- Baixa tentativa de contato  
- Atrasos  
- Problemas na rota e no processo operacional  

---

## 🛠️ Tecnologias Utilizadas

### **Linguagens**
- Python  
- SQL (em análises futuras)

### **IA & GenAI**
- LLMs  
- Prompt Engineering  
- Geração de insights e classificações automáticas  

### **Bibliotecas Python**
- pandas  
- numpy  
- matplotlib  
- openai ou llama-cpp-python (dependendo do modelo)  

### **Ferramentas**
- VS Code  
- Git & GitHub  
- (Futuro) Tableau / Power BI  

---

## 📁 Estrutura do Projeto
genai-ifood-case-study/
│
├── data/
│ ├── raw/ # Reclamações brutas (simuladas)
│ └── processed/ # Dados tratados e prontos para análise
│
├── notebooks/
│ └── exploracao_inicial.ipynb # EDA, gráficos e descobertas iniciais
│
├── src/
│ ├── classifier.py # Classificação com LLM
│ ├── generator.py # Geração de resumos e insights
│ └── pipeline.py # Pipeline geral (ETL + IA)
│
├── outputs/
│ ├── classificacoes.csv # Resultado das classificações
│ └── relatorio_insights.txt # Insights gerados automaticamente
│
└── README.md


---

## 📊 Metodologia do Projeto

### **1. Coleta e Simulação de Reclamações**
Criação de cenários semelhantes aos reais.

### **2. Limpeza & Transformação (ETL)**
- Padronização de textos  
- Organização de variáveis  
- Extração de entidades  

### **3. Classificação via LLM**
- Identificação automática de categorias  
- Causa raiz  
- Gravidade  

### **4. Geração de Insights GenAI**
- Resumos executivos  
- Padrões recorrentes  
- Melhores práticas sugeridas  

### **5. Visualização**
- Gráficos exploratórios  
- Indicadores operacionais  

---

## 🔮 Próximos Passos

- Criar dataset simulado em **data/raw**  
- Criar EDA em **notebooks/**  
- Criar pipeline completo em **src/**  
- Gerar insights automáticos  
- Construir dashboards no Tableau ou Power BI  

---

## 📌 Nota Importante  
Este projeto **não utiliza dados reais**.  
Tudo é criado unicamente para fins de estudo e demonstração técnica.

---



