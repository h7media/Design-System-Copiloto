# Design Tokens — Copiloto

Tokens do Design System do Piloto Automático. Valores em hex resolvidos (prontos pra colar no Figma).

---

## 🎨 Cores

### Brand · Lime
| Token | Hex |
|---|---|
| `lime/50` | `#FBFEF2` |
| `lime/100` | `#F2FBD8` |
| `lime/200` | `#E6F8B4` |
| `lime/300` | `#D6F47E` |
| `lime/400` ⭐ | `#C6F24F` |
| `lime/500` | `#A9D13B` |
| `lime/600` | `#8AAE2D` |
| `lime/700` | `#687F22` |
| `lime/800` | `#4A5818` |
| `lime/900` | `#2C340E` |

### Neutral · Slate
| Token | Hex |
|---|---|
| `neutral/0` | `#FFFFFF` |
| `neutral/50` | `#F8F9F7` |
| `neutral/100` | `#F4F5F2` |
| `neutral/200` | `#E7E9E4` |
| `neutral/300` | `#D3D6CF` |
| `neutral/400` | `#A8ADA3` |
| `neutral/500` | `#797E76` |
| `neutral/600` | `#5B6066` |
| `neutral/700` | `#2B2F33` |
| `neutral/800` | `#1B1E22` |
| `neutral/900` | `#111317` |

### Feedback
| Token | Base | Fundo (bg) | Texto |
|---|---|---|---|
| Success | `#22C55E` | `#DCFCE7` | `#15803D` |
| Warning | `#F59E0B` | `#FEF3C7` | `#B45309` |
| Error | `#EF4444` | `#FEE2E2` | `#B91C1C` |
| Info | `#3B82F6` | `#DBEAFE` | `#1D4ED8` |

### Semânticos — tema claro
| Token | Valor |
|---|---|
| `brand` | `#C6F24F` |
| `brand/hover` | `#A9D13B` |
| `brand/active` | `#8AAE2D` |
| `on-brand` (texto sobre lime) | `#111317` |
| `bg-body` | `#F8F9F7` |
| `surface-1` (card) | `#FFFFFF` |
| `surface-2` (campo/fill) | `#F4F5F2` |
| `surface-sunken` | `#F1F3EE` |
| `text-primary` | `#111317` |
| `text-secondary` | `#5B6066` |
| `text-muted` | `#A8ADA3` |
| `border` | `#E7E9E4` |
| `border-strong` | `#D3D6CF` |

### Semânticos — tema escuro
| Token | Valor |
|---|---|
| `bg-body` | `#0F1115` |
| `surface-1` | `#181B21` |
| `surface-2` | `#22262E` |
| `surface-sunken` | `#0A0C0F` |
| `text-primary` | `#ECEEEA` |
| `text-secondary` | `#A4A8AD` |
| `text-muted` | `#6C7077` |
| `border` | `rgba(255,255,255,.09)` |
| `border-strong` | `rgba(255,255,255,.17)` |
| `success/text` | `#4ADE80` |
| `warning/text` | `#FBBF24` |
| `error/text` | `#F87171` |
| `info/text` | `#60A5FA` |

---

## ✍️ Tipografia

**Famílias:** Display = **Outfit** · Texto/dados = **Inter**
**Pesos:** Regular 400 · Medium 500 · Semibold 600 · Bold 700

| Estilo | Fonte | Tamanho | Line-height | Tracking |
|---|---|---|---|---|
| `display-2xl` | Outfit 700 | 44px | 1.05 | -3% |
| `display-xl` | Outfit 700 | 36px | 1.10 | -2.5% |
| `display-lg` | Outfit 700 | 30px | 1.15 | -2% |
| `h1` | Outfit 600 | 24px | 1.20 | -2% |
| `h2` | Outfit 600 | 20px | 1.30 | -1.5% |
| `h3` | Outfit 600 | 17px | 1.40 | -1% |
| `body-lg` | Inter 400 | 16px | 1.60 | — |
| `body` | Inter 400 | 14px | 1.60 | — |
| `body-sm` | Inter 400 | 13px | 1.50 | — |
| `caption` | Inter 500 | 12px | 1.40 | — |
| `overline` | Inter 600 | 11px | 1.30 | +6% · UPPERCASE |

---

## 📏 Espaçamento (base 4px)

| Token | px |
|---|---|
| `space/1` | 4 |
| `space/2` | 8 |
| `space/3` | 12 |
| `space/4` | 16 |
| `space/5` | 20 |
| `space/6` | 24 |
| `space/8` | 32 |
| `space/10` | 40 |
| `space/12` | 48 |
| `space/16` | 64 |

---

## 🔲 Raios de borda

| Token | px |
|---|---|
| `radius/default` | 4 |
| `radius/lg` | 8 |
| `radius/md` | 12 |
| `radius/xl` | 24 |
| `radius/2xl` (stage) | 32 |
| `radius/super` (department) | 44 |
| `radius/full` | 9999 |

---

## 🧱 Bordas

| Token | px |
|---|---|
| `border/hairline` | 1 |
| `border/strong` | 1.5 |
| `border/heavy` | 2 |

---

## 🌑 Sombras (tema claro)

| Token | Valor |
|---|---|
| `shadow/xs` | `0 1px 2px rgba(17,19,23,.04)` |
| `shadow/sm` | `0 1px 3px rgba(17,19,23,.06), 0 1px 2px rgba(17,19,23,.04)` |
| `shadow/md` | `0 4px 12px rgba(17,19,23,.08)` |
| `shadow/lg` | `0 12px 28px rgba(17,19,23,.10)` |
| `shadow/xl` | `0 24px 48px rgba(17,19,23,.12)` |
| `focus-ring` | `0 0 0 3px rgba(198,242,79,.45)` |

---

## 🎬 Motion

| Token | Valor |
|---|---|
| `duration/fast` | 120ms |
| `duration/base` | 180ms |
| `duration/slow` | 280ms |
| `ease/standard` | `cubic-bezier(.4, 0, .2, 1)` |
| `ease/out` | `cubic-bezier(0, 0, .2, 1)` |
| `ease/spring` | `cubic-bezier(.34, 1.56, .64, 1)` |

---

> Para importar no Figma, use o arquivo [`tokens.json`](tokens.json) com o plugin **Tokens Studio for Figma** (Tokens → Settings → Add new → cole/sincronize o JSON).
