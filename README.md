# Final Project - The Rumos Bank Marketing Campaign

Este projecto foi desenvolvido no âmbito do unidade curricular Fundamentos de Machine Learning pertencente à pós-graduação em Data Science.

O objetivo é criar um modelo que ajude a equipa de marketing de um banco a seleccionar os melhores candidatos a ser alvo de uma campanha de depósitos a prazo, reduzindo assim o custo do negócio.

De forma a alcançar esse objectivo os passos a seguir são:


*   Fazer uma pequena análise exploratória do dataset
*   Fazer uma primeira seleção dos melhores modelos utilizando a ROC curve
*   Dos melhores modelos escolher o que minimiza o custo do negócio
*   Verificar as features mais relevantes para identificar bons candidatos
*   Perceber o benefício que o modelo tem no custo da campanha ao banco
*   Verificar se o modelo escolhido tem estabilidade para diferentes random states

<br>
<br>


**Conclusão**

Em conclusão, conseguimos encontrar um modelo que consegue ajudar a equipa de marketing a seleccionar clientes com mais probabilidade de aderirem ao depósito a prazo e assim minimizar os custos que o banco teria sem nenhum modelo.

O modelo neste caso é o Random Forest com os parâmetros :

max_depth=8, min_samples_split=6, n_estimators=10

Com estes parâmetros, embora o modelo apenas consiga identificar 52% de todos os possíveis bons candidatos (TP) e dos que identifica apenas 43% o realmente são, consegue reduzir o custo da campanha em cerca de 67%.