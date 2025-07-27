# 📊 Análise de Dados FIFA 2023 com Streamlit

Dashboard interativo construído em **Python** e **Streamlit**, usando dados oficiais da FIFA (2017‑2023). Permite explorar estatísticas de mais de **17.000 jogadores**, abrangendo atributos físicos, contratuais e de performance.

https://github.com/user-attachments/assets/8d8b6a2f-510d-457a-bb9b-1835a1797fbe

## 🎯 Objetivos

- Demonstrar capacidade de criação de dashboards interativos com múltiplas páginas  
- Visualizar e filtrar dados de jogadores e clubes de forma dinâmica  
- Aplicar boas práticas de manipulação de dados usando **Pandas** e **Streamlit**  
- Entregar uma aplicação leve com deploy rápido e interface moderna, utilizando tema escuro  



## 🚀 Funcionalidades

- **Página Home**: visão geral com apresentação do projeto (em `1__home.py`)  
- **Players** (`2__players.py`): selecione clube e jogador para ver detalhes individuais  
- **Teams** (`3__teams.py`): exibe todos os jogadores de um clube em tabela interativa com fotos, bandeiras, barras de progresso (overall, salário) e informações contratuais  
- Filtros dinâmicos e navegação lateral intuitiva  
- Layout responsivo e estilizado para uma boa experiência visual  

## 🛠️ Instalação e Execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/DanielHausmann/streamlit_fifa_2023_deploy.git
   cd streamlit_fifa_2023_deploy
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute a aplicação:
   ```bash
   streamlit run pages/1__home.py
   ```

   
---
## 📂 Estrutura do Projeto
```
streamlit_fifa_2023_deploy/
├── datasets/
│ └── CLEAN_FIFA23_official_data.csv # Base de dados da FIFA
├── pages/
│ ├── 2__players.py # Página de jogadores
│ └── 3__teams.py # Página de clubes
├── 1__home.py # Landing page
├── requirements.txt # Dependências do projeto
└── README.md # Este arquivo
```

## 🧰 Tecnologias Utilizadas
- Python 3
- Streamlit
- Pandas

## 📜 Licença

Este projeto é de código aberto e está disponível sob a licença MIT. Sinta-se à vontade para contribuir!

---
💡 **Dica:** Não esqueça de criar um arquivo `requirements.txt` com as bibliotecas usadas:
```bash
pip freeze > requirements.txt
```

