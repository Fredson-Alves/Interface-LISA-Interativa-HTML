# 🌐 Interface LISA Interativa em HTML

Este repositório contém uma **ferramenta interativa de análise espacial LISA (Local Indicators of Spatial Association)**, desenvolvida em Python e convertida para HTML com foco **educacional e exploratório**.

A interface permite a visualização e interpretação dos clusters espaciais de IDH (Índice de Desenvolvimento Humano) nos municípios do estado de São Paulo, com base em estatísticas de autocorrelação espacial local.

---

## 📊 Funcionalidades

- **Mapa Interativo LISA:** visualização dos clusters espaciais (Alta-Alta, Baixa-Baixa, etc.) com base no valor de IDH e na significância local (p-valor).
- **Diagrama de Moran:** representação gráfica da autocorrelação espacial global.
- **Dispersão LISA:** gráfico com regressões locais por cluster LISA.
- **Tabela LISA:** lista interativa com IDH, cluster LISA e p-valor para cada município.
- **Interface HTML Responsiva:** pode ser executada diretamente no navegador (offline ou local).

---

## 🛠️ Tecnologias Utilizadas

- Python  
- GeoPandas  
- PySAL  
- Plotly  
- Folium  
- Pandas  
- HTML + JavaScript (Leaflet.js, DataTables.js)

---

## 🚀 Como Usar Localmente

1. Clone ou baixe este repositório:
   ```bash
   git clone https://github.com/Fredson-Alves/Interface-LISA-Interativa-HTML.git

2. Extraia o conteúdo do arquivo mapa_lisa.7z (requer software de descompactação como 7-Zip).

3. Execute o painel abrindo o arquivo painel_lisa.html no seu navegador.

⚠️ Importante: o GitHub não permite a visualização direta de arquivos com mais de 25 MB. Por isso, o mapa interativo (mapa_lisa.html) foi compactado. Para utilizar a interface completa, é necessário descompactar esse arquivo localmente.

📁 Estrutura do Projeto
Interface-LISA-Interativa-HTML/
│
├── painel_lisa.html          # Página principal da interface
├── mapa_lisa.7z              # Arquivo zipado com o mapa interativo
├── moran_diagrama.html       # Diagrama de Moran
├── disp_lisa.html            # Dispersão LISA
├── tabela.html               # Tabela LISA interativa
└── .github/                  # Fluxos de trabalho (CI/CD)

🤖 Apoio da Assistente LISA (IA)

Este projeto contou com o suporte da assistente virtual LISA, uma IA especializada em análise espacial, que auxiliou na transposição de um script original em R para Python, garantindo aderência metodológica e estatística.

🤝 Contribuições

Contribuições são bem-vindas!
Sinta-se livre para abrir uma issue, propor melhorias, ou adaptar a interface para outros indicadores geográficos.

📬 Contato

Desenvolvido por Fredson Alves.

Dúvidas ou sugestões? Envie uma mensagem ou abra uma issue aqui no GitHub.
