# EcoLar — consumo inteligente

Projeto acadêmico de Desenvolvimento Front-End sobre consumo doméstico consciente de água e energia. O site combina orientações educativas, estimativas declaradamente simuladas e uma residência interativa.

## Equipe

- Abner da Silva Santos
- Kaique Rocha Vieira
- Murilo Cavalcante Rapozo da Silva
- Samuel da Silva Lima

O histórico disponível registra desenvolvimento em equipe, mas não permite atribuir com segurança cada página a uma pessoa.

## Executar localmente

Requer apenas Python 3 para servir os arquivos estáticos:

```bash
python3 -m http.server 8000 --directory ecolar
```

Abra `http://localhost:8000/`. Também é possível abrir `ecolar/index.html` diretamente, embora alguns navegadores restrinjam recursos locais.

## Páginas

O projeto mantém as páginas personalizadas solicitadas pela equipe e também inclui `projetos.html` e `galeria.html` para cobrir integralmente a atividade:

| Página | Conteúdo |
|---|---|
| [Início](./ecolar/index.html) | Painel e resumo ilustrativo do consumo |
| [Sobre](./ecolar/sobre.html) | Proposta, missão, visão e valores |
| [Minha casa](./ecolar/casa.html) | Residência interativa e cadastro temporário de cômodos/equipamentos |
| [Equipamentos](./ecolar/equipamentos.html) | Catálogo e filtros |
| [Projetos](./ecolar/projetos.html) | Ações educativas propostas, não programas já executados |
| [Consumo e impacto](./ecolar/impacto.html) | Estimativas, tabela e simulador de tarifas |
| [Acessibilidade](./ecolar/acessibilidade.html) | Recursos, práticas e controles de leitura |
| [Galeria](./ecolar/galeria.html) | Protótipos da interface com legendas e créditos |
| [Mídia educativa](./ecolar/midia.html) | Vídeo e áudio originais, transcrições e vídeos incorporados |
| [Notícias e dicas](./ecolar/noticias.html) | Recomendações e referências |
| [Contato e equipe](./ecolar/contato.html) | Integrantes e formulário demonstrativo validado |
| [Orçamento e hospedagem](./ecolar/orcamento_hospedagem.html) | Comparação de plataformas e domínios |

## Tecnologias

- HTML5, CSS3 e JavaScript sem framework de aplicação.
- Bootstrap 5.3 para layout e navegação responsiva.
- Vídeos do YouTube incorporados; mídia autoral local na página educativa.
- Recursos externos (Bootstrap e Google Fonts) requerem conexão com a internet.

## Publicação

A equipe informa que a publicação está no Railway, conforme requisito da atividade. O endereço público HTTPS e o plano contratado não estão registrados nesta cópia do repositório; confira-os no painel antes de compartilhar o link.

- Repositório: <https://github.com/DevKaique-1/Ecolar_Projeto_html>
- Produção: Railway (URL pública a confirmar no painel da equipe).

## Limites importantes

- Os indicadores, tarifas de exemplo e consumos são simulações educativas, não medições de uma residência.
- Os dados inseridos na casa interativa existem apenas durante a sessão no navegador.
- O formulário de contato valida os campos, mas não envia nem armazena mensagens.
- O EcoLar não é afiliado nem certificado pela ONU; referências aos ODS são temáticas.

## Documentação da entrega

Consulte [docs/README.md](./docs/README.md) para o escopo, diário de bordo, orçamento, testes e reavaliação. A apresentação está em [PPTX](./docs/apresentacao-ecolar.pptx) e [PDF](./docs/apresentacao-ecolar.pdf); o código compactado está em [ecolar-codigo-fonte.zip](./docs/ecolar-codigo-fonte.zip) e a captura da Home em [home-mvp.png](./docs/img/home-mvp.png). A nota é formativa: a URL Railway e os dados oficiais da A06 ainda precisam ser confirmados.
