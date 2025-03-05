<img src="./img/gif v1.gif" min-width="400px" max-width="400px" width="400px" align="right" alt="Computador iuriCode">
<p>
  <div align="right"> 
<a href="./readme.md"> <img src="./img/LogoUK.png" alt="Logo UK" width="30"/></a><a href="./leiame.md"> <img src="./img/logoBrazil.png" alt="Logo Brasil" width="30"/> </a>
</div>
  <H1><b> Victor Sérgio Silva Barros </b> </H1>
</p> 

<img src="./img/dio.png" alt="DIO Logo" width="200"/>
<img src="./img/artificial-intelligence.png" alt="Artificial Intelligence Logo" width="200"/>

# Cálculo de Métricas de Avaliação de Aprendizado

Este projeto é baseado no [laboratório da DIO](https://web.dio.me/lab/calculo-de-metricas-de-avaliacao-de-aprendizado/learning/8c981faa-c9db-4a02-bad0-87035e170684).


## Visão Geral

O cálculo de métricas de avaliação de aprendizado é essencial para medir a performance de modelos de machine learning. Este projeto demonstra como calcular e interpretar diversas métricas de avaliação.

## Descrição do Desafio

Cálculo de Métricas de Avaliação de Aprendizado

Neste projeto, vamos calcular as principais métricas para avaliação de modelos de classificação de dados, como acurácia, sensibilidade (recall), especificidade, precisão e F-score. Para que seja possível implementar estas funções, você deve utilizar os métodos e suas fórmulas correspondentes (Tabela 1).

Para a leitura dos valores de VP, VN, FP e FN, será necessário escolher uma matriz de confusão para a base dos cálculos. Essa matriz você pode escolher de forma arbitrária, pois nosso objetivo é entender como funciona cada métrica.

<img src="./img/Tabela 1.png" alt="Tabela 1" width="600"/>

Tabela 1: Visão geral das métricas usadas para avaliar métodos de classificação. VP: verdadeiros positivos; FN: falsos negativos; FP: falsos positivos; VN: verdadeiros negativos; P: precisão; S: sensibilidade; N: total de elementos.

## Requisitos

- Python 3.x
- Scikit-learn
- NumPy
- Pandas
- Matplotlib

## Instalação

1. Clone o repositório:
    ```sh
    git clone https://github.com/your-repo/calculo-metricas-avaliacao.git
    ```
2. Navegue até o diretório do projeto:
    ```sh
    cd calculo-metricas-avaliacao
    ```
3. Instale os pacotes necessários:
    ```sh
    pip install -r requirements.txt
    ```

## Uso

1. Prepare seu conjunto de dados e coloque-o no diretório `data`.
2. Execute o script de cálculo de métricas:
    ```sh
    python calcular_metricas.py
    ```

## Colab

Você também pode executar o projeto usando o Google Colab. Abra o seguinte notebook no Colab:
[Cálculo de Métricas Notebook](https://github.com/vicssb/Training-Neural-Networks-with-Transfer-Learning/blob/main/notebooks/transfer-learning.ipynb)

## Resultados

Após a execução, a performance do modelo será avaliada e os resultados serão exibidos. Você pode visualizar o processo de treinamento e os resultados usando o TensorBoard.

## Licença

Este projeto está licenciado sob a licença MIT.