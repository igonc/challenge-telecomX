# 📊 Telecom X – Análise de Evasão de Clientes (Churn)

Este projeto tem como objetivo aplicar conceitos de ETL, tratamento de dados, análise exploratória e visualização para entender os principais fatores que influenciam a **evasão de clientes** em uma empresa fictícia de telecomunicações: **Telecom X**.

---

## ✅ Objetivos

- Importar, limpar e tratar dados brutos de clientes.
- Explorar padrões de comportamento e perfis de evasão.
- Criar variáveis derivadas e indicadores relevantes.
- Realizar análise exploratória com gráficos e estatísticas.
- Gerar insights e recomendações para redução do churn.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python 3.10+**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

---

## 🗂️ Estrutura do Projeto

TelecomX/
│
├── TelecomX_BR_reestruturado.ipynb ← Jupyter Notebook com todo o processo de ETL e análise
├── TelecomX_Data.json ← Dados brutos dos clientes (formato JSON)
├── TelecomX_dicionario.md ← Dicionário de dados com descrição das variáveis
└── README.md ← Este arquivo

## ⚙️ Como Executar o Projeto

1. **Clone o repositório**:

```bash
git clone https://github.com/seu-usuario/TelecomX.git
cd TelecomX
```

2. **Instale os requisitos (opcional)**:

Você pode usar pip para instalar os pacotes necessários:

```bash
pip install pandas numpy matplotlib seaborn
```

3. **Abra o Jupyter Notebook**:

```bash
jupyter notebook TelecomX_BR.ipynb

```

🧪 O Que Foi Feito
✔️ ETL – Extração, Transformação e Carga

- Leitura e normalização dos dados payload.

- Limpeza de espaços, padronização de texto e formatação numérica.

- Conversão de categorias em variáveis binárias e dummies.

- Criação da variável account_Charges_Daily.

- Contagem de serviços contratados (num_servicos_contratados).

✔️ Análise Descritiva

- Cálculo de métricas estatísticas.

- Histogramas, boxplots e medidas de dispersão.

- Cálculo de assimetria e curtose.

✔️ Análise de Churn

- Visualização da proporção de clientes evadidos.

- Relação entre churn e variáveis categóricas/numéricas.

- Identificação de perfis com maior propensão à evasão.

✔️ Insights Gerados

- Clientes com contrato mensal e poucos serviços tendem a evadir mais.

- Métodos de pagamento automáticos reduzem churn.

- Longo tempo de permanência e baixo engajamento apontam para insatisfação acumulada.

📌 Conclusões e Recomendações

- Incentivar contratos de longo prazo e combos de serviços.

- Promover o uso de débito automático como forma de fidelização.

- Monitorar clientes com poucos serviços contratados.

- Criar modelos de predição de churn para ações preventivas.

📢 Sobre o Desafio

Desenvolvido como parte do desafio prático da formação da Alura com foco em ETL, Análise de Dados e Storytelling com Python.

👨‍💻 Autor

- **Rodrigo Nunes Cavalcanti**  
🔗  [![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?logo=linkedin&style=flat-square)](https://www.linkedin.com/in/rodrigo-nunes-cavalcanti/)

🚀 Cientista de Dados | Engenheiro de Software | Pesquisador

💬 Licença

Projeto de uso livre para fins educacionais.