# Design System Copiloto

Este é o **Padrão e Design System do Piloto Automático**. Construa soluções dentro da identidade da empresa.

Estética **Lime & Slate**: lime vibrante (`#C6F24F`) sobre off-white suave, contornos em slate quase-preto, cantos arredondados tipo bloco e o par tipográfico **Outfit** (display) + **Inter** (texto/dados).

## Página

[`index.html`](index.html) — página única e autossuficiente com a biblioteca completa: fundações (tokens, cores, tipografia, espaçamento, raios, sombras), componentes base, blocos de aplicação e todos os componentes (accordion, cards, modal, dropdown, tabs, toasts, paginação, formulários, tabelas e mais). É só abrir no navegador.

## Exemplos

Telas reais construídas 100% dentro do Design System — totalmente **responsivas** (mobile, tablet, desktop) e com **tema claro/escuro**:

- [`exemplos/copiloto-landing.html`](exemplos/copiloto-landing.html) — landing page da suíte (menu mobile, grids que empilham, hero responsivo).
- [`exemplos/leads-kanban.html`](exemplos/leads-kanban.html) — CRM de leads em Kanban, com sidebar drawer no mobile e gaveta de configuração de etapa (campos, follow-up, automações, Copiloto IA).
- [`exemplos/lead-conversa.html`](exemplos/lead-conversa.html) — inbox/conversa do lead (chat estilo WhatsApp, funil, painel de dados com auto-save; painéis viram drawers no mobile/tablet).

## Recursos

- **Tokens** como variáveis CSS (`:root`) — cores, tipografia, espaçamento, raios, sombras e motion.
- **Tema claro e escuro** — botão de alternância no topo da sidebar (com persistência).
- **Navegação lateral** com scroll suave e destaque automático da seção (scrollspy); vira drawer no mobile.
- **Modelo de interação consistente** — hover sobe levemente, clique afunda.

_Powered by Piloto Automático._
