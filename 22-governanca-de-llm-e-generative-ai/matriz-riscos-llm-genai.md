# Matriz de Riscos de LLM e IA Generativa

Mapeamento dos principais riscos ao OWASP Top 10 for LLM Applications (2025), com controles e evidências.

| ID OWASP | Risco | Impacto principal | Controles recomendados | Evidência |
|---|---|---|---|---|
| LLM01 | Prompt Injection | Execução de instruções indevidas, vazamento, ações não autorizadas | Separação de instruções e dados, filtros de entrada, privilégio mínimo, aprovação humana | Resultados de red teaming |
| LLM02 | Divulgação de Informação Sensível | Vazamento de dados pessoais e confidenciais | DLP, minimização, mascaramento, contratos sem treinamento com dados | Relatório de DLP, RIPD |
| LLM03 | Cadeia de Suprimentos | Modelos, pacotes ou datasets comprometidos | Avaliação de fornecedores, verificação de integridade, SBOM/AIBOM | Due diligence, inventário de componentes |
| LLM04 | Envenenamento de Dados e Modelo | Comportamento manipulado ou enviesado | Validação de dados de treino e RAG, controle de origem, monitoramento | Trilha de proveniência |
| LLM05 | Tratamento Inadequado de Saída | XSS, injeção de comandos, execução de código | Validação e sanitização de saídas, sandbox | Testes de segurança de aplicação |
| LLM06 | Agência Excessiva | Ações destrutivas ou indevidas por agentes | Escopo mínimo de ferramentas, human-in-the-loop, limites de transação | Matriz de permissões do agente |
| LLM07 | Vazamento de Prompt de Sistema | Exposição de lógica e segredos | Sem segredos no prompt, controles externos ao modelo | Revisão de prompts |
| LLM08 | Fragilidades em Vetores e Embeddings | Acesso indevido a dados via RAG | Controle de acesso por documento, segregação de índices | Testes de autorização no RAG |
| LLM09 | Desinformação | Decisões incorretas, alucinações, dano reputacional | Ancoragem em fontes, citação, revisão humana, avaliação de qualidade | Métricas de acurácia e alucinação |
| LLM10 | Consumo Ilimitado | Negação de serviço, custo excessivo | Rate limiting, quotas, monitoramento de custo | Alertas e relatórios de consumo |

## Riscos adicionais (NIST AI 600-1)

| Risco | Controle |
|---|---|
| Confabulação | Verificação factual e supervisão humana |
| Privacidade de dados | RIPD/DPIA e minimização |
| Propriedade intelectual | Revisão jurídica de saídas e termos do provedor |
| Viés e homogeneização | Testes de equidade e diversidade de fontes |
| Conteúdo nocivo ou abusivo | Filtros de moderação e políticas de uso |
| Integridade da informação | Identificação de conteúdo gerado por IA |

## Referências

- OWASP Top 10 for LLM Applications (2025)
- NIST AI 600-1, seção de riscos específicos de IA Generativa
- MITRE ATLAS
- ISO/IEC 23894:2023
