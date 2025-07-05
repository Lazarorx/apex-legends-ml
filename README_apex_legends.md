
# Previsão de Colocação no Apex Legends com Machine Learning

## Objetivo

Analisar o desempenho dos jogadores no Apex Legends e prever a colocação final da partida com base em estatísticas individuais como dano, abates, assistências e revives.

## Dataset usado

Dados de partidas da 15ª temporada do Apex Legends, contendo informações como duração, posição final, estatísticas de combate e participação da equipe.

Arquivo original: [CSV - apex_legends_temporada15](https://drive.google.com/file/d/1sH_rCzAzJRerFegsKAim2kTDCIis7o2K/view?usp=sharing)

## Técnicas aplicadas

- Análise exploratória de dados (EDA)
- Regressão Linear
- Árvore de Decisão
- Random Forest Regressor
- Avaliação de modelos com RMSE e R²
- Interpretação de coeficientes

## Ferramentas

- Google Colab
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Link para o notebook

[Notebook no Google Colab](https://colab.research.google.com/drive/1zYKeiM5VvJHm4iIoEVeb5MS5I4suyWgp)

## Conclusão

O modelo de regressão linear simples foi o que melhor se ajustou ao conjunto de dados, explicando cerca de 10% da variação na colocação final do jogador. Modelos mais complexos, como árvore de decisão e random forest, apresentaram overfitting e desempenho inferior, provavelmente devido ao tamanho reduzido e à variabilidade dos dados. A análise revelou que kills, dano e knockdowns têm maior impacto sobre a colocação final, embora o contexto da partida e ações do time ainda influenciem fortemente o resulta...
