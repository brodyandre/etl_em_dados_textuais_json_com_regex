# 🏡 Locação de Imóveis - Processo de Limpeza e Transformação de Dados

## 📌 Objetivo
Este projeto tem como objetivo realizar o processo de **limpeza, normalização e transformação de dados** textuais extraídos de um arquivo JSON contendo informações sobre locações de imóveis. utilizamos processamento de dados textuais e regex (expressões regulares)

---

## 🔍 **Estrutura do Projeto e Base de Dados**

```bash
📦 analise_de_atraso_de_pagamentos_de_locacao_de_imoveis
├── 📂 data
│   └── 🗂️ dados_locacao_imoveis.json
├── 📂 notebooks
│   └── 📓 limpeza_transformacao_dados.ipynb
└── 📄 README.md
```

- `data`: Contém os dados brutos em formato JSON. A base de dados utilizada pode ser acessada através do link: [dados_locacao_imoveis.json](https://cdn3.gnarususercontent.com.br/2928-transformacao-manipulacao-dados/dados_locacao_imoveis.json).
- `notebooks`: Contém o notebook utilizado para processamento dos dados.
- `README.md`: Documentação do projeto.

---

## ⚙️ **Tecnologias Utilizadas**

- ![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
- ![NumPy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
- ![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
- ![Regex](https://img.shields.io/badge/Regex-00599C?style=for-the-badge&logo=regex&logoColor=white)
- ![Unicodedata](https://img.shields.io/badge/Unicodedata-FFCA28?style=for-the-badge)

---

## 🛠️ **Processo de ETL (Limpeza e Transformação)**
1. **Leitura dos Dados**:
   - Carregamento dos dados JSON para um DataFrame.

2. **Normalização da Estrutura**:
   - Utilização de `pd.json_normalize` para expandir estruturas aninhadas.

3. **Explosão de Colunas**:
   - Expansão de listas contidas nas colunas com o método `.explode()`.

4. **Remoção de Substrings com Regex**:
   - Remoção de padrões indesejados utilizando expressões regulares.

5. **Conversão de Datas**:
   - Transformação de strings para objetos `datetime`.

6. **Limpeza de Valores Monetários**:
   - Remoção de símbolos e formatações inadequadas com Regex.

7. **Substituição de Vírgulas por Pontos**:
   - Adequação para o padrão numérico internacional.

8. **Conversão para Tipo Numérico**:
   - Transformação final para tipo `float64`.

---

## 🚀 **Como Executar o Projeto**

1. Clone o repositório:

```bash
git clone https://github.com/brodyandre/analise_de_atraso_de_pagamentos_de_locacao_de_imoveis.git
```

2. Acesse o diretório do projeto:

```bash
cd analise_de_atraso_de_pagamentos_de_locacao_de_imoveis
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Execute o notebook:

Abra o arquivo `.ipynb` no Jupyter Notebook ou JupyterLab e execute as células.

---

## 📊 **Resultados Esperados**
- Dados normalizados e prontos para análise.
- Estruturas de DataFrame otimizadas para manipulação e visualização.

---

## 🤝 **Contribuindo**
Sinta-se à vontade para abrir issues e enviar pull requests. Todas as contribuições são bem-vindas!

---

## 📫 **Contato**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/luizandredesouza)
[![GitHub](https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github)](https://github.com/brodyandre)

---

✨ Projeto desenvolvido por **Luiz André de Souza**.

