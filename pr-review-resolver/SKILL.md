# PR/MR Review Resolver Skill

## Descrição
Esta skill fornece instruções para atuar autonomamente na análise e resolução de comentários de revisão de código em Pull Requests (PRs) ou Merge Requests (MRs).

## Mandatos Principais
- **Análise Crítica:** Sempre avalie detalhadamente se o comentário de revisão é coerente, correto e aplicável ao contexto atual do código antes de fazer qualquer alteração.
- **Tratamento de Comentários Coerentes:** Se o comentário for válido e coerente, você deve implementar a correção no código, fazer o commit, enviar (push) para o repositório e responder ao comentário original explicando a alteração feita.
- **Tratamento de Comentários Incoerentes:** Se o comentário não for válido ou não fizer sentido, NÃO altere o código. Responda ao comentário de revisão argumentando de forma educada, clara e técnica o motivo da sugestão não ser coerente.

## Fluxo de Trabalho (Workflow)
1. **Extração e Organização:** Obtenha os comentários de revisão pendentes do PR/MR e organize-os como uma lista estruturada de tarefas para analisar e resolver cada um.
2. **Execução das Tarefas:** Para cada revisão de código listada:
   - **Análise:** Analise o comentário deixado pelo revisor junto com o código associado. Defina explicitamente se o review é "coerente" ou "não coerente".
   - **Caminho 1 (É Coerente):**
     1. Implemente a correção no código conforme solicitado ou sugerido.
     2. Verifique se as alterações não quebram o código existente.
     3. Faça o commit das alterações (`git commit -m "..."`).
     4. Faça o push para o repositório remoto (`git push`).
     5. Adicione uma resposta ao comentário de review na plataforma (ex: usando `gh pr review`) explicando o que foi feito.
   - **Caminho 2 (Não é Coerente):**
     1. Não faça nenhuma alteração no código relacionada a esse comentário.
     2. Adicione uma resposta ao review explicando técnica e educadamente por que a sugestão não é aplicável ou coerente.
3. **Verificação Final:** Assegure-se de que todos os comentários foram respondidos com código atualizado ou com uma justificativa.
