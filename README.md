# Game Monetization HTML Template

Este projeto é um **molde HTML único** para publicar demos de jogos (ex: TurboWarp)
com anúncios e botões configuráveis sem alterar código.

## Estrutura
- `index.html` → único arquivo com HTML + CSS + JS
- `jogo.html` → jogo exportado
- `config.xlsx` → configura layout, anúncios e botões

## Configuração do Excel

### Linha 0
| Coluna | Função |
|------|-------|
| A | Tamanho do jogo (alturaXlargura) |
| B | Título |
| C | Texto expansível |
| D | HTML do anúncio |
| E | Tamanho do iframe do anúncio |

### Linha 1+
| Coluna | Função |
|------|-------|
| A | Ícone do botão |
| B | URL |
| C | Texto do botão |

## Como usar
1. Substitua `jogo.html`
2. Edite `config.xlsx`
3. Publique tudo (Vercel, GitHub Pages, etc)

Nenhuma modificação de código necessária.

## Observações
- Compatível com jogos exportados pelo TurboWarp Packager
- Suporta Adsense e outros sistemas de ads via iframe
- Projeto gerado com auxílio de Inteligência Artificial

Use com responsabilidade. Ou não, o problema não é meu.
### viva o codigo livre, viva o open-source

## Licensa de uso: Ao usar este progama, automaticamente estara concordando com a licensa abaixo
`a definir`
