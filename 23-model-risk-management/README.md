# Gerenciamento de Risco de Modelo (Model Risk Management)

## Objetivo

Estabelecer o processo de gerenciamento de risco de modelo para sistemas de IA e modelos de Machine Learning, assegurando que sejam desenvolvidos, validados, implantados, monitorados e desativados de forma controlada, com desafio efetivo independente e rastreabilidade das decisões.

## Definição

Risco de modelo é o risco de consequências adversas decorrentes de decisões baseadas em resultados incorretos ou mal utilizados de modelos. Decorre de erros de projeto, implementação, dados, premissas, uso inadequado ou ausência de monitoramento.

## Escopo

Aplica-se a:

- Modelos de Machine Learning e estatísticos usados em decisões de negócio
- Modelos de IA desenvolvidos internamente
- Modelos de terceiros e de fornecedores (caixa-preta)
- Modelos de IA Generativa e LLMs, de forma complementar à pasta 22
- Modelos adaptados por fine-tuning ou recalibração

## Princípios

- Desafio efetivo e independente
- Proporcionalidade ao risco (classificação em níveis)
- Documentação suficiente para reprodução por terceiro
- Validação antes do uso e de forma contínua
- Monitoramento de desempenho, deriva e estabilidade
- Responsabilidade clara por modelo (proprietário, desenvolvedor, validador)
- Rastreabilidade do ciclo de vida completo

## Ciclo de vida do modelo

1. Concepção e definição de uso pretendido
2. Desenvolvimento e documentação
3. Validação independente
4. Aprovação e implantação
5. Monitoramento contínuo e outcomes analysis
6. Revalidação periódica ou por gatilho
7. Aposentadoria e descomissionamento

## Responsabilidades

### Proprietário do Modelo

- Definir o uso pretendido e os limites de uso
- Garantir a documentação e o monitoramento contínuo
- Reportar mudanças, desvios e incidentes

### Desenvolvedores do Modelo

- Documentar dados, premissas, metodologia e limitações
- Executar testes de desenvolvimento e de qualidade
- Corrigir achados de validação

### Validação Independente (2ª linha)

- Realizar validação conforme o nível de risco
- Emitir parecer e registrar achados
- Acompanhar o tratamento dos achados

### Auditoria Interna (3ª linha)

- Avaliar a eficácia do processo de gerenciamento de risco de modelo

### Comitê de Governança de IA

- Aprovar a política e os modelos de risco alto ou crítico
- Deliberar sobre exceções e achados críticos

## Conteúdo da pasta

- politica-risco-de-modelo.md
- criterios-classificacao-risco-modelo.md
- matriz-validacao-modelos.md
- checklist-validacao-independente.md
- registro-validacoes-e-achados.md

## Evidências

- Inventário de modelos com classificação de risco
- Documentação de desenvolvimento e relatórios de validação
- Aprovações e pareceres
- Relatórios de monitoramento e outcomes analysis
- Registro de achados e planos de ação

## Referências

- SR 11-7 / OCC 2011-12: Supervisory Guidance on Model Risk Management (2011)
- PRA SS1/23: Model risk management principles for banks (2023)
- NIST AI 100-1: AI Risk Management Framework 1.0 (funções Map, Measure e Manage)
- ISO/IEC 42001:2023: Sistema de gestão de inteligência artificial
- ISO/IEC 23894:2023: Gestão de riscos de IA
- ISO/IEC TR 24029-1: Avaliação da robustez de redes neurais
- Regulamento (UE) 2024/1689 (EU AI Act), Arts. 9, 10 e 15
- Resolução CMN nº 4.557/2017 (gerenciamento de riscos, para instituições financeiras)
