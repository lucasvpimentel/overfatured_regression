# Previsão de Salários da NBA e Análise de Superfaturamento

## Visão Geral do Projeto

Este projeto utiliza aprendizado supervisionado, especificamente modelos de regressão linear, para prever os salários dos jogadores da NBA. O objetivo é identificar quais jogadores estão superfaturados comparando os salários previstos com os salários reais. Projeto da disciplina de introdução ao aprendizado de máquina

## Metodologia

Para uma análise de não só um ano independente, foi analisado o superfaturamente durante toda a carreira do jogador, e não apenas em um ano.

## Processamento de Dados

1. **Limpeza dos Dados:** Tratamento de valores ausentes e duplicados.
2. **Normalização:** Ajuste das variáveis para a mesma escala.
3. **Divisão dos Dados:** Separação em conjuntos de treino e teste.

## Treinamento do Modelo

1. **Seleção de Features:** Escolha das variáveis que impactam os salários.
2. **Treinamento:** Ajuste do modelo de regressão linear com os dados de treino.
3. **Ajuste de Hiperparâmetros:** Otimização dos parâmetros do modelo.

## Avaliação do Modelo

Avaliação usando:

- **Raiz do Erro Quadrático Médio (RMSE)**
- **Análise de Resíduos**

## Resultados

- Comparação entre salários previstos e reais.
- Lista de jogadores superfaturados.

## Conclusão

Resumo dos principais achados e identificação dos jogadores superfaturados.

## Dependências

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

## Uso

1. Clone o repositório:
   ```sh
   git clone https://github.com/seuusuario/nba-salary-prediction.git
