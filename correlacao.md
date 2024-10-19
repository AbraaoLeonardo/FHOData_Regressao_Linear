## O que é correlação?
A correlação é uma medida que indica a relação entre duas variáveis. Em termos simples, ela mostra como a alteração em uma variável pode impactar outra.

Por exemplo, considere uma casa com 10 paredes que precisam ser pintadas. Se temos um pintor que consegue pintar duas paredes por dia, a quantidade de dias necessários para concluir o trabalho dependerá do número de paredes. Assim, quanto mais paredes a casa tiver, maior será o número de dias necessários para pintá-las.

Além disso, se aumentarmos a quantidade de pintores disponíveis, o tempo total para finalizar a pintura será reduzido. Isso ilustra como a correlação entre o número de paredes, o número de pintores e o tempo necessário para pintar a casa é dinâmica e interdependente.

## Quem descobriu a correlação
O coeficiente de correlação foi descoberto pelo geógrafo, meterolista, estatistica e inventor Francis Galton. Auxiliou o seu tio Charles Darwin a analisar e interpretar os dados da teoria da evolução.

Através da teoria definida por Galton, Karl Pearson refinou o processo e criou o coeficiente de correlação de Pearson, o qual é utilizado ainda hoje.

## Como calcular o coeficiente de correlação?
Agora que entendemos o que é correlação, precisaremos entender como calcular ele. Para isso, precisaremos da seguinte formula:
$r = \frac{\sum_(X_i - \bar{X})\times(Y_i - \bar{Y})}{\sqrt{\sum_(X_i - \bar{X})^2\times(Y_i - \bar{Y})^2}}$

Analisando a fórmula, identificamos o componente $X_i - \bar{X}$, que representa a diferença entre um valor individual $X_i$ e a média $\bar{X}$. Na parte superior da fórmula, calculamos a soma dos produtos das diferenças de $X$ e $Y$. Essa etapa é crucial para entender como as variações em $X$ se relacionam com as variações em $Y$.

Na parte inferior, encontramos a raiz quadrada da soma dos produtos das diferenças dos valores em relação às suas médias. Essa expressão é fundamental para normalizar o resultado, permitindo uma interpretação adequada do coeficiente de correlação. Essa fórmula, portanto, nos ajuda a quantificar a relação entre as duas variáveis, revelando tanto a direção quanto a força dessa relação.

Ao calcular o coeficiente de correlação, o resultado varia entre -1 e 1. Um valor próximo de 1 indica uma forte correlação positiva entre as variáveis, enquanto um valor próximo de -1 sugere uma forte correlação negativa. Quando o coeficiente é exatamente 1 ou -1, estabelece-se uma correlação perfeita, seja positiva ou negativa. Por outro lado, se o coeficiente se aproxima de 0, isso indica uma correlação fraca ou até inexistente entre as variáveis analisadas. Essa medida é essencial para entender a relação entre diferentes conjuntos de dados e orientar decisões baseadas em suas interações.

## Como isso impactá no nossos projetos de data science?
Agora que entendemos o que é correlação, e como calcular, conseguimos entender a importância delas em nossos modelos de ciência de dados. pois permite identificar e quantificar a relação entre variáveis. Essa análise ajuda os cientistas de dados a entender como diferentes fatores interagem, podendo revelar padrões ocultos que influenciam os resultados.

Um simples exemplo de uso delas é na parte de exploração de dados, onde podemos definir quais variáveis são importantes para nossos modelos, e reduzir o custo computacional para processar esses dados.

## Correlação não é causalidade!!!!
Embora a correlação seja uma ferramenta valiosa na análise de dados, é fundamental entender que uma forte correlação entre as variáveis $X$ e $Y$ não implica necessariamente que alterações em $X$ impactarão $Y$.

Por exemplo, entre 2004 e 2020, observou-se uma forte correlação entre o número de pessoas que pesquisaram no Google a frase “**why isn't 11 pronounced onety one**” e o consumo de querosene na Romênia. Essa relação, à primeira vista curiosa, não sugere que um fator influencia o outro; na verdade, é um exemplo de correlação espúria, onde duas variáveis estão correlacionadas sem qualquer relação causal.

Esse tipo de situação é bem ilustrado pelo site [Tyler Vigen](https://www.tylervigen.com/spurious-correlations), que apresenta diversos casos de correlações fortes entre variáveis que não têm uma conexão causal real. É um lembrete importante de que, ao analisar dados, é essencial diferenciar entre correlação e causalidade para evitar conclusões erradas.

## Conclusão
Dado tudo que abordamos, a correlação é uma ferramenta poderosa para entender relações entre variáveis, sendo crucial para projetos de data science. Compreender como calcular o coeficiente de correlação permite que profissionais identifiquem padrões significativos nos dados, orientando a tomada de decisões. No entanto, é fundamental lembrar que correlação não implica causalidade; uma associação entre variáveis não garante que uma cause a outra. Essa distinção é vital para evitar interpretações errôneas e garantir a robustez dos insights gerados. Ao integrar esses conceitos, podemos construir análises mais precisas e eficazes, elevando a qualidade dos nossos projetos.