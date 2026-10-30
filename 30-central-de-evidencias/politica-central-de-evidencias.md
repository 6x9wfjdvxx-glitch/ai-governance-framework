# Política da Central de Evidências

## 1. Finalidade

Definir as regras para criação, coleta, validação, proteção, retenção e uso das evidências de governança de IA, de modo a demonstrar conformidade de forma consistente, reutilizável e auditável.

## 2. Aplicabilidade

Todas as áreas, processos, sistemas de IA, fornecedores e colaboradores abrangidos pelo programa de governança de IA.

## 3. Diretrizes

1. Todo requisito relevante dos frameworks adotados deve estar associado a ao menos uma evidência no catálogo-de-evidencias.md.
2. Cada evidência deve ter identificador único, proprietário, frequência de atualização, classificação da informação e prazo de retenção.
3. O mapeamento entre evidências e frameworks deve ser mantido em mapeamento-evidencias-por-framework.md, evitando coletas duplicadas.
4. As evidências devem ser geradas pela operação regular, com data, autoria e aprovação identificáveis.
5. A coleta deve seguir o calendário e o fluxo definidos em calendario-e-fluxo-de-coleta.md.
6. O proprietário do controle deve atestar a veracidade e a completude das evidências enviadas.
7. Toda evidência passa por verificação de qualidade antes de ser publicada na Central.
8. O armazenamento deve ter controle de acesso por perfil, registro de acessos, histórico de versões e proteção contra alteração indevida.
9. A integridade deve ser demonstrável, por exemplo, por cálculo de hash, armazenamento imutável ou assinatura.
10. Evidências com dados pessoais ou confidenciais devem ser minimizadas, anonimizadas ou mascaradas antes de qualquer compartilhamento externo.
11. O compartilhamento com auditores, reguladores e clientes exige solicitação registrada, perímetro definido e canal seguro.
12. A retenção respeita o maior prazo exigido pelos frameworks e pela legislação, observado o princípio da necessidade.
13. É vedado criar, alterar retroativamente ou omitir evidências; correções geram nova versão, com justificativa.
14. Evidências vencidas, ausentes ou sem proprietário são lacunas e devem ter plano de ação com prazo.
15. A cobertura e a qualidade das evidências são monitoradas e reportadas ao Comitê de Governança de IA.
16. Sempre que possível, a coleta deve ser automatizada a partir das fontes primárias (inventário, plataformas de ML, logs, sistemas de GRC).

## 4. Níveis de qualidade da evidência

| Atributo | Pergunta de verificação |
|---|---|
| Completa | Cobre todo o período e o escopo exigidos? |
| Precisa | Os dados correspondem aos fatos e à fonte? |
| Atual | Está dentro da validade definida? |
| Autêntica | Autoria, data e aprovação são identificáveis? |
| Rastreável | Liga requisito, evidência, responsável e fonte? |
| Protegida | Tem classificação e acesso adequados? |

## 5. Retenção de referência

| Tipo de evidência | Retenção de referência |
|---|---|
| Documentação técnica de sistemas de IA de alto risco | 10 anos após a colocação no mercado ou em serviço (EU AI Act, Art. 18) |
| Logs gerados automaticamente por sistemas de alto risco | No mínimo 6 meses, ou mais conforme a finalidade e a legislação (EU AI Act, Art. 19) |
| Registros do AIMS e relatórios de auditoria | Ciclo de certificação vigente mais o ciclo anterior |
| Evidências com dados pessoais | Pelo menor prazo necessário, conforme LGPD e política de retenção |

Os prazos devem ser confirmados com Jurídico e Privacidade.

## 6. Exceções

Exceções devem ser justificadas, aprovadas pelo Comitê de Governança de IA e registradas em registro-de-evidencias-e-qualidade.md.

## 7. Revisão

Esta política é revisada no mínimo anualmente ou após mudança em framework, regulação ou arquitetura da Central.

## Referências

- ISO/IEC 42001:2023, cláusula 7.5 (controle de informação documentada)
- EU AI Act, Arts. 12, 18 e 19 (registros, retenção da documentação e dos logs)
- LGPD, Arts. 6º (necessidade, segurança e responsabilização), 15 e 16 (término do tratamento) e 46
- ISO/IEC 27001:2022, A.5.33 (proteção de registros) e A.8.15 (registro de eventos)
- ISO 19011:2018, seção sobre evidência de auditoria
