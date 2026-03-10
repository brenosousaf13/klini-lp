# Design System — Klini Saúde

> Documento de identidade visual e design system baseado no brandbook oficial da Klini Saúde, adaptado à estrutura de componentes do site [levesaude.com.br](https://www.levesaude.com.br/).

---

## 1. Visão Geral da Marca

**Empresa:** Klini Saúde  
**Logotipo:** "klini saúde" — tipografia customizada em caixa baixa, com detalhe de "sorriso" conectando as letras "n" e "i", reforçando acolhimento e humanização.  
**Tom de voz:** Acolhedor, moderno, acessível e humano. Linguagem direta e próxima do público.

---

## 2. Logotipo

### 2.1 Versões

| Variação | Fundo | Uso |
|---|---|---|
| **Principal (colorida)** | Branco | Header, materiais institucionais, documentos |
| **Branca** | Verde Teal `#259591` | Hero banners, seções com fundo colorido |
| **Branca** | Laranja `#CD7925` | Variações promocionais, destaque quente |
| **Branca** | Rosa/Coral `#E05759` | Variações promocionais, destaque vibrante |

### 2.2 Regras de Uso

- Em **fundo branco**, usar somente a versão colorida (teal + "saúde" em cinza/escuro).
- Em **fundos coloridos** alinhados à paleta da Klini, usar a versão do logo em **branco**.
- Manter área de respiro (safe zone) ao redor do logotipo.
- Nunca distorcer, rotacionar ou alterar as cores fora das variações aprovadas.
- O logotipo possui um elemento gráfico de "sorriso" entre o "n" e o "i" — preservar sempre esse detalhe.

---

## 3. Paleta de Cores

### 3.1 Cores Primárias

| Nome | HEX | RGB | HSB | CMYK | Pantone | Uso |
|---|---|---|---|---|---|---|
| **Teal Principal** | `#259591` | 37, 149, 145 | 178, 75%, 58% | 96, 7, 49, 0 | 2461 C | Cor principal da marca. Botões primários, header, CTAs, ícones |
| **Teal Claro** | `#6AA7AE` | 106, 167, 174 | 186, 39%, 68% | 71, 11, 33, 0 | 549 C | Backgrounds suaves, seções alternadas, hover states |

#### Tints — Teal Principal `#259591`

| Nível | HEX | Uso |
|---|---|---|
| 80% | `#51AAA7` | Hover de botões, bordas ativas |
| 60% | `#7CBFBD` | Backgrounds leves, tags |
| 40% | `#A8D5D3` | Backgrounds muito suaves, cards |
| 20% | `#D3EAE9` | Backgrounds mínimos, faixas claras |

#### Tints — Teal Claro `#6AA7AE`

| Nível | HEX | Uso |
|---|---|---|
| 80% | `#88B9BE` | Bordas suaves, separadores |
| 60% | `#A6CACE` | Backgrounds informativos |
| 40% | `#C3DCDF` | Fundos de seções |
| 20% | `#E1EDEF` | Fundo extremamente sutil |

### 3.2 Cores Secundárias

| Nome | HEX | RGB | HSB | CMYK | Pantone | Uso |
|---|---|---|---|---|---|---|
| **Laranja** | `#CD7925` | 205, 121, 37 | 30, 82%, 80% | 5, 61, 97, 0 | 7565 C | Destaques, preços, badges, CTAs de urgência |
| **Rosa/Coral** | `#E05759` | 224, 87, 89 | 359, 61%, 88% | 0, 78, 55, 0 | 7625 C | Alertas, promoções, destaques vibrantes, acentos |

#### Tints — Laranja `#CD7925`

| Nível | HEX | Uso |
|---|---|---|
| 80% | `#D79451` | Hover de elementos laranja |
| 60% | `#E1AF7C` | Backgrounds de aviso suave |
| 40% | `#EBC9A8` | Cards de destaque |
| 20% | `#F5E4D3` | Fundo de alertas leves |

#### Tints — Rosa/Coral `#E05759`

| Nível | HEX | Uso |
|---|---|---|
| 80% | `#E6797A` | Hover de elementos rosa |
| 60% | `#EC9A9B` | Backgrounds de erro suave |
| 40% | `#F3BCBD` | Cards de atenção |
| 20% | `#F9DDDE` | Fundo de alertas mínimos |

### 3.3 Cores Neutras

| Nome | HEX | Uso |
|---|---|---|
| **Branco** | `#FFFFFF` | Fundo principal, cards, texto sobre fundo escuro |
| **Cinza Claríssimo** | `#F5F7F7` | Fundo de seções alternadas |
| **Cinza Claro** | `#E0E4E4` | Bordas, separadores, dividers |
| **Cinza Médio** | `#9EA8A8` | Textos secundários, placeholders, captions |
| **Cinza Escuro** | `#4A5656` | Textos de corpo |
| **Preto Suave** | `#2D3436` | Títulos, textos de alto contraste |

### 3.4 Cores Semânticas

| Função | HEX | Uso |
|---|---|---|
| **Sucesso** | `#259591` | Confirmações, status positivo (usa a cor primária) |
| **Erro** | `#E05759` | Mensagens de erro, validações negativas |
| **Aviso** | `#CD7925` | Alertas, chamadas de atenção |
| **Informação** | `#6AA7AE` | Dicas, tooltips, informações complementares |

---

## 4. Tipografia

### 4.1 Famílias Tipográficas

| Tipo | Fonte | Classificação | Fallback | Uso |
|---|---|---|---|---|
| **Primária** | **Objective** | Sans-serif | `'Objective', 'Helvetica Neue', Arial, sans-serif` | Títulos, botões, navegação, UI, headings |
| **Secundária** | **Merriweather** | Serif | `'Merriweather', Georgia, 'Times New Roman', serif` | Corpo de texto, parágrafos longos, depoimentos, citações |

> **Objective** transmite modernidade e clareza — ideal para a interface digital.  
> **Merriweather** adiciona legibilidade e personalidade ao texto corrido, criando contraste sofisticado com a sans-serif.

### 4.2 Escala Tipográfica

| Token | Tamanho | Peso | Fonte | Uso |
|---|---|---|---|---|
| `display` | 48–56px | Bold (700) | Objective | Hero banners, headlines de impacto |
| `heading-xl` | 36–40px | Bold (700) | Objective | Títulos de página |
| `heading-lg` | 28–32px | Bold (700) | Objective | Títulos de seção |
| `heading-md` | 22–24px | SemiBold (600) | Objective | Subtítulos, nomes de planos |
| `heading-sm` | 18–20px | SemiBold (600) | Objective | Títulos de cards |
| `body-lg` | 18px | Regular (400) | Merriweather | Leads, destaques de texto |
| `body-md` | 16px | Regular (400) | Merriweather | Corpo de texto padrão |
| `body-sm` | 14px | Regular (400) | Merriweather | Legendas, textos auxiliares |
| `caption` | 12px | Regular (400) | Objective | Labels, disclaimers, notas de rodapé |
| `overline` | 12px | Bold (700) | Objective | Categorias, tags, caixa alta com letter-spacing |

### 4.3 Line Height e Espaçamento

| Tipo | Line-height | Letter-spacing |
|---|---|---|
| **Headings (Objective)** | `1.2` – `1.3` | `0` a `0.01em` |
| **Body (Merriweather)** | `1.6` – `1.7` | `0` |
| **Overline/Caps** | `1.4` | `0.08em` – `0.12em` |

---

## 5. Espaçamento (Spacing Tokens)

| Token | Valor | Uso |
|---|---|---|
| `space-xxs` | 4px | Espaçamento mínimo interno |
| `space-xs` | 8px | Gaps pequenos, padding de ícones |
| `space-sm` | 12px | Espaçamento entre elementos inline |
| `space-md` | 16px | Padding de cards, gaps de grid |
| `space-lg` | 24px | Separação entre blocos |
| `space-xl` | 32px | Margens de seção |
| `space-xxl` | 48px | Separação entre seções |
| `space-xxxl` | 64–80px | Padding de hero e grandes seções |

---

## 6. Bordas e Sombras

### 6.1 Border Radius

| Token | Valor | Uso |
|---|---|---|
| `radius-sm` | 4px | Inputs, tags pequenas |
| `radius-md` | 8px | Cards, modais |
| `radius-lg` | 12–16px | Cards destacados, imagens |
| `radius-xl` | 24px | Botões pill, badges |
| `radius-full` | 50% / 9999px | Avatares, ícones circulares |

### 6.2 Sombras (Elevation)

| Token | Valor CSS | Uso |
|---|---|---|
| `shadow-sm` | `0 1px 3px rgba(37,149,145,0.08)` | Cards sutis, inputs |
| `shadow-md` | `0 4px 14px rgba(37,149,145,0.10)` | Cards elevados, dropdowns |
| `shadow-lg` | `0 8px 28px rgba(37,149,145,0.12)` | Modais, popups, menus flutuantes |
| `shadow-warm` | `0 4px 14px rgba(205,121,37,0.10)` | Cards de destaque com tom quente |

> As sombras utilizam as cores da marca com opacidade baixa, em vez de preto puro, para manter coesão visual.

---

## 7. Iconografia

| Propriedade | Detalhe |
|---|---|
| **Biblioteca recomendada** | Feather Icons ou Lucide Icons (open source) |
| **Ícones customizados** | Contexto de saúde (coração, estetoscópio, escudo, cruz, sorriso) |
| **Estilo** | Outline, traço de 1.5–2px, cantos arredondados (alinhado à suavidade do logo) |
| **Tamanhos** | 16px (inline), 20px (UI), 24px (padrão), 32px (destaque), 48px (ilustrativo) |
| **Cor padrão** | Herdam a cor do texto ou usam Teal Principal `#259591` |
| **Cor alternativa** | Laranja `#CD7925` para ícones de destaque/ação |

---

## 8. Componentes Principais

### 8.1 Botões

| Variante | Fundo | Texto | Borda | Border Radius |
|---|---|---|---|---|
| **Primário** | Teal `#259591` | Branco `#FFF` | Nenhuma | `24px` (pill) |
| **Primário Hover** | `#1E7B78` | Branco `#FFF` | Nenhuma | `24px` |
| **Secundário** | Transparente | Teal `#259591` | 2px Teal `#259591` | `24px` |
| **Secundário Hover** | `#D3EAE9` | Teal `#259591` | 2px Teal | `24px` |
| **Destaque (CTA quente)** | Laranja `#CD7925` | Branco `#FFF` | Nenhuma | `24px` |
| **Ghost** | Transparente | Cinza Escuro `#4A5656` | Nenhuma | `8px` |
| **Disabled** | Cinza `#E0E4E4` | Cinza `#9EA8A8` | Nenhuma | `24px` |

**Estados:** Default → Hover (escurece 10-15%) → Active (escurece 20%) → Focus (outline 2px offset) → Disabled (opacidade reduzida)

**Tipografia dos botões:** Objective, SemiBold (600), 14–16px, caixa normal.

### 8.2 Cards de Planos

- **Fundo:** Branco `#FFFFFF`
- **Sombra:** `shadow-md`
- **Border-radius:** `16px`
- **Estrutura interna:**
  - Overline com nome do plano (Objective Bold, cor Teal)
  - Descrição breve (Merriweather Regular, cinza escuro)
  - Preço em destaque: "a partir de R$…" (Objective Bold, Laranja `#CD7925`)
  - Botão CTA "Saiba mais" (Primário)
- **Hover:** eleva sombra para `shadow-lg`, `translateY(-4px)`
- **Borda superior opcional:** 4px sólida na cor primária

### 8.3 Navbar / Header

- **Fundo:** Branco com sombra sutil na rolagem (sticky top)
- **Logo:** Klini Saúde versão colorida, alinhado à esquerda
- **Links de navegação:** Objective Regular, 15px, cor Cinza Escuro `#4A5656`
- **Link ativo/hover:** cor Teal `#259591`, underline animado
- **CTAs à direita:**
  - "Simule aqui" → botão Primário (Teal pill)
  - "Login" → botão Secundário (outline Teal)
- **Mobile:** Hamburger menu com slide lateral, fundo Teal `#259591`, links em branco

### 8.4 Hero Banner

- **Fundo:** Teal Principal `#259591` ou gradiente `linear-gradient(135deg, #259591 0%, #6AA7AE 100%)`
- **Título:** Objective Bold, 48–56px, Branco
- **Subtítulo:** Merriweather Regular, 18–20px, Branco com opacidade 90%
- **CTA:** Botão Laranja `#CD7925` ou Branco com texto Teal
- **Imagem:** Foto recortada de pessoas/profissionais de saúde à direita

### 8.5 Cards de Clínicas / Localizações

- **Layout:** Horizontal ou em grid
- **Fundo:** Branco, border-radius `12px`, sombra `shadow-sm`
- **Ícone:** Pin de localização em Teal `#259591`
- **Nome:** Objective SemiBold, 18px
- **Horário:** Merriweather Regular, 14px, Cinza Médio
- **Link:** "Veja a localização" → cor Teal, underline no hover

### 8.6 Cards de Diferenciais

- **Layout:** Vertical, centralizado
- **Ícone/Ilustração:** 48–64px, cor Teal ou Laranja
- **Título:** Objective SemiBold, 18–20px, Preto Suave
- **Descrição:** Merriweather Regular, 14–16px, Cinza Escuro
- **CTA:** Link "Saiba Mais" em Teal

### 8.7 Seção de Depoimentos

- **Card:** Fundo Branco, border-radius `16px`, sombra `shadow-md`
- **Avatar:** Círculo 56px, borda 2px Teal `#259591`
- **Nome:** Objective SemiBold, 16px
- **Plano:** Objective Regular, 12px, Teal `#259591`
- **Depoimento:** Merriweather Italic, 16px, Cinza Escuro, com aspas decorativas na cor Teal
- **Carrossel:** Autoplay suave, dots de navegação

### 8.8 Seção de Contato

- **Cards de canal:** Fundo branco, ícone do canal (WhatsApp, telefone, email) em Teal
- **Número/link:** Objective Bold, 20px, Teal
- **Descrição:** Merriweather Regular, 14px, Cinza Médio
- **Horário:** Caption, Objective Regular, 12px

### 8.9 Footer

- **Fundo:** Preto Suave `#2D3436` ou Teal Escuro
- **Logo:** Klini Saúde versão branca
- **Propósito/tagline:** Merriweather Italic, 14px, Branco com opacidade 70%
- **Links:** Objective Regular, 14px, Branco com opacidade 80%, hover 100%
- **Títulos de coluna:** Objective Bold, 14px, Branco, caixa alta, letter-spacing `0.08em`
- **Redes sociais:** Ícones 24px em branco, hover em Laranja `#CD7925`
- **Badges de app stores:** Apple Store + Google Play
- **Créditos/legal:** Caption 12px, Branco com opacidade 50%

### 8.10 Botão Flutuante WhatsApp

- **Posição:** Fixed, bottom-right (24px de margem)
- **Tamanho:** 56px circular
- **Cor:** Verde WhatsApp `#25D366`
- **Ícone:** WhatsApp branco
- **Sombra:** `shadow-lg`
- **Animação:** Bounce sutil ao carregar, pulse ao hover

---

## 9. Grid e Layout

| Propriedade | Valor |
|---|---|
| **Container máximo** | 1200px |
| **Colunas** | 12 colunas (CSS Grid ou Flexbox) |
| **Gutter** | 24px |
| **Breakpoints** | `sm`: < 640px · `md`: 640–1024px · `lg`: > 1024px · `xl`: > 1280px |
| **Padding lateral** | 16px (mobile) · 24px (tablet) · 0 (desktop, container centralizado) |

---

## 10. Imagens e Fotografia

| Tipo | Diretriz |
|---|---|
| **Banners hero** | Pessoas sorridentes, profissionais de saúde, famílias. Tons quentes e naturais. |
| **Tratamento** | Overlay teal semitransparente em fotos de fundo. Duotone teal+laranja em ilustrações. |
| **Ícones ilustrativos** | Estilo flat/outline, traço fino, paleta da marca. |
| **Fotos de clínicas** | Ambientes limpos, claros, modernos, acolhedores. |
| **Border-radius em imagens** | `12–16px` em cards; `50%` em avatares. |

---

## 11. Animações e Interações

| Elemento | Comportamento |
|---|---|
| **Transição padrão** | `transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1)` |
| **Cards hover** | `translateY(-4px)` + elevação de sombra |
| **Navbar sticky** | Fundo transparente → branco com `shadow-sm` ao rolar |
| **Carrosséis** | Slide horizontal, autoplay 5s, dots de navegação |
| **Botão WhatsApp** | Bounce sutil na entrada, pulse no hover |
| **Links** | Underline animado da esquerda para direita |
| **Fade-in on scroll** | Elementos aparecem suavemente ao entrar no viewport |

---

## 12. Acessibilidade

| Diretriz | Implementação |
|---|---|
| **Contraste** | WCAG AA mínimo (4.5:1 texto, 3:1 elementos grandes). Teal `#259591` sobre branco = ✅ 4.56:1 |
| **Foco visível** | Outline 2px offset na cor Teal em todos os elementos interativos |
| **Alt text** | Todas as imagens com descrição significativa |
| **Semântica HTML** | h1–h6 hierárquicos, landmarks `<header>`, `<nav>`, `<main>`, `<footer>` |
| **Tamanho de toque** | Mínimo 44×44px em mobile |
| **Texto redimensionável** | Layout responsivo com unidades `rem` |

---

## 13. Design Tokens (CSS Custom Properties)

```css
:root {
  /* ===== CORES PRIMÁRIAS ===== */
  --color-teal: #259591;
  --color-teal-light: #6AA7AE;
  --color-teal-80: #51AAA7;
  --color-teal-60: #7CBFBD;
  --color-teal-40: #A8D5D3;
  --color-teal-20: #D3EAE9;
  --color-teal-light-80: #88B9BE;
  --color-teal-light-60: #A6CACE;
  --color-teal-light-40: #C3DCDF;
  --color-teal-light-20: #E1EDEF;

  /* ===== CORES SECUNDÁRIAS ===== */
  --color-orange: #CD7925;
  --color-orange-80: #D79451;
  --color-orange-60: #E1AF7C;
  --color-orange-40: #EBC9A8;
  --color-orange-20: #F5E4D3;
  --color-coral: #E05759;
  --color-coral-80: #E6797A;
  --color-coral-60: #EC9A9B;
  --color-coral-40: #F3BCBD;
  --color-coral-20: #F9DDDE;

  /* ===== NEUTROS ===== */
  --color-white: #FFFFFF;
  --color-bg-light: #F5F7F7;
  --color-gray-light: #E0E4E4;
  --color-gray-medium: #9EA8A8;
  --color-gray-dark: #4A5656;
  --color-black: #2D3436;

  /* ===== SEMÂNTICAS ===== */
  --color-success: #259591;
  --color-error: #E05759;
  --color-warning: #CD7925;
  --color-info: #6AA7AE;

  /* ===== TIPOGRAFIA ===== */
  --font-heading: 'Objective', 'Helvetica Neue', Arial, sans-serif;
  --font-body: 'Merriweather', Georgia, 'Times New Roman', serif;

  /* ===== ESPAÇAMENTO ===== */
  --space-xxs: 4px;
  --space-xs: 8px;
  --space-sm: 12px;
  --space-md: 16px;
  --space-lg: 24px;
  --space-xl: 32px;
  --space-xxl: 48px;
  --space-xxxl: 80px;

  /* ===== BORDAS ===== */
  --radius-sm: 4px;
  --radius-md: 8px;
  --radius-lg: 16px;
  --radius-pill: 24px;
  --radius-full: 9999px;

  /* ===== SOMBRAS ===== */
  --shadow-sm: 0 1px 3px rgba(37, 149, 145, 0.08);
  --shadow-md: 0 4px 14px rgba(37, 149, 145, 0.10);
  --shadow-lg: 0 8px 28px rgba(37, 149, 145, 0.12);
  --shadow-warm: 0 4px 14px rgba(205, 121, 37, 0.10);

  /* ===== TRANSIÇÕES ===== */
  --transition-default: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  --transition-fast: all 0.15s ease;
  --transition-slow: all 0.5s ease;
}
```

---

## 14. Mapa de Componentes → Seções da LP

Referência de como os componentes se mapeiam à estrutura da LP (baseada no layout da Leve Saúde):

| Seção da LP | Componentes utilizados |
|---|---|
| **Header** | Navbar (8.3) |
| **Hero** | Hero Banner (8.4) |
| **Acesso Rápido** | Cards com ícone + link (8.5 adaptado) |
| **Planos** | Cards de Planos (8.2) em grid/carrossel |
| **Diferenciais** | Cards de Diferenciais (8.6) em grid |
| **Clínicas** | Cards de Clínicas (8.5) em carrossel |
| **Depoimentos** | Seção de Depoimentos (8.7) em carrossel |
| **Contato** | Seção de Contato (8.8) em grid |
| **Recrutamento/CTA** | Cards com ícone + botão (8.6 variação) |
| **Footer** | Footer completo (8.9) |
| **WhatsApp flutuante** | Botão flutuante (8.10) |

---

*Documento criado em março de 2026. Fontes tipográficas (Objective e Merriweather) e valores de cor extraídos do brandbook oficial da Klini Saúde.*
