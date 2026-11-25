# Testes e evidências

Registro das verificações executadas localmente em 25/11/2026. A publicação Railway, sua URL pública e eventuais condições de produção não foram verificadas.

## Validação estática

| Verificação | Resultado |
|---|---|
| Nu HTML Checker 26.11.20 nas 12 páginas `ecolar/*.html` | Sem erros, avisos ou informações reportados. |
| `git diff --check` | Sem erros de whitespace. |
| Respostas das páginas no servidor local | As 12 páginas responderam com HTTP 200. |

## Navegação e responsividade

As páginas foram abertas em 375, 768 e 1440 px (36 verificações de rota/viewport). Todas apresentaram `<main>`, um título `<h1>`, exatamente um link de navegação marcado `aria-current="page"` e nenhuma rolagem horizontal detectada. As doze barras de navegação continham os mesmos destinos locais.

Com os recursos Bootstrap carregados, o botão do menu expandido exibiu o menu e atualizou `aria-expanded`.

## Interações

| Área | Cenário | Resultado |
|---|---|---|
| Minha casa | Adicionar um cômodo e um equipamento à cozinha | Ambos apareceram na interface. Os dados permanecem apenas na sessão da página. |
| Equipamentos | Filtrar pelo cômodo “Banheiro” | Três cartões exibidos e botão com `aria-pressed="true"`. |
| Acessibilidade | Aumentar texto, ativar alto contraste e restaurar | Escala foi a 110%; os dois modos foram ativados e restaurados. |
| Impacto | Recalcular com R$ 1,00/kWh e R$ 4,00/m³ | Total exibido: R$ 219,80, conforme os consumos ilustrativos da página. |
| Contato | Tentar validar vazio e depois preencher os campos obrigatórios | O formulário vazio foi inválido; preenchido, exibiu confirmação de demonstração sem enviar ou guardar os dados. |
| JavaScript | Navegar pelas páginas e executar os cenários acima | Nenhuma exceção JavaScript detectada. |

## Contraste

Foi feita uma verificação automatizada dos pares de texto/fundo calculados nos estados iniciais das páginas e conferência das cores de destaque. A correção de contraste dos fundos verdes foi mantida; o texto das etiquetas gerais também foi escurecido.

| Par de cores | Contraste |
|---|---:|
| Branco sobre `#28753f` | 5,67:1 |
| Branco sobre `#286b3d` | 6,44:1 |
| `#286b3d` sobre `#edf7ef` | 5,87:1 |
| `#4c6386` sobre `#edf3fa` | 5,47:1 |
| `#66611a` sobre `#f8f6d9` | 5,83:1 |

Os valores atendem ao mínimo WCAG AA para texto normal nesses pares. A leitura automatizada não substitui uma auditoria completa de todas as combinações, estados de foco/hover, conteúdo externo ou testes com tecnologias assistivas.

## Limites da evidência

- Iframes, fontes e folhas de estilo externas dependem de terceiros e de conexão à internet.
- Os formulários são demonstrações front-end; não existe backend nem envio de mensagens.
- A URL HTTPS e a configuração de produção precisam ser confirmadas no painel Railway.
- A avaliação formal, feedback da A05, divisão real de tarefas e apresentação oral dependem da equipe e do professor.
