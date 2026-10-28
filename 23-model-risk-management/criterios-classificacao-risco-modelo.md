# Critérios de Classificação de Risco de Modelo

## 1. Fatores de avaliação

Cada fator é pontuado de 1 (baixo) a 4 (crítico). O nível final considera a soma e a regra de elevação do item 3.

| Fator | 1 - Baixo | 2 - Médio | 3 - Alto | 4 - Crítico |
|---|---|---|---|---|
| Materialidade do impacto | Impacto operacional pequeno | Impacto financeiro ou de cliente moderado | Impacto financeiro, legal ou reputacional relevante | Impacto severo, sistêmico ou sobre direitos de pessoas |
| Uso em decisões | Apoio informativo | Recomendação com revisão humana | Decisão com supervisão limitada | Decisão automatizada sem revisão |
| Complexidade e opacidade | Modelo simples e interpretável | Moderadamente complexo | Complexo, interpretabilidade limitada | Caixa-preta ou de terceiro sem transparência |
| Dados sensíveis | Dados públicos | Dados internos | Dados pessoais | Dados pessoais sensíveis ou regulados |
| Exposição regulatória | Nenhuma | Regulação indireta | Regulação aplicável | Alto risco sob regulação específica |
| Escala de uso | Poucos usuários ou casos | Uso departamental | Uso corporativo | Uso em escala massiva ou externa |

## 2. Nível de risco

| Pontuação total | Nível |
|---|---|
| 6 a 10 | Baixo |
| 11 a 15 | Médio |
| 16 a 20 | Alto |
| 21 a 24 | Crítico |

## 3. Regras de elevação

O nível é elevado automaticamente, independentemente da pontuação, quando:

- O modelo toma decisões automatizadas com efeito jurídico ou significativo sobre pessoas
- O modelo se enquadra em categoria de alto risco sob o EU AI Act
- O modelo é de terceiro e não permite auditoria nem acesso a evidências de validação
- Houver histórico de falha, incidente ou achado crítico em aberto

## 4. Requisitos por nível

| Requisito | Baixo | Médio | Alto | Crítico |
|---|---|---|---|---|
| Registro no inventário | Sim | Sim | Sim | Sim |
| Documentação do modelo | Resumida | Completa | Completa e revisada | Completa e revisada |
| Validação independente | Revisão simplificada | Sim | Sim, aprofundada | Sim, aprofundada com testes adversariais |
| Aprovação | Proprietário | Gestor da área | Comitê de Governança de IA | Comitê de Governança de IA e alta direção |
| Supervisão humana (pasta 21) | Recomendada | Definida | Obrigatória | Obrigatória com critérios de intervenção |
| Monitoramento | Semestral | Trimestral | Mensal | Contínuo com alertas |

## 5. Reclassificação

A classificação é revisada na revalidação e sempre que houver mudança de uso, de população, de dados ou de impacto.

## Referências

- SR 11-7 / OCC 2011-12 (materialidade e complexidade do modelo)
- PRA SS1/23, princípio 1 (identificação e classificação de modelos)
- NIST AI 100-1, função Map
- EU AI Act, Art. 6 e Anexo III (sistemas de alto risco)
- ISO/IEC 23894:2023
