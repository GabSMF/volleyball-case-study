# **SPRINT 2 - Testando Modelos**

Nessa sprint 2 primeiramente atualizamos o pré processamento pós a realização da EDA na sprint 1. Seguindo o que foi proposto no artigo do João Gabriel Gelli, realizamos um teste preliminar utilizando o KMeans e percebemos que os resultados estavam dando bem ruins por conta da distribuição dos dados. Apesar de que quando comparamos com os resultados propostos na literatura, os nossos podem ser considerados bem melhores que o da maioria.

Após percebermos esses resultados ""ruins"" decidimos fazer algumas mudanças na base para procurarmos melhorar o desempenho dos modelos.

Por conta disso nos dividimos em **3 funções**:

- **Feature Engineering**: 2 integrantes ficaram responsáveis por criar novas features a partir das existentes e procurar possíveis novas categorias.

- **Inserção do Time B**: Nossos testes preliminares consideraram somente as features do time A nas categorias. A proposta agora seria analisar se algum comportamento/feature do time B pode nos auxiliar

- **Adiantamento das Próximas Etapas e Testagem de outros modelos de Clustering**: Fomos adiantando os próximos passos do códigos com os resultados ruins mesmo, para quando tivermos a base melhorada apenas "rodarmos o código". Além disso já fomos testando outros modelos como o DBSCAN, que já tinhamos percebido anteriormente que poderia ter um resultado melhor por conta da distribuição dos registros. **OBS: RECOMENDAMOS ANALISAR PRIMEIRO O `teste_preliminar_kmeans.ipynb` já que foi o primeiro teste feito, os outros apenas sendo adaptações do mesmo**

EM ANDAMENTO: junção dos resultados e avaliação do "modelo preliminar conjunto"