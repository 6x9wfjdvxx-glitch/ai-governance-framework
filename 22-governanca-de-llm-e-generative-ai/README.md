# Governança de LLM e IA Generativa

## Objetivo

Estabelecer controles de governança para o uso, a aquisição e o desenvolvimento de Modelos de Linguagem de Grande Escala (LLMs) e sistemas de IA Generativa, assegurando uso seguro, lícito, transparente e alinhado aos requisitos de privacidade, segurança da informação e conformidade regulatória.

## Escopo

Aplica-se a:

- LLMs internos e de terceiros (APIs, plataformas SaaS e modelos de código aberto)
- Assistentes e copilotos de IA Generativa usados por colaboradores
- Aplicações com RAG (Retrieval-Augmented Generation) e bases vetoriais
- Agentes de IA com acesso a ferramentas, sistemas e dados
- Prompts de sistema, fine-tuning e integrações via plugins ou conectores

## Princípios

- Responsabilidade humana pelos resultados
- Minimização e proteção de dados
- Transparência sobre o uso de IA Generativa
- Segurança desde a concepção (security by design)
- Mitigação de alucinações e desinformação
- Privilégio mínimo para agentes e integrações
- Rastreabilidade e auditabilidade

## Responsabilidades

### Proprietário do Processo

- Classificar o caso de uso e o nível de risco
- Garantir o cumprimento da política e dos critérios de uso aceitável
- Manter o registro de incidentes e exceções

### Equipe de Tecnologia e Segurança

- Implementar controles técnicos (filtros, DLP, controle de acesso, logging)
- Executar testes adversariais (red teaming, prompt injection)
- Gerir fornecedores e a cadeia de suprimentos de modelos

### Privacidade e Jurídico

- Avaliar bases legais, transferência internacional e RIPD/DPIA
- Revisar termos contratuais de provedores de LLM

### Comitê de Governança de IA

- Aprovar a política e os casos de uso de alto risco
- Deliberar sobre exceções e incidentes relevantes

## Conteúdo da pasta

- politica-governanca-llm-genai.md
- matriz-riscos-llm-genai.md
- criterios-uso-aceitavel-llm.md
- checklist-validacao-llm-genai.md
- registro-incidentes-excecoes-llm.md

## Evidências

- Inventário de casos de uso de LLM aprovados
- Resultados de testes adversariais e de avaliação de qualidade
- Avaliações de impacto à privacidade (RIPD/DPIA)
- Logs de uso, aprovações e exceções
- Registros de incidentes e lições aprendidas

## Referências

- NIST AI 600-1: Artificial Intelligence Risk Management Framework: Generative AI Profile (2024)
- NIST AI 100-1: AI Risk Management Framework 1.0 (2023)
- OWASP Top 10 for LLM Applications (2025)
- ISO/IEC 42001:2023: Sistema de gestão de inteligência artificial
- ISO/IEC 23894:2023: Gestão de riscos de IA
- ISO/IEC 27001:2022: Sistemas de gestão de segurança da informação
- MITRE ATLAS: Adversarial Threat Landscape for AI Systems
- Regulamento (UE) 2024/1689 (EU AI Act), Art. 50 e Capítulo V
- Lei nº 13.709/2018 (LGPD)
