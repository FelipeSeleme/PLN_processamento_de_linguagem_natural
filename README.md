# Processamento de Linguagem Natural (PLN) 📖

Este repositório contém um notebook Jupyter demonstrando técnicas fundamentais de **Processamento de Linguagem Natural (PLN)** com Python. O objetivo é apresentar conceitos práticos e teóricos sobre PLN, explorando bibliotecas populares e técnicas essenciais para análise e manipulação de textos.

## 📌 Conteúdo do Notebook

O notebook aborda os seguintes tópicos:

1. **Introdução ao PLN** – Visão geral do processamento de linguagem natural e suas aplicações.
2. **Pré-processamento de Texto** – Técnicas como tokenização, remoção de stopwords, stemming e lematização.
3. **Extração de Características** – Representação de texto com Bag-of-Words (BoW) e TF-IDF.
4. **Modelagem de Texto** – Implementação de modelos básicos para análise de sentimentos e classificação de texto.
5. **Modelos Avançados de PLN** – Utilização de embeddings e redes neurais para tarefas de PLN.
6. **Conclusão** – Resumo dos aprendizados e direções futuras.

## 🛠️ Tecnologias Utilizadas

- Python 3
- NLTK
- spaCy
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🚀 Como Executar

1. Clone este repositório:
   ```sh
   git clone https://github.com/FelipeSeleme/PLN_processamento_de_linguagem_natural.git
   ```
2. Acesse a pasta do projeto:
   ```sh
   cd PLN_processamento_de_linguagem_natural
   ```
3. Crie um ambiente virtual (opcional, mas recomendado):
   ```sh
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows
   ```
4. Instale as dependências:
   ```sh
   pip install -r requirements.txt
   ```
5. Execute o Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
6. Abra o notebook `pln.ipynb` e explore o conteúdo! 🚀

## 📌 Observações

- Certifique-se de baixar modelos do spaCy, se necessário:
  ```sh
  python -m spacy download en_core_web_sm
  ```
- Algumas análises podem exigir datasets específicos. Caso necessário, verifique as instruções no próprio notebook.

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Sinta-se à vontade para usar e contribuir! 😊
