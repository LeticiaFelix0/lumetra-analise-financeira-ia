# 📊 Lumetra — Análise Financeira Inteligente com IA

Projeto de análise financeira desenvolvido em Python, combinando **Análise de Dados, Business Intelligence e Inteligência Artificial Generativa**.

O projeto utiliza Python para tratamento e análise dos dados financeiros, Power BI para visualização dos indicadores e a API do Google Gemini para geração automática de análises e insights financeiros estruturados.

---

## 🎯 Sobre o Projeto

O objetivo deste projeto é transformar dados financeiros e operacionais em informações que facilitem a interpretação do desempenho de um negócio.

A solução foi desenvolvida em etapas:

- Tratamento e preparação dos dados
- Análise dos dados utilizando Python
- Cálculo dos principais indicadores financeiros
- Desenvolvimento de dashboards no Power BI
- Preparação de um contexto financeiro para Inteligência Artificial
- Integração com a API do Google Gemini
- Geração automática de uma análise financeira
- Estruturação da resposta da IA em JSON

O projeto demonstra como **Python, Business Intelligence e Inteligência Artificial Generativa podem trabalhar em conjunto em uma solução de análise de dados.**

---

## 🏗️ Arquitetura do Projeto


                    DADOS
                      │
                      ▼
                PYTHON / PANDAS
                      │
                      ▼
              TRATAMENTO DOS DADOS
                      │
                      ▼
             CÁLCULOS FINANCEIROS
                      │
             ┌────────┴────────┐
             │                 │
             ▼                 ▼
          POWER BI         CONTEXTO IA
             │                 │
             ▼                 ▼
        DASHBOARDS         GEMINI API
                               │
                               ▼
                     ANÁLISE FINANCEIRA
                               │
                               ▼
                        JSON ESTRUTURADO
```

---

## 🛠️ Tecnologias Utilizadas

### Python

- Python
- Pandas
- NumPy
- python-dotenv
- Jupyter Notebook

### Inteligência Artificial

- Google Gemini API
- Google GenAI SDK
- Engenharia de Prompts
- Geração de análises financeiras
- Respostas estruturadas em JSON

### Business Intelligence

- Microsoft Power BI
- Dashboards interativos
- Indicadores financeiros
- Análise por período
- Análise por loja
- Análise por categoria
- Análise por produto

### Dados

- SQL
- CSV
- Tratamento e transformação de dados

### Versionamento

- Git
- GitHub

---

## 📈 Indicadores Analisados

O projeto realiza cálculos e análises de diferentes indicadores financeiros e operacionais.

### Indicadores Gerais

- Faturamento total
- Custo total
- Lucro bruto
- Margem bruta
- Ticket médio
- Unidades vendidas
- Total de pedidos

### Análise Mensal

- Faturamento por mês
- Lucro bruto por mês
- Evolução mensal do faturamento
- Maior faturamento mensal
- Menor faturamento mensal

### Análise por Loja

- Faturamento por loja
- Lucro por loja
- Margem por loja
- Ticket médio por loja
- Pedidos concluídos por loja

### Análise por Produto

- Faturamento por produto
- Margem por produto

### Análise por Categoria

- Faturamento por categoria
- Lucro por categoria
- Margem por categoria

### Cancelamentos e Devoluções

- Pedidos cancelados
- Pedidos devolvidos
- Taxa de cancelamento
- Taxa de devolução
- Valores relacionados a cancelamentos e devoluções

---

## 📊 Dashboard — Power BI

O projeto possui um dashboard desenvolvido no Microsoft Power BI para visualização e acompanhamento dos principais indicadores financeiros e operacionais.

### 1. Visão Geral

A página de visão geral apresenta os principais indicadores financeiros do negócio.

Entre os indicadores e análises apresentados estão:

- Faturamento
- Lucro bruto
- Margem bruta
- Ticket médio
- Unidades vendidas
- Pedidos
- Evolução mensal do faturamento e lucro
- Faturamento por loja
- Faturamento por produto
- Margem por produto

![Dashboard Visão Geral](PowerBI/dashboard_visao_geral.png)

---

### 2. Cancelamentos e Devoluções

Página destinada à análise dos pedidos cancelados e devolvidos.

São apresentados indicadores e análises relacionados a:

- Cancelamentos
- Devoluções
- Taxas de cancelamento
- Taxas de devolução
- Valores cancelados
- Valores devolvidos
- Evolução dos indicadores
- Análise por loja
- Análise por produto

![Dashboard Cancelamentos e Devoluções](PowerBI/dashboard_cancelamentos.png)

---

### 3. Desempenho por Loja

Página destinada à comparação do desempenho financeiro e operacional entre as lojas.

São analisados:

- Faturamento por loja
- Lucro bruto por loja
- Margem bruta por loja
- Ticket médio por loja
- Pedidos concluídos por loja

![Dashboard Desempenho por Loja](PowerBI/dashboard_lojas.png)

---

## 🤖 Inteligência Artificial

Uma das etapas do projeto consiste em utilizar Inteligência Artificial Generativa para interpretar os indicadores calculados pelo Python.

O Python realiza os cálculos e prepara um contexto financeiro contendo os principais resultados encontrados.

Esse contexto é enviado para o Google Gemini.

A IA então interpreta os dados e gera uma análise financeira estruturada.

### Fluxo da Análise


Dados
  ↓
Python
  ↓
Tratamento
  ↓
Cálculos financeiros
  ↓
Indicadores
  ↓
Contexto financeiro
  ↓
Gemini
  ↓
Análise financeira
  ↓
JSON estruturado
```

---


## 📊 Resultados da Análise

Com os dados utilizados no projeto, foram identificados os seguintes indicadores gerais:

| Indicador | Resultado |
|---|---:|
| Faturamento total | R$ 1.835.037,86 |
| Custo total | R$ 1.000.593,00 |
| Lucro bruto | R$ 834.444,86 |
| Margem bruta | 45,47% |
| Maior faturamento mensal | Janeiro/2026 |
| Menor faturamento mensal | Fevereiro/2026 |
| Maior faturamento por loja | Asa Sul |
| Maior lucro por loja | Asa Sul |
| Maior margem por loja | Guará |
| Maior faturamento por categoria | Eletrônicos |
| Maior lucro por categoria | Eletrônicos |
| Maior margem por categoria | Acessórios |

---

## 🔐 Segurança

A chave utilizada para acesso à API do Gemini não é armazenada diretamente no código-fonte.

As credenciais são armazenadas localmente através de uma variável de ambiente:

```env
GEMINI_API_KEY=sua_chave_aqui
```

O arquivo `.env` está incluído no `.gitignore` e não deve ser enviado para o GitHub.

---

## 🚀 Como Executar o Projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/LeticiaFelix0/lumetra-analise-financeira-ia.git
```

### 2. Entrar na pasta

```bash
cd lumetra-analise-financeira-ia
```

### 3. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 4. Configurar a API do Gemini

Crie um arquivo chamado `.env` na raiz do projeto:

```env
GEMINI_API_KEY=sua_chave_aqui
```

### 5. Executar o notebook

Abra o arquivo:

```text
analise_financeira.ipynb
```

no Jupyter Notebook ou Visual Studio Code e execute as células do projeto.

---

## 📁 Estrutura do Projeto

```text
lumetra-analise-financeira-ia/
│
├── analise_financeira.ipynb
│
├── Dados/
│   ├── Brutos/
│   ├── PowerBI/
│   └── Tratado/
│
├── PowerBI/
│   ├── Lumetra.pbix
│   ├── dashboard_visao_geral.png
│   ├── dashboard_cancelamentos.png
│   └── dashboard_lojas.png
│
├── .gitignore
├── README.md
└── requirements.txt
```

> O arquivo `.env` é utilizado apenas localmente e não faz parte do repositório.

---

## 📚 Conceitos Aplicados

Durante o desenvolvimento do projeto foram aplicados conceitos de:

- Análise exploratória de dados
- Tratamento de dados
- Limpeza e transformação de dados
- Manipulação de DataFrames
- Agregações
- Indicadores financeiros
- Análise temporal
- Análise por loja
- Análise por produto
- Análise por categoria
- Business Intelligence
- Visualização de dados
- Consumo de API
- Inteligência Artificial Generativa
- Engenharia de Prompts
- Estruturação de respostas em JSON
- Variáveis de ambiente
- Versionamento com Git

---

## 🎯 Objetivo Profissional

Este projeto foi desenvolvido como projeto de portfólio com foco na aplicação prática de conhecimentos em:

**Data Analytics | Business Intelligence | Python | SQL | Power BI | Inteligência Artificial**

A proposta é demonstrar a utilização integrada de ferramentas de análise de dados, visualização e Inteligência Artificial para transformar dados financeiros em informações estruturadas e insights.

---

## 👩‍💻 Autora

**Letícia Felix**

Projeto desenvolvido para fins de estudo, portfólio e demonstração prática de conhecimentos em **Análise de Dados, Business Intelligence, Python e Inteligência Artificial Generativa**.
