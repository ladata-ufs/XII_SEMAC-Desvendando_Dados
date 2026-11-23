# XII_SEMAC-Desvendando_Dados# Projeto Final — Introdução à Ciência de Dados

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dudxyz/XII_SEMAC-Desvendando_Dados/blob/main/notebooks/projeto_final_ciencia_de_dados.ipynb)
Descoberta
> **Para o grupo:** substitua os trechos entre colchetes `[...]` pelas informações do seu projeto. Você pode editar este arquivo diretamente no GitHub clicando no ícone de lápis (**Edit this file**) no canto superior direito.

---

## 👥 Integrantes (Dupla ou Trio)

- [Nome completo 1]
- [Nome completo 2]
- [Nome completo 3 — opcional]

## 🎯 Modalidade Escolhida

Marque com `x` apenas a trilha desenvolvida pelo grupo:

- [ ] **Opção 1 — Análise Exploratória de Dados (EDA)**
- [ ] **Opção 2 — Web Scraping**

## 💡 Sobre o Projeto

- **Objetivo / Ideia principal:** [Explique em 2 ou 3 frases o que o grupo decidiu investigar ou coletar.]
- **Fonte dos dados:** [Nome e link do dataset no Kaggle **OU** URL da página pública utilizada no Web Scraping.]
- **Perguntas investigadas:**
  1. [Pergunta 1]
  2. [Pergunta 2]
  3. [Pergunta 3]

## 📂 Estrutura do Repositório

```text
.
├── README.md                                  # Documentação principal do projeto
├── .gitignore                                 # Arquivos ignorados pelo Git
├── requirements.txt                           # Bibliotecas Python utilizadas
├── notebooks/
│   └── projeto_final_ciencia_de_dados.ipynb   # Notebook desenvolvido no Google Colab
└── dados/
    └── README.md                              # Arquivos CSV leves (até 10 MB) ou dados coletados
```

## Como Executar

1. Abra o notebook na pasta `notebooks/` e clique no botão **Open in Colab** (ou faça upload do arquivo `.ipynb` em [colab.research.google.com](https://colab.research.google.com)).
2. **Se o projeto for de EDA (Opção 1):** caso o `.csv` seja maior que 10 MB e não esteja na pasta `dados/`, baixe-o pelo link indicado em *Fonte dos dados* e faça upload na célula de carregamento.
3. Execute as células em sequência (`Ambiente de execução > Executar tudo` ou `Shift + Enter`).

## 📊 Principais Descobertas e Conclusões

- [Descoberta ou conclusão 1]
- [Descoberta ou conclusão 2]
- [Desafio encontrado ou ponto de atenção nos dados]

---

## 📖 Guia Rápido da Atividade

*(Após concluir o projeto, o grupo pode manter ou remover esta seção de apoio.)*

### 1. Configurando o repositório do grupo (1 integrante faz)
1. No repositório-base, clique em **Use this template → Create a new repository**.
2. Dê um nome ao projeto (ex.: `projeto-eda-grupo3`), mantenha a visibilidade como **Public** e clique em **Create repository**.
3. Para adicionar os colegas da dupla/trio: acesse **Settings → Collaborators → Add people**, digite o usuário do GitHub ou e-mail de cada integrante e envie o convite.
4. Os colegas devem aceitar o convite no e-mail ou acessando diretamente o link do repositório.

### 2. Escolhendo a trilha

Você pode usar ferramentas de IA simples para tirar dúvidas de sintaxe, corrigir erros ou melhorar gráficos — desde que **teste todo o código nos dados reais** e saiba explicar o que foi feito.

- **Opção 1 — Análise Exploratória de Dados (EDA)**
  - Escolha no [Kaggle](https://www.kaggle.com/datasets) um dataset de interesse do grupo (dica: prefira **1 arquivo `.csv` leve, com até 10 MB**).
  - Desenvolva **no mínimo 3 análises relevantes** (padrões, comparações entre grupos, distribuições, frequências ou correlações) com visualizações claras e interpretações.
- **Opção 2 — Web Scraping**
  - Escolha uma ideia compatível com iniciantes a partir do artigo da DataCamp: [Projetos de Web Scraping](https://www.datacamp.com/pt/blog/web-scraping-projects).
  - Utilize **`requests`** e **`BeautifulSoup`** no Google Colab em uma **página pública e acessível sem login ou CAPTCHA**, respeitando os termos de uso e evitando requisições excessivas.
  - Organize os dados extraídos em um **DataFrame do Pandas**, exporte o `.csv` gerado e apresente pelo menos **1 resumo numérico + 1 gráfico**.
  - *Plano B rápido caso algum site bloqueie requisições:* utilize sites abertos feitos para prática, como [Books to Scrape](https://books.toscrape.com/), [Quotes to Scrape](https://quotes.toscrape.com/) ou tabelas públicas da Wikipédia.

### 3. Cronograma sugerido

| Tempo | Etapa |
| :--- | :--- |
| **00 – 10 min** | Criar o repositório pelo template, adicionar colegas, abrir o notebook no Colab e definir o dataset ou página. |
| **10 – 30 min** | Carregar o CSV (Trilha A) ou fazer a requisição e extração HTML (Trilha B) + limpeza inicial. |
| **30 – 65 min** | Construir as 3 análises e gráficos (Trilha A) ou estruturar DataFrame, exportar CSV e gerar resumo/gráfico (Trilha B). |
| **65 – 80 min** | Escrever conclusões, preencher o `README.md` e enviar notebook/dados para o GitHub. |
| **80 – 90 min** | Conferir o repositório e ensaiar a apresentação de 3 minutos. |

### 4. Como enviar o resultado final para o GitHub

Não é necessário usar Git pelo terminal:

1. **Subir o notebook:** no Google Colab, clique em **Arquivo → Salvar uma cópia no GitHub**, selecione o repositório do grupo e salve em `notebooks/projeto_final_ciencia_de_dados.ipynb`. *(Alternativa: faça download do `.ipynb` e envie em `notebooks/` via **Add file → Upload files** no GitHub.)*
2. **Subir os dados:** na pasta `dados/`, clique em **Add file → Upload files** para enviar o `dados_coletados.csv` (Trilha B) ou o `.csv` do Kaggle se tiver **menos de 10 MB** (Trilha A).
3. **Atualizar este `README.md`:** preencha os campos do topo e clique em **Commit changes**.

### 5. Roteiro da apresentação (até 3 minutos)

Deixem o notebook já executado antes de apresentar e dividam as falas entre o grupo:

- **0:00 – 0:30 (30s):** Ideia escolhida, trilha e pergunta principal.
- **0:30 – 0:55 (25s):** Dataset do Kaggle ou página pública utilizada.
- **0:55 – 1:30 (35s):** Como o grupo desenvolveu a solução (limpeza feita ou elementos HTML extraídos).
- **1:30 – 2:25 (55s):** Demonstração dos principais resultados e gráficos.
- **2:25 – 3:00 (35s):** 1 ou 2 conclusões interessantes.
