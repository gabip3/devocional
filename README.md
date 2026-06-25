# 매일 — Protótipos de Interface

> "Todos os dias com Deus."  
> App devocional cristão minimalista em português e coreano.

---

## Arquivos

| Arquivo | Descrição |
|---|---|
| `maeil_splash.html` | Tela de abertura / onboarding |
| `maeil_hoje.html` | Tela principal — versículo do dia com áudio real e palavras clicáveis |
| `maeil_versiculos.html` | Tela de versículos — categorias e detalhe por tema |
| `maeil_share_flow.html` | Fluxo de compartilhamento — prévia do card + destinos |
| `maeil_share_cards.html` | Templates de cards por categoria (Paz, Ansiedade, Gratidão, Família, Oppa ♡) |
| `maeil_plus.html` | Tela de paywall — 매일 Plus por R$ 19,90 vitalício |

## Como visualizar

Abra qualquer arquivo `.html` diretamente no navegador — não precisa de servidor.  
Funciona melhor em Chrome ou Safari, com janela em torno de 400px de largura.

## Decisões de design

- **Tipografia coreana:** Dongle Bold (Google Fonts) — arredondada, acolhedora, bold
- **Tipografia PT:** Cormorant Garamond SemiBold Itálico (versículos) + Noto Sans KR (UI)
- **Ícones:** estilo Feather — outline, traço 1.6px, sem preenchimento
- **Paleta base:** papel/tinta — `#F8F4EE` (fundo), `#2E2519` (tinta), `#C9B99A` (dourado)
- **Cores por categoria:** verde sálvia (Paz), azul poeira (Ansiedade), âmbar (Gratidão), terracota (Família), rosa (Oppa ♡)
- **Sem romanização** em nenhuma tela
- **Bíblia:** Almeida Revista e Corrigida (domínio público) — canon protestante
- **Áudio:** Web Speech API (`speechSynthesis`, `lang: ko-KR`) — sem custo, offline, mesma solução do Oi Coreia
- **Preço:** R$ 19,90 vitalício (pagamento único, sem assinatura)

## Próximos passos

- [ ] Código Flutter — começar pela tela Hoje
- [ ] Revisão nativa dos 100 versículos em coreano
- [ ] Fundos dos cards de compartilhamento (desenhados pela Gabi)
- [ ] Ícone final do app (512×512px para as lojas)
- [ ] Texto da loja (Google Play + App Store)
- [ ] Política de privacidade
- [ ] Publicação Google Play + App Store (via Codemagic)

---

*Projeto em desenvolvimento — 2026*
