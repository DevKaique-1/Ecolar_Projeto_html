# Reavaliação técnica do EcoLar

**Data:** 25/11/2026  
**Resultado estimado:** **8,5/10 — avaliação formativa, não oficial**

## Base e método

O PDF da Atividade A06 e a ficha de nota não estão nesta cópia do repositório. Por isso, não é possível reproduzir com segurança os pesos usados na estimativa inicial de 2,53/10 nem afirmar que esta nota equivale à avaliação oficial da A06. A tabela abaixo usa os onze critérios de avaliação listados no PDF disponível da Atividade A05, separando hospedagem como critério próprio, e atribui pesos iguais apenas para produzir uma estimativa transparente.

| Critério | Nota estimada | Evidência e motivo para não ser máxima |
|---|---:|---|
| Estrutura e organização | 9,5/10 | Doze páginas, CSS comum, pastas de mídia e documentação; falta conferir o pacote e a versão publicados. |
| Semântica HTML5 | 9,0/10 | As 12 páginas passaram no Nu HTML Checker sem mensagens; isso não substitui uma auditoria completa de acessibilidade. |
| Validação de formulário | 8,0/10 | Validação HTML5 e resposta acessível testadas; o formulário é demonstrativo e não transmite dados. |
| Multimídia e navegação | 9,5/10 | Menu comum, links internos, vídeo e áudio locais, legendas/transcrição e iframes; recursos externos dependem da rede. |
| Acessibilidade e inclusão | 8,0/10 | Link de salto, foco, controles de texto/contraste e pares principais AA verificados; faltam testes com leitores de tela e usuários. |
| Sustentabilidade e impacto social | 9,0/10 | Conteúdo educativo e referências com estimativas explicitamente simuladas; não há medições próprias verificadas. |
| Criatividade | 9,0/10 | Casa interativa, filtros e calculadora; os dados adicionados não persistem entre sessões. |
| Documentação e orçamento | 8,5/10 | README, escopo, diário baseado em evidências, orçamento e testes; feedback formal e alguns registros da equipe faltam. |
| Clareza do escopo | 9,0/10 | Limites e páginas documentados; foram mantidas 12 páginas para atender pedidos da equipe e itens da atividade. |
| Apresentação | 8,5/10 | Deck de 16 slides com captura real, pontos positivos, dificuldades e próximos passos; apresentação oral não foi observada. |
| Publicação no Railway | 6,0/10 | A equipe informa que está publicado, mas a URL e o estado de produção não puderam ser confirmados. |

**Cálculo:** média aritmética dos 11 critérios = 8,545..., arredondada para **8,5/10**.

## Correções aplicadas nesta revisão

- Corrigidos erros de marcação e avisos encontrados no HTML: espaço entre atributos, opção inicial obrigatória, título dinâmico vazio e rótulo ARIA em elemento genérico.
- Eliminado o transbordamento horizontal da Home nos viewports testados.
- Escurecidos fundos verdes e etiquetas para atingir os pares de contraste AA verificados.
- Testados menu, cômodos/equipamentos, filtros, controles de acessibilidade, calculadora e formulário.
- Criados o relatório de testes, a captura real da Home e a apresentação em PPTX/PDF.

## O que falta para buscar a nota máxima

1. Inserir e testar a URL HTTPS real do Railway, incluindo navegação, mídias e formulários na produção.
2. Conferir os pesos e exigências exatos com o PDF oficial da A06 e atualizar esta avaliação se necessário.
3. Acrescentar o feedback verdadeiro da A05, a divisão de tarefas e o cronograma confirmado pela equipe.
4. Demonstrar os fluxos ao vivo e executar testes com teclado, leitor de tela e participantes.
5. Se o escopo evoluir para produto, decidir com a equipe se formulário e casa precisam de backend/persistência; não foram implementados porque o projeto atual é uma demonstração estática.

O resultado não garante nota do professor. A disponibilidade e avaliação da publicação, participação oral e registros reais da equipe dependem de validação externa.
