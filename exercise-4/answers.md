# Perguntas

1. Qual comando principal para iniciar o treinamento de um modelo?

Existem duas alternativas: utilizar o `fit` que vai realizar o treinamento considerando as *features* `X` e o objetivo `y`.
Contudo, o `scikit-learn` fornece uma alternativa chamada `fit_transform` disponível para alguns modelos que, além de realizar o treinamento, aplica
as transformações aos dados em um único passo.

2. Qual comando utilizado para classificação das amostras?

Para classificação devemos utilizar a função `predict` onde podemos passar as *features* da(s) amostra(s) e termos a lista de classificação.

3. Para que servem os pipelines?

4. Como podemos usar uma árvore de decisão para realizar uma predição numérica?

5. O que são as fronteiras de decisão?

6. Qual comando utilizado para particionamento de dados entre treino e teste? Quais seus principais argumentos?

7. Considerando um classificador do tipo vizinhos mais próximos, como especificar quantos vizinhos devem ser considerados no processo de classificação?

8. Considerando um classificador do tipo vizinhos mais próximos, qual o impacto em se utilizar poderação tipo uniforme ou baseada em distância?

9. Considerando o classificar do tipo Naive Bayes, como especificar as probabilidades a priori das classes diretamente, ou seja, sem computar a partir dos dados?

10. Considerando os datasets “moons”, “circles” e “linearly separable”. Qual classificador apresenta a melhor eficácia para cada um e qual apresenta a pior eficácia? Justifique.

11. Considerando classificadores do tipo árvore de decisão, o que é chamado de “caminho de decisão”?
