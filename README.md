# Modelo 01 — Comece seu próprio negócio · On Track LP

Landing page modelo da **On Track** (HTML, CSS e JS puros, sem build), pronta para ser personalizada para um cliente.

- **Estilo:** Lilás claro, roxo e laranja; balões de conversa, letra de mão e caderno.
- **Ideal para:** Quem vende um novo negócio, franquia, programa de parceiros ou oportunidade, com simulador de margem.
- **Seções:** Topo com vídeo estilo story · Sequência Escolha→Divulgue→Atenda→Aprenda→Repita · Canais (Instagram, WhatsApp, marketplaces) · Simulador de margem com aviso legal · Checklist + app · Transparência · Instagram/WhatsApp · Dúvidas
- **Demonstração:** https://devagenciaontrack-sys.github.io/lp-modelo-01-ontrack/

## Como personalizar (o que o cliente precisa enviar)

| Item | Onde trocar |
|---|---|
| Nome da marca | Procure por `Sua Marca` / `SUA MARCA` / `sua<b>marca</b>` em todos os arquivos |
| Logo | Topo e rodapé (classe `logo`) — trocar o texto pelo `<img>` do logo |
| Link principal (app, site, loja ou grupo) | Links `href="#"` dos botões principais |
| WhatsApp | `wa.me/5500000000000` → número com DDI e DDD |
| Telefones | `(00) 00000-0000`, `0800 000 0000` e `tel:+5500000000000` |
| Instagram | Comentários `[INSERIR_INSTAGRAM]` |
| Vídeo do YouTube | `data-video-id=""` → ID do vídeo (o que vem depois de `watch?v=` ou `/shorts/`) |
| Imagens | Pasta `assets/`: video-capa.svg, tela-app.svg |
| Empresa | `RAZÃO SOCIAL DA EMPRESA LTDA` e `CNPJ 00.000.000/0000-00` no rodapé e nas páginas legais |
| Textos | Títulos, benefícios e respostas das dúvidas — ajustar ao negócio do cliente |
| Cores | Variáveis no topo do `style.css` (`:root`) |
| Rastreamento | Eventos `lp_*` já enviados ao dataLayer/gtag/Meta Pixel; colar as tags do cliente no `<head>` |

As páginas `politica-de-privacidade.html` e `termos-de-uso.html` também usam os dados da empresa.

## Briefing para o cliente
PDF com tudo o que precisamos do cliente para montar o site: [baixar o briefing](Briefing-Modelo-01-Seu-proprio-negocio.pdf?raw=1)
