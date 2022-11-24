Análise exploratória de dados do Enem de 2019 no estado de SP

Primeiramente foi realizado o tratamento dos dados, basicamente limpando dados missing, dados que não seria relevantes para esta análise, renomeando algumas colunas e
retirando do dataframe os candidatos treineiros

Passando à análise exploratória, foi calculada a média simples total da prova, a contagem de notas 0 em cada matéria e em cada componente da redação

A fim de se analisar as notas comparadas ao sexo, raça e tipo de escolar, foram utilizados gráficos de boxplot, da biblioteca plotly, para se ter uma ideia da distribuição
das notas. Vale ressaltar que não foram removidos os dados outliers, considerando que o objeto da análise são as notas dos cancidatos.

NOTA: os gráficos do projeto original desta análise foram feitos com a biblioteca plotly, visto que, os gráficos interativos da mesma proporcionam uma melhor análise.
Porém, devido ao limite de tamanho para exibição do github, foi necessária a alteração dos gráficos para a biblioteca seaborn.
