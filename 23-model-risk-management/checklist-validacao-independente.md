# Checklist de Validação Independente de Modelos

Preencher pelo validador independente antes da aprovação e a cada revalidação.

**Modelo:** ____________________
**Versão:** ____________________
**Proprietário:** ____________________
**Validador:** ____________________
**Data:** ____/____/______
**Nível de risco:** ( ) Baixo ( ) Médio ( ) Alto ( ) Crítico

## 1. Independência e governança

- [ ] Validador independente do desenvolvimento e sem conflito de interesse
- [ ] Modelo registrado no inventário de IA
- [ ] Uso pretendido e limites de uso documentados
- [ ] Nível de risco classificado e justificado

## 2. Documentação

- [ ] Metodologia, premissas e limitações documentadas
- [ ] Dados de treino, validação e teste descritos
- [ ] Versionamento do código, dados e modelo
- [ ] Documentação suficiente para reprodução por terceiro

## 3. Dados

- [ ] Representatividade da população avaliada
- [ ] Qualidade, completude e proveniência verificadas
- [ ] Ausência de vazamento de dados entre treino e teste
- [ ] Vieses identificados e tratados
- [ ] Base legal e minimização de dados validadas (LGPD)

## 4. Desempenho e robustez

- [ ] Métricas adequadas ao caso de uso definidas e medidas
- [ ] Back-testing ou outcomes analysis realizado
- [ ] Teste de estabilidade e de cenários extremos
- [ ] Comparação com modelo desafiante ou benchmark
- [ ] Análise de desempenho por segmento e por grupo

## 5. Explicabilidade e supervisão

- [ ] Explicações das decisões avaliadas e compreensíveis
- [ ] Supervisão humana definida (pasta 21)
- [ ] Usuários treinados quanto aos limites do modelo

## 6. Segurança

- [ ] Testes adversariais executados quando exigido pelo nível de risco
- [ ] Controle de acesso e integridade do modelo e dos dados
- [ ] Cadeia de suprimentos e componentes de terceiros avaliados

## 7. Monitoramento

- [ ] Métricas e limiares de monitoramento definidos
- [ ] Gatilhos de revalidação definidos
- [ ] Plano de resposta a degradação e deriva
- [ ] Plano de reversão (rollback) e de descomissionamento

## Parecer

( ) Aprovado ( ) Aprovado com condições ( ) Reprovado

**Achados e condições:** ____________________

**Prazo de revalidação:** ____/____/______

**Assinatura do validador:** ____________________
**Assinatura do proprietário do modelo:** ____________________

## Referências

- SR 11-7 / OCC 2011-12, seção de validação de modelos
- PRA SS1/23, princípio 4 (validação independente)
- NIST AI 100-1, funções Measure e Manage
- EU AI Act, Arts. 9, 10 e 15
