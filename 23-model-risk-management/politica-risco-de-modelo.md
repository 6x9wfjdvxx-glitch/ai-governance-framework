# Política de Gerenciamento de Risco de Modelo

## 1. Finalidade

Definir os requisitos obrigatórios para o gerenciamento do risco de modelo ao longo de todo o ciclo de vida de modelos de IA e Machine Learning.

## 2. Aplicabilidade

Todos os modelos em uso, em desenvolvimento ou em aquisição, internos ou de terceiros, que apoiem decisões de negócio, operacionais, regulatórias ou que afetem pessoas.

## 3. Diretrizes

1. Todo modelo deve constar no inventário de IA (pasta 04) com proprietário, finalidade, versão, dados utilizados e nível de risco.
2. Todo modelo deve ser classificado conforme criterios-classificacao-risco-modelo.md antes da implantação.
3. A intensidade da validação e do monitoramento é proporcional ao nível de risco do modelo.
4. Nenhum modelo de risco médio, alto ou crítico entra em produção sem validação independente e aprovação formal.
5. A validação deve ser realizada por pessoas independentes da equipe de desenvolvimento e sem conflito de interesse.
6. A documentação deve permitir que um terceiro qualificado compreenda e reproduza o modelo: dados, premissas, metodologia, desempenho e limitações.
7. Os limites de uso e as limitações conhecidas devem ser comunicados aos usuários do modelo.
8. Modelos de terceiros devem ter evidências de validação do fornecedor, direitos contratuais de auditoria e testes compensatórios internos quando houver opacidade.
9. O desempenho, a estabilidade e a deriva (data drift e concept drift) devem ser monitorados com métricas e limiares definidos.
10. A revalidação ocorre periodicamente, conforme o nível de risco, e por gatilho: mudança de dados, de uso, de população, de metodologia ou degradação de desempenho.
11. Mudanças materiais exigem nova validação antes da implantação.
12. Achados de validação devem ter responsável, prazo e plano de ação, com acompanhamento até o encerramento.
13. Modelos sem validação válida ou com achados críticos vencidos devem ser restringidos ou suspensos.
14. Modelos aposentados devem ser descomissionados com preservação de documentação e registros conforme a política de retenção.

## 4. Periodicidade mínima de revalidação

| Nível de risco | Revalidação completa | Monitoramento |
|---|---|---|
| Crítico | A cada 12 meses | Contínuo, com alertas |
| Alto | A cada 12 a 18 meses | Mensal |
| Médio | A cada 24 meses | Trimestral |
| Baixo | A cada 36 meses ou por gatilho | Semestral |

## 5. Exceções

Exceções devem ser justificadas, temporárias, aprovadas pelo Comitê de Governança de IA e registradas em registro-validacoes-e-achados.md.

## 6. Revisão

Esta política é revisada no mínimo anualmente ou após mudança regulatória, incidente relevante ou falha de modelo.

## Referências

- SR 11-7 / OCC 2011-12, seções de desenvolvimento, validação e governança
- PRA SS1/23, princípios 1 a 5
- ISO/IEC 42001:2023, cláusulas 6 (Planejamento) e 8 (Operação)
- NIST AI 100-1, funções Govern e Manage
- EU AI Act, Art. 9 (sistema de gestão de riscos)
