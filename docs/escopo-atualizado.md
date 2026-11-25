# Escopo atualizado — EcoLar

**Data desta atualização:** 24/11/2026  
**Disciplina:** Desenvolvimento Front-End — Fatec SCS  
**Professor indicado nos documentos:** Paulo Fratta  
**Equipe:** Abner da Silva Santos, Kaique Rocha Vieira, Murilo Cavalcante Rapozo da Silva e Samuel da Silva Lima.

## Objetivo geral

Apresentar uma experiência web acessível e responsiva que ajude pessoas a compreender o consumo doméstico de água e energia por meio de conteúdo educativo, referências, tabelas e estimativas explicitamente simuladas.

## Público e necessidade

O público inclui famílias, estudantes e pessoas interessadas em acompanhar hábitos e custos domésticos. A interface deve ser utilizável por pessoas com deficiência, inclusive com teclado, leitor de tela, ampliação de texto e alternativas textuais para dados visuais.

## Escopo funcional atual

1. Doze páginas interligadas por navegação compartilhada.
2. Casa interativa com visualização de cômodos, consulta a equipamentos e formulário simples para adicionar cômodos/equipamentos durante a sessão.
3. Catálogo filtrável de equipamentos domésticos.
4. Indicadores ilustrativos, tabela e calculadora de tarifas de referência.
5. Formulário de contato com validação HTML5, sem transmissão ou armazenamento.
6. Conteúdo educativo, projetos sugeridos, notícias/dicas, galeria e mídia.
7. Áudio e vídeo locais com transcrição/legendas, além de iframes externos.
8. Link para pular ao conteúdo, navegação por teclado, foco visível, controles de leitura e alto contraste na página de acessibilidade.

## Alterações em relação à lista A06

A atividade lista `projetos.html` e `galeria.html`; a equipe havia pedido que o catálogo e a casa interativa fossem implementados como `equipamentos.html` e `casa.html`. Para satisfazer os dois requisitos sem apagar as páginas personalizadas, foram mantidos os quatro endereços. O resultado tem 12 páginas, com links em todas elas.

## Escopo não funcional e critérios de aceitação

- Semântica HTML, idioma `pt-BR`, título e descrição em cada página.
- Layout responsivo em celular, tablet e desktop.
- Alternativas textuais e legendas para conteúdo visual/audiovisual.
- Citações de fontes externas e identificação explícita de dados simulados.
- Links internos válidos, navegação comum e formulário testado com entradas inválidas e válidas.
- Publicação no Railway conforme informação da equipe; URL de produção pendente de ser copiada do painel para a documentação pública.

## Limitações e riscos

- Não há backend, autenticação, transmissão de mensagens nem persistência dos cômodos cadastrados.
- As estimativas não são medições, parecer de engenharia ou conta oficial.
- Iframes do YouTube e bibliotecas CDN dependem de terceiros e de acesso à internet.
- O plano Railway, a URL publicada, os registros do feedback da A05 e a divisão individual de tarefas não foram fornecidos pelos artefatos disponíveis.
- Os recursos e preços de hospedagem/domínio podem mudar.

## Fontes dos registros

Este resumo foi atualizado a partir do documento `ESCOPO DO PROJETO — ECOLAR.docx`, das instruções da Atividade A06, do código e do histórico Git local. Não altera nem atribui retroativamente aprovações, assinaturas, RA ou responsabilidades individuais que não estejam documentadas.
