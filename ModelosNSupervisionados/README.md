# Conteúdo dos exercícios:

## Ex1 - Agrupamento de dados de sensores industriais

Uma fábrica de motores elétricos coleta continuamente dados de sensores de suas máquinas ao longo dos turnos de produção. Cada máquina registra quatro variáveis por minuto:

- temperatura (°C)
- vibração (mm/s)
- corrente (A)
- pressão (bar)

O objetivo é aplicar algoritmos de **aprendizado não supervisionado** para identificar padrões de funcionamento, possíveis estados de operação e indícios de falhas.

Serão utilizados três métodos de clusterização:

- K-Means  
- DBSCAN  
- Hierarchical Clustering (Agglomerative)

As análises devem permitir:

- detectar grupos naturais de operação,
- encontrar comportamentos irregulares,
- sugerir estados como carga leve, carga alta e sobreaquecimento,
- e identificar pontos anômalos (possíveis falhas ou eventos críticos).

---

## Ex2 - Visualização e comparação entre métodos de clusterização

Após aplicar cada algoritmo, o objetivo é gerar visualizações utilizando **PCA (redução de dimensionalidade)** para representar os clusters em 2D, facilitando a interpretação dos padrões.

As comparações devem abordar:

- clareza na separação dos grupos,
- detecção de ruído e anomalias (especialmente no DBSCAN),
- coerência dos agrupamentos formados,
- diferenças entre linkages no método hierárquico (ward, complete, average).

Ao final, espera-se concluir:

- qual método apresentou clusters mais bem definidos,
- qual técnica evidenciou melhor os pontos fora do padrão,
- e qual abordagem seria mais indicada para manutenção preditiva na fábrica.
