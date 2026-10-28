# Política de Governança de LLM e IA Generativa

## 1. Finalidade

Definir regras obrigatórias para o uso de LLMs e IA Generativa na organização, reduzindo riscos de vazamento de dados, decisões incorretas, violação regulatória e abuso de sistemas.

## 2. Aplicabilidade

Todos os colaboradores, terceiros e sistemas que utilizem, integrem ou desenvolvam soluções com LLM e IA Generativa.

## 3. Diretrizes

1. Todo caso de uso deve ser registrado no inventário de IA (pasta 04-ai-inventory) antes de entrar em produção.
2. Todo caso de uso deve ser classificado por risco (baixo, médio, alto, crítico) conforme a pasta 02-ai-risk-management.
3. Dados pessoais, confidenciais, segredos comerciais, credenciais e código proprietário não podem ser inseridos em ferramentas não aprovadas.
4. Somente provedores aprovados e com contrato que vede o uso dos dados da organização para treinamento podem ser utilizados em dados internos.
5. Resultados de LLM não podem ser tratados como fonte única para decisões de alto impacto; aplica-se a supervisão humana (pasta 21).
6. Conteúdo gerado por IA destinado a público externo deve ser revisado por pessoa responsável e, quando exigido, identificado como gerado por IA.
7. Agentes com acesso a ferramentas devem operar com privilégio mínimo, escopo limitado e aprovação humana para ações irreversíveis ou de alto impacto.
8. Aplicações com RAG devem respeitar as permissões de acesso da fonte original dos documentos.
9. Prompts de sistema não devem conter segredos e devem ser tratados como ativos sujeitos a controle de versão.
10. Todo caso de uso de risco alto ou crítico exige testes adversariais antes da liberação e a cada mudança relevante de modelo, prompt ou dados.
11. Logs de interação devem ser mantidos conforme a política de retenção, com proteção de dados pessoais.
12. Incidentes envolvendo LLM seguem o processo da pasta 18-gestao-de-incidentes-ia.

## 4. Proibições

- Uso de LLM para decisões automatizadas com efeito jurídico ou significativo sobre pessoas sem supervisão humana e base legal
- Geração de conteúdo enganoso, deepfakes não autorizados ou falsificação de identidade
- Tentativa de contornar controles de segurança do modelo (jailbreak) fora de testes autorizados
- Uso de contas pessoais de IA para tratar informação corporativa

## 5. Exceções

Exceções devem ser justificadas, temporárias, avaliadas quanto ao risco, aprovadas pelo Comitê de Governança de IA e registradas em registro-incidentes-excecoes-llm.md.

## 6. Não conformidade

O descumprimento sujeita o responsável às medidas previstas nas políticas internas.

## 7. Revisão

Esta política é revisada no mínimo anualmente ou após mudança regulatória, incidente relevante ou alteração significativa na tecnologia.

## Referências

- NIST AI 600-1 (Generative AI Profile), ações das funções Govern e Manage
- ISO/IEC 42001:2023, cláusulas 5 (Liderança) e 8 (Operação) e Anexo A
- OWASP Top 10 for LLM Applications (2025)
- LGPD, Arts. 6º, 7º e 20
- EU AI Act, Art. 50
