# Documentação do EcoLar

## Objetivo e escopo

O EcoLar é uma experiência acadêmica educativa para ajudar a compreender o consumo residencial de água e energia. A equipe pediu versões próprias da casa interativa e do catálogo de equipamentos; também foram mantidas as páginas de projetos e galeria consideradas na avaliação da atividade. Por isso, o site tem 12 páginas, sem substituir páginas rubricadas por outras.

| Página | Responsabilidade |
|---|---|
| `index.html` | Apresentação e resumo demonstrativo |
| `sobre.html` | Contexto, missão, visão e valores |
| `projetos.html` | Propostas educativas de sustentabilidade |
| `impacto.html` | Estimativas, tabela, tarifas e limitações |
| `acessibilidade.html` | Práticas de inclusão e controles de leitura |
| `galeria.html` | Protótipos da interface com créditos |
| `midia.html` | Mídia autoral, transcrição e iframes |
| `noticias.html` | Dicas e referências externas |
| `contato.html` | Equipe e formulário HTML5 demonstrativo |
| `orcamento_hospedagem.html` | Comparação de plataformas e domínios |
| `casa.html` | Casa interativa solicitada pela equipe |
| `equipamentos.html` | Catálogo de equipamentos solicitado pela equipe |

## Estrutura

- `../ecolar/*.html`: páginas e conteúdo.
- `../ecolar/css/style.css`: identidade visual e estilos responsivos compartilhados.
- `../ecolar/js/script.js`: arquivo reservado; as interações atuais ficam próximas ao HTML para facilitar a explicação didática.
- `../ecolar/img/`: logotipos, protótipos e poster do vídeo.
- `../ecolar/media/`: vídeo, áudio e legendas locais autorais.
- `diario-de-bordo.md`: histórico baseado no histórico Git disponível e no trabalho desta revisão.
- `escopo-atualizado.md`: diferenças documentadas em relação ao escopo.
- `orcamento-hospedagem.md`: quadro comparativo e fontes.
- `relatorio-melhorias.md`: correções feitas nesta revisão.
- `testes.md`: verificações e limites das evidências.
- `avaliacao-final.md`: reavaliação formativa, critérios e pendências.
- `apresentacao-ecolar.pptx` e `apresentacao-ecolar.pdf`: apresentação de 16 slides.
- `img/home-mvp.png`: captura real da Home para a apresentação/entrega.
- `ecolar-codigo-fonte.zip`: pacote do site e README para envio.

## Executar e testar localmente

Na raiz do repositório:

```bash
python3 -m http.server 8000 --directory ecolar
```

Abra `http://localhost:8000/`. O formulário é somente demonstrativo; o cadastro da casa não persiste após fechar ou recarregar a página.

## Publicação e equipe

A equipe informou que o projeto já está publicado no Railway. A URL HTTPS não está nos arquivos nem no histórico consultado, então não foi inventada; copie o domínio exibido no painel Railway para a versão final do README, slides e entrega no Teams. Os quatro nomes completos estão em `../ecolar/integrantes.txt`; a divisão individual de tarefas e os registros do feedback formal da A05 não constam nos artefatos disponíveis.

## Referência de avaliação

O PDF disponível nesta cópia é o da Atividade A05; o PDF e a ficha de avaliação da A06 não estão no checkout. A reavaliação em `avaliacao-final.md` é, portanto, formativa e usa os critérios verificáveis disponíveis, não reproduz pesos oficiais. Ela não substitui a confirmação do Railway, a apresentação oral ou a validação do professor.
