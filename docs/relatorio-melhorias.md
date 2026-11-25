# Relatório de melhorias da revisão A06

O repositório não contém o formulário de avaliação nem a lista de comentários do MVP. A tabela abaixo registra problemas observáveis durante a revisão do código e da rubrica; ela não afirma que sejam os apontamentos formais do professor.

| Antes observado | Melhoria aplicada | Evidência |
|---|---|---|
| Faltavam as páginas previstas na rubrica para projetos e galeria. | Criadas as páginas com propostas educativas e imagens legendadas/creditadas, preservando `casa.html` e `equipamentos.html`. | `ecolar/projetos.html`, `ecolar/galeria.html`. |
| A página educativa tinha iframes, mas nenhum `<video controls>` ou `<audio controls>`. | Incluídos vídeo autoral local, áudio narrado, legenda WebVTT e transcrições. | `ecolar/media/`, `ecolar/midia.html`. |
| Texto branco sobre os verdes claros usados em botões e na casa tinha contraste insuficiente. | Escurecidos os tons da identidade e os estados de foco; adicionado foco forte para controles e suporte a movimento reduzido. | `ecolar/css/style.css`; relatório de contraste em `testes.md`. |
| Dois fundos verdes e etiquetas ainda não atingiam o limiar AA de texto normal. | Escurecidos os gradientes da Home/Sobre e o texto das etiquetas; os pares testados ficaram acima de 4,5:1. | `ecolar/css/style.css`, `testes.md`. |
| A Home apresentava pequeno transbordamento horizontal em viewports móveis, tablet e desktop. | Ajustados os paddings do painel e repetidos os testes em 375, 768 e 1440 px. | `ecolar/css/style.css`, `testes.md`. |
| O atalho “pular para conteúdo” estava disponível somente na página de acessibilidade. | Disponibilizado em todas as páginas, com destino `main` válido. | Todos os arquivos `ecolar/*.html`. |
| A página de hospedagem era apenas um placeholder. | Adicionadas comparações de três plataformas e três opções de domínio, com ressalvas, preços observados e fontes oficiais. | `ecolar/orcamento_hospedagem.html`, `orcamento-hospedagem.md`. |
| Um valor da Home (R$ 164,80) divergia do cálculo inicial de tarifas em Impacto (R$ 164,85). | Corrigido para R$ 164,85, que corresponde a 186 × R$ 0,75 + 8,45 m³ × R$ 3,00. | `ecolar/index.html`, `ecolar/impacto.html`. |
| A variação de 30% na Home podia parecer medição real. | Passou a ser identificada como exemplo simulado, com aviso geral sobre os indicadores. | `ecolar/index.html`. |
| A grade da casa podia crescer para trás do telhado quando novos cômodos eram adicionados. | Reservado espaço abaixo do telhado e habilitada rolagem da grade quando necessário. | `ecolar/css/style.css`; ver também teste da interação em `testes.md`. |
| A página de impacto não explicava a origem dos números usados. | Acrescentados créditos e links de referência, deixando claro que os valores numéricos são exemplos internos. | `ecolar/impacto.html`, `ecolar/equipamentos.html`. |

## Pendências externas que não podem ser comprovadas pelo código

- Copiar a URL HTTPS pública e o plano do painel Railway.
- Anexar o feedback formal recebido na A05 e completar a tabela com os apontamentos reais.
- Registrar a divisão verdadeira de tarefas, cronograma e participação oral.
- Realizar a demonstração ao vivo e responder às perguntas da banca.
- Conferir a nota com o PDF oficial da A06; esse arquivo não está nesta cópia do repositório.
