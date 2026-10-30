# Calendário e Fluxo de Coleta de Evidências

## 1. Fluxo de coleta

| Etapa | Descrição | Responsável | Prazo de referência |
|---|---|---|---|
| 1. Planejar | Gerar a agenda de coleta a partir do catálogo e notificar os proprietários | Proprietário da Central | Início do período |
| 2. Coletar | Gerar ou extrair a evidência na fonte primária | Proprietário do controle | Até 5 dias úteis após o fechamento do período |
| 3. Preparar | Minimizar, anonimizar ou mascarar dados sensíveis; aplicar convenção de nomes | Proprietário do controle | Até 2 dias úteis |
| 4. Validar | Verificar qualidade conforme os atributos da política | Proprietário da Central | Até 5 dias úteis |
| 5. Atestar | Atestar veracidade e completude | Proprietário do controle | Até 2 dias úteis |
| 6. Publicar | Publicar na Central com versão, hash e metadados | Proprietário da Central | Até 2 dias úteis |
| 7. Monitorar | Acompanhar vencimento, cobertura e lacunas | Proprietário da Central | Contínuo |
| 8. Arquivar | Arquivar conforme retenção e descartar quando permitido | Proprietário da Central | Conforme retenção |

## 2. Calendário anual de referência

| Período | Atividades de evidência |
|---|---|
| Mensal | Inventário de IA, monitoramento e deriva de modelos, supervisão humana, incidentes |
| Trimestral | KPIs e OKRs, treinamento, atestações dos proprietários, revisão do catálogo |
| Semestral | Avaliação de fornecedores críticos, revisão do mapeamento, relatório de cobertura ao Comitê |
| Anual | Políticas, programa de auditoria interna, análise crítica pela direção, avaliação de maturidade, revisão desta Central |
| Por evento | Novos sistemas de IA, mudanças materiais, incidentes, solicitações de auditores e reguladores |

## 3. Níveis de automação

| Nível | Descrição | Exemplo |
|---|---|---|
| 1. Manual | Coleta e envio por pessoas | Envio de relatórios em planilha |
| 2. Semiautomatizado | Extração automática, com revisão e envio manual | Exportação programada do inventário |
| 3. Contínuo | Coleta automática da fonte primária, com alertas de desvio | Integração de logs, plataformas de ML e sistema de GRC |

A meta de referência é elevar as evidências de alta frequência e alto risco ao nível 3.

## 4. Modelo de atestação do proprietário do controle

Declaro que as evidências enviadas para o período ____________________:

- Foram geradas pela operação regular do processo ou controle
- Estão completas e correspondem aos fatos e à fonte
- Não foram alteradas retroativamente
- Tiveram dados pessoais e confidenciais tratados conforme a política

**Evidências atestadas (IDs):** ____________________
**Exceções ou ressalvas:** ____________________

**Nome:** ____________________
**Cargo:** ____________________
**Data:** ____/____/______
**Assinatura:** ____________________

## 5. Atendimento a solicitações de auditores, reguladores e clientes

| Etapa | Ação | Prazo de referência |
|---|---|---|
| Registro | Registrar a solicitação com solicitante, escopo e prazo | Mesmo dia |
| Triagem | Identificar as evidências no catálogo e os proprietários | 1 dia útil |
| Revisão | Verificar sensibilidade e necessidade; aplicar minimização | 2 dias úteis |
| Aprovação | Aprovação do Proprietário da Central e, quando aplicável, de Jurídico e Privacidade | 1 dia útil |
| Entrega | Envio por canal seguro, com acesso temporário e registro | Conforme prazo solicitado |
| Encerramento | Registrar o que foi entregue e eventuais pendências | Em até 2 dias úteis |

## 6. Indicadores de desempenho da coleta

| Indicador | Fórmula | Meta de referência |
|---|---|---|
| Cobertura de evidências | Evidências vigentes / evidências catalogadas | 95% ou mais |
| Evidências vencidas | Quantidade de evidências além da validade | 0 para controles críticos |
| Pontualidade da coleta | Evidências entregues no prazo / evidências planejadas | 90% ou mais |
| Tempo médio de atendimento a solicitações | Dias entre solicitação e entrega | Até 5 dias úteis |
| Taxa de reaproveitamento | Evidências usadas em mais de um framework / total | Acompanhar a tendência |

## Referências

- ISO/IEC 42001:2023, cláusulas 7.5, 9.1 e 9.2
- ISO/IEC 27004:2016: Medição da segurança da informação
- ISO 19011:2018, seções de coleta e verificação de evidências
- Pasta 24-kpis-e-okrs-de-ia deste repositório
