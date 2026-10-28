# Checklist de Validação para Soluções com LLM e IA Generativa

Preencher antes da liberação em produção e a cada mudança relevante.

**Caso de uso:** ____________________
**Proprietário:** ____________________
**Data:** ____/____/______
**Nível de risco:** ( ) Baixo ( ) Médio ( ) Alto ( ) Crítico

## 1. Governança

- [ ] Caso de uso registrado no inventário de IA
- [ ] Risco classificado e aprovado conforme o nível
- [ ] Proprietário e responsável técnico definidos
- [ ] Aprovação do Comitê de Governança de IA (risco alto ou crítico)

## 2. Privacidade e conformidade

- [ ] Base legal identificada (LGPD)
- [ ] RIPD/DPIA realizado quando aplicável
- [ ] Contrato do provedor veda treinamento com dados da organização
- [ ] Transferência internacional de dados avaliada
- [ ] Obrigações de transparência avaliadas (EU AI Act, Art. 50, quando aplicável)

## 3. Segurança

- [ ] Teste de prompt injection (direto e indireto) executado
- [ ] Validação e sanitização das saídas implementadas
- [ ] Prompt de sistema sem segredos
- [ ] Controle de acesso aplicado ao RAG por documento
- [ ] Agentes com privilégio mínimo e aprovação humana para ações críticas
- [ ] Rate limiting e monitoramento de consumo ativos
- [ ] Cadeia de suprimentos do modelo avaliada

## 4. Qualidade e confiabilidade

- [ ] Métricas de acurácia e alucinação definidas e medidas
- [ ] Teste de viés e conteúdo nocivo executado
- [ ] Mecanismo de citação de fontes ou ancoragem quando aplicável
- [ ] Supervisão humana definida (pasta 21)

## 5. Operação

- [ ] Logging e retenção configurados com proteção de dados pessoais
- [ ] Processo de resposta a incidentes definido (pasta 18)
- [ ] Plano de monitoramento contínuo (pasta 11)
- [ ] Plano de reversão (rollback) documentado

## Resultado

( ) Aprovado ( ) Aprovado com condições ( ) Reprovado

**Condições / observações:** ____________________

**Assinatura do proprietário:** ____________________
**Assinatura de Segurança / Privacidade:** ____________________

## Referências

- OWASP Top 10 for LLM Applications (2025)
- NIST AI 600-1 e NIST AI 100-1 (funções Govern, Map, Measure, Manage)
- ISO/IEC 42001:2023
