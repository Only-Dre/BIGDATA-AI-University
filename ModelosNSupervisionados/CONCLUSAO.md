## Conclusão

A aplicação conjunta dos três algoritmos de agrupamento:
K-Means, DBSCAN e Hierarchical Clustering — que permitiu compreender melhor o comportamento operacional das máquinas a partir dos dados de sensores, sem a necessidade de rótulos prévios.

O K-Means apresentou uma separação clara entre os estados de funcionamento, sendo útil para identificar grupos centrais e padrões gerais de operação normal.
O método hierárquico (principalmente com o linkage **ward**) auxiliou na interpretação estrutural dos dados, mostrando relações entre os grupos e sugerindo um número adequado de clusters.

Já o DBSCAN destacou-se pela capacidade de detectar **anomalias** e pontos fora do padrão, informação essencial para alertas de manutenção preditiva.
De forma geral, os resultados indicam que os algoritmos se complementam: enquanto K-Means e Hierarchical são mais eficazes na identificação de estados estáveis da máquina, o DBSCAN traz insights importantes sobre eventos esporádicos que podem representar desgaste, sobrecarga ou falhas iminentes. 
Assim, recomenda-se o uso combinado dos métodos para apoiar decisões estratégicas no setor industrial, aumentando a confiabilidade do equipamento e contribuindo para a redução de custos com paradas inesperadas.
