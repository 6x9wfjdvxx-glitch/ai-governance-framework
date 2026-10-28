# Matriz de Validação de Modelos de IA

Escopo e profundidade da validação por componente. Legenda: B = Baixo, M = Médio, A = Alto, C = Crítico.

| Componente de validação | O que avaliar | B | M | A | C | Evidência |
|---|---|---|---|---|---|---|
| Solidez conceitual | Adequação da metodologia, premissas, escolha do algoritmo e limitações | Revisão | Sim | Sim | Sim, com modelo desafiante | Parecer de validação |
| Qualidade dos dados | Representatividade, completude, proveniência, vieses e vazamento de dados | Revisão | Sim | Sim | Sim, com reprodução | Relatório de dados |
| Implementação | Código, pipeline, parâmetros e consistência com a documentação | Amostral | Sim | Sim | Replicação independente | Evidência de testes |
| Desempenho | Acurácia, precisão, recall, AUC, erro e calibração conforme o caso de uso | Sim | Sim | Sim | Sim, por segmento | Relatório de métricas |
| Back-testing e outcomes analysis | Comparação entre previsões e resultados observados | Opcional | Sim | Sim | Sim, periódico | Relatório de back-testing |
| Robustez e estabilidade | Sensibilidade a variações, ruído e cenários extremos | Opcional | Sim | Sim | Sim, com stress test | Relatório de robustez |
| Equidade e viés | Desempenho por grupos e impacto desigual | Opcional | Sim | Sim | Sim, com análise de causa | Relatório de equidade |
| Explicabilidade | Interpretabilidade global e local das decisões | Opcional | Sim | Sim | Sim, com validação de explicações | Relatório de explicabilidade |
| Segurança adversarial | Evasão, envenenamento, extração e inversão de modelo | Opcional | Opcional | Sim | Sim, com red teaming | Resultados de testes |
| Monitoramento contínuo | Métricas, limiares, deriva e plano de resposta | Sim | Sim | Sim | Sim, com alertas | Plano de monitoramento |
| Governança de uso | Limites de uso, supervisão humana e treinamento dos usuários | Sim | Sim | Sim | Sim | Registro de aprovações |

## Métricas de monitoramento de referência

| Métrica | Finalidade | Limiar de referência |
|---|---|---|
| PSI (Population Stability Index) | Estabilidade da população | Atenção acima de 0,10; ação acima de 0,25 |
| Degradação de desempenho | Queda frente ao baseline | Definir por modelo, tipicamente 5% a 10% |
| Taxa de override humano | Discordância entre modelo e revisor | Definir por modelo e revisar tendências |
| Disparidade entre grupos | Diferença de desempenho ou resultado | Definir por caso de uso e base legal |

Os limiares são valores de referência de mercado e devem ser calibrados para cada modelo e aprovados pelo Comitê.

## Referências

- SR 11-7 / OCC 2011-12: solidez conceitual, monitoramento contínuo e outcomes analysis
- NIST AI 100-1, função Measure
- ISO/IEC TR 24029-1 (robustez)
- MITRE ATLAS (ameaças adversariais)
- PRA SS1/23, princípios 3 e 4
