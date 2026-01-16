# Game Monetization HTML Template
`este projeto, em sua versão original, utilisa UTF-8 e esta em pt-BR`

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

#### Redes Sociais
[discord (para contato)](https://discord.com/app)
[instagram]()
[youtube](https://youtube.com/)

## Licensa de uso: Ao usar este progama, automaticamente estara concordando com a licensa abaixo

### Permissões
Você **PODE**:
- Usar este projeto para qualquer finalidade, pessoal ou pública
- Modificar o código livremente
- Redistribuir o projeto original ou modificado

### Obrigações
Você **DEVE**:
- Manter os **créditos do projeto original** em qualquer redistribuição
- Incluir um **link para o repositório oficial** do projeto
- Dar **créditos claros** ao projeto original em qualquer modificação ou derivação

### Restrições
Você **NÃO PODE**:
- Declarar este projeto como sendo de sua autoria exclusiva
- Remover ou ocultar os créditos do projeto original
- Solicitar patente, registro de propriedade intelectual ou qualquer forma de exclusividade
- Vender este projeto ou qualquer versão derivada como produto proprietário

### Observações
- O código é fornecido **“como está”**, sem garantias
- Nada do que for feito a partir deste codigo é responsabilidade do criador
- Este projeto existe para promover **código livre, open-source e acessível**
