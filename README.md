# ETL de Acidentes de Trânsito no Brasil (2017–2023)

**Carlos Emanuel**

## 🗂️ Descrição do Projeto

Este projeto realiza o carregamento e tratamento de dados de acidentes de trânsito ocorridos entre 2017 e 2023, fornecidos pela PRF (Polícia Rodoviária Federal). Foram aplicados filtros, transformações e geração de gráficos para entender padrões como:

- Acidentes com mais de 2 mortos
- Acidentes em dias da semana
- Acidentes com chuva por estado
- Análises cruzadas com variáveis relevantes


## 🔗 Fonte dos Dados

- [Portal de Dados Abertos PRF](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos)
- Arquivo usado: `acidentes_2017_2023.csv`  
*(Adicionado diretamente ao repositório)*


## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib / Seaborn
- Google Colab


## 🧪 Etapas do Projeto

1. **Extração dos dados** (.zip transformado em .csv e carregado no Colab)
2. **Exploração inicial** (`df.shape`, `df.columns`, `df.info()`)
3. **Tratamento dos dados** (valores ausentes, tipos de dados, renomeação)
4. **Análises específicas e cruzadas**
5. **Geração de gráficos** com `Matplotlib` e `Seaborn`


## 📊 Resultado Visual
Gráfico 1: https://github.com/carlosemanueln/ETL_acidentes_transito/blob/main/Gr%C3%A1fico%201.png

Gráfico 2: https://github.com/carlosemanueln/ETL_acidentes_transito/blob/main/Gr%C3%A1fico%202.png

## ▶️ Como Executar

1. Faça o download do arquivo `acidentes_2017_2023.csv`
2. Abra o `notebook.ipynb` no Google Colab ou Jupyter
3. Execute célula por célula, observando os comentários explicativos


## 📝 Observações

- Os dados foram tratados e limpos com cuidado, mas podem conter limitações por conta da origem pública.
- Todas as etapas possuem comentários linha por linha explicando a lógica usada.
- O arquivo original (.csv) não foi adicionado ao repositório por ultrapassar o limite de 25MB do GitHub

## 📬 Contato

Dúvidas ou sugestões? Me chame no GitHub:(https://github.com/carlosemanueln)
