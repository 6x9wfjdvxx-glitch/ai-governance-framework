# Critérios de Uso Aceitável de LLM e IA Generativa

## 1. Uso permitido

- Rascunho e revisão de textos sem dados sensíveis
- Resumo de documentos públicos ou classificados como uso geral
- Apoio à codificação com revisão humana e sem código proprietário em ferramentas não aprovadas
- Pesquisa exploratória com validação das fontes
- Casos de uso aprovados e registrados no inventário

## 2. Uso condicionado (exige aprovação prévia)

- Tratamento de dados pessoais ou confidenciais em ferramentas aprovadas
- Integração de LLM a sistemas de produção
- Agentes com acesso a ferramentas, e-mail, arquivos ou APIs
- Conteúdo gerado por IA publicado externamente
- Fine-tuning ou RAG com bases internas

## 3. Uso proibido

- Inserir credenciais, chaves, segredos comerciais ou dados regulados em ferramentas não aprovadas
- Decisões automatizadas sobre pessoas sem supervisão humana e base legal
- Gerar conteúdo falso, difamatório ou que viole direitos de terceiros
- Contornar controles de segurança do modelo ou da organização
- Utilizar contas pessoais para tratar informações corporativas

## 4. Classificação de dados e destino permitido

| Classificação | Ferramenta pública | Ferramenta corporativa aprovada | Modelo interno |
|---|---|---|---|
| Pública | Permitido | Permitido | Permitido |
| Interna | Proibido | Permitido | Permitido |
| Confidencial | Proibido | Condicionado | Permitido |
| Pessoal ou sensível | Proibido | Condicionado (RIPD e base legal) | Condicionado |
| Segredos e credenciais | Proibido | Proibido | Proibido |

## 5. Deveres do usuário

- Validar os resultados antes de utilizá-los
- Não atribuir ao modelo a responsabilidade pela decisão
- Reportar comportamentos anômalos, vazamentos e respostas inadequadas
- Declarar o uso de IA quando exigido por política, contrato ou regulamento

## Referências

- ISO/IEC 42001:2023, Anexo A (controles de uso de sistemas de IA)
- ISO/IEC 27001:2022, Anexo A (classificação da informação e uso aceitável)
- NIST AI 600-1
- LGPD, Arts. 6º e 7º
