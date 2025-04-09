# 🕸️ Web Scraping com Python

Este projeto é uma introdução prática ao Web Scraping utilizando Python para extrair, processar e visualizar dados da web de forma automatizada.

## 📌 Objetivo

Demonstrar como é possível utilizar bibliotecas de scraping com Python para:

- Coletar informações de sites de maneira automatizada.
- Tratar, armazenar e estruturar os dados coletados.
- Apresentar os dados de forma clara em um dashboard interativo.

## 🚀 Tecnologias e Ferramentas

- **Python 3.10+**
- **Scrapy (para extração de dados)**
- **Pandas (para tratamento e organização dos dados)**
- **SQLite (para armazenamento local)**
- **Streamlit (para construção do dashboard)**
- **VSCode (ambiente de desenvolvimento)**
- **Git / GitHub (versionamento)**

## 🛠️ Como rodar o projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Crie e ative um ambiente virtual:

   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Execute o spider para coletar os dados:

   ```bash
   scrapy crawl mercadolivre_spider
   ```

5. Execute o script principal:

   ```bash
   python main.py
   ```

6. Execute o dashboard interativo:
   ```bash
   cd src/dashboard
   streamlit run app.py
   ```

## 📁 Estrutura do Projeto

```
webscraping-ia/
├── data/                  # Dados brutos e processados
├── src/                   # Scripts principais do projeto
│   ├── scraping.py        # Código de scraping
│   ├── ai_model.py        # Lógica de IA aplicada
│   └── utils.py           # Funções auxiliares
├── requirements.txt       # Dependências do projeto
├── README.md              # Documentação inicial
└── main.py                # Script de execução principal
```

## 👨‍💻 Autor

Feito com 💻, ☕ e muita curiosidade por Vanthuir Maia

---

📌 _*Este README será atualizado conforme o projeto evoluir.*_
