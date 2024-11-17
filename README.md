# ProjetoKNNRESTICGrupo2
Projeto Referente à Unidade 9 da Trilha de Ciência de Dados do ResTIC36, Grupo 2.

# **Relatório Técnico: Implementação do Algoritmo k-Nearest Neighbors (kNN) Aplicado ao Instagram**

## **Descrição do Projeto**
Este projeto utiliza o algoritmo **k-Nearest Neighbors (kNN)** para explorar e analisar dados de influenciadores do Instagram, com foco em prever padrões de engajamento e alcance. O trabalho inclui desde o pré-processamento dos dados até a validação do modelo e a análise dos resultados, fornecendo insights sobre variáveis-chave como número de seguidores, média de curtidas e taxa de engajamento.

O principal objetivo é avaliar a eficácia do kNN como modelo preditivo em um cenário real, destacando limitações e melhorias possíveis.

---

## **Como Executar no Google Colab**

### **Passo a Passo**
1. **Acesse o Notebook**:
    - Abra o Google Colab e importe o notebook utilizando o link do repositório ou faça upload manual do arquivo `KNN-Influencers.ipynb`.

2. **Carregue os Dados**:
    - Certifique-se de que o arquivo de dados está disponível no Google Drive ou faça o upload manual. Atualize os caminhos no notebook conforme necessário.

3. **Instale Dependências**:
    - Execute a célula que contém o código para instalar as bibliotecas necessárias no ambiente do Colab:
      ```python
      !pip install pandas numpy scikit-learn matplotlib seaborn
      ```

4. **Execute o Notebook**:
    - Siga as células sequencialmente para realizar as análises:
      - **Pré-processamento dos Dados**: Inclui limpeza, normalização e transformações.
      - **Treinamento do Modelo kNN**: Configuração do algoritmo, validação cruzada e otimização de hiperparâmetros.
      - **Visualizações**: Geração de gráficos e análise de correlações.

5. **Exportação do Relatório**:
    - Use a funcionalidade do Google Colab para exportar o notebook como PDF:
      - Vá para `Arquivo > Fazer Download > Fazer download como PDF`.

---

## **Estrutura do Notebook**

- **Introdução**: Apresentação do problema e objetivos do projeto.
- **Pré-processamento**: Limpeza dos dados e transformações, incluindo normalização e tratamento de valores ausentes.
- **Análise Exploratória**: Gráficos e matrizes de correlação para explorar padrões nos dados.
- **Implementação do Modelo**: Configuração do algoritmo kNN, otimização de hiperparâmetros e validação cruzada.
- **Resultados e Discussão**: Avaliação das métricas e considerações sobre o desempenho do modelo.
- **Exportação**: Instruções e código para salvar os resultados e o relatório em PDF.

---

## **Tecnologias Utilizadas**
- **Ambiente de Desenvolvimento**:
    - Google Colab
- **Bibliotecas**:
    - Pandas
    - Numpy
    - Scikit-Learn
    - Matplotlib
    - Seaborn

## **Autores e Colaboradores**

- **Caio Franco e Camilo Alves Mascarenhas**

Se você tiver dúvidas ou sugestões, sinta-se à vontade para entrar em contato!
