---
name: Atelier Médico de Longevidade
colors:
  surface: '#f5f5f5'
  surface-dim: '#e0e0e0'
  surface-bright: '#fafafa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f1f1'
  surface-container: '#ececec'
  surface-container-high: '#e5e5e5'
  surface-container-highest: '#e0e0e0'
  on-surface: '#181d1c'
  on-surface-variant: '#424242'
  inverse-surface: '#2c3130'
  inverse-on-surface: '#f3f3f3'
  outline: '#727876'
  outline-variant: '#c7c7c7'
  surface-tint: '#4b635c'
  primary: '#001611'
  on-primary: '#ffffff'
  primary-container: '#132b25'
  on-primary-container: '#d6d6d6'
  inverse-primary: '#c8c8c8'
  secondary: '#725b24'
  on-secondary: '#ffffff'
  secondary-container: '#fcdc98'
  on-secondary-container: '#775f28'
  tertiary: '#001610'
  on-tertiary: '#ffffff'
  tertiary-container: '#0a2c23'
  on-tertiary-container: '#d2d2d2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e5e5'
  primary-fixed-dim: '#c8c8c8'
  on-primary-fixed: '#181d1c'
  on-primary-fixed-variant: '#424242'
  secondary-fixed: '#ffdf9b'
  secondary-fixed-dim: '#e2c381'
  on-secondary-fixed: '#251a00'
  on-secondary-fixed-variant: '#59440e'
  tertiary-fixed: '#e5e5e5'
  tertiary-fixed-dim: '#c8c8c8'
  on-tertiary-fixed: '#181818'
  on-tertiary-fixed-variant: '#424242'
  background: '#f5f5f5'
  on-background: '#181d1c'
  surface-variant: '#e1e1e1'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system establishes a high-end, clinically rigorous visual identity tailored for endocrinology and clinical nutrition. Grounded in ethical medical guidelines, the aesthetic favors scientific precision, discreet service, and a restrained, neutral-gray canvas.

### Target Audience & Emotional Impact
- **Audience:** Patients seeking endocrinology, metabolic health, and clinical nutrition care.
- **Emotional Response:** Inspire reassurance, clinical confidence, discretion, and clarity while preserving a calm, professional tone.

### Design Movement
- **Editorial Minimalism:** Deep forest green anchors the institutional identity, muted gold highlights important actions, and neutral grays provide calm, readable surfaces. High-contrast typography pairs classical serif headlines with clear sans-serif body text.

## Colors

Use neutral grays for the page canvas and cards; reserve forest green for the brand, primary actions, and dark feature sections. Use gold sparingly for accents and active states.

- **Primary (`#132B25` - Deep Forest Green):** Institutional anchor for branding, primary actions, and selected dark surfaces.
- **Secondary (`#C5A869` - Noble Warm Gold):** Restrained accent for borders, active states, and iconography.
- **Tertiary (`#2C4C42` - Muted Pine Slate):** Supporting brand color for limited use in dark visual elements.
- **Neutral (`#181D1C` - Deep Graphite):** Main text color for clear contrast and legibility.
- **Canvas & Background Surfaces:** Use neutral gray `#F5F5F5` for the page background, `#F1F1F1` for subtle section separation, and white `#FFFFFF` for elevated cards.

## Typography

The typography system strikes a deliberate tension between classic editorial prestige and ultra-modern humanistic clarity:

- **Playfair Display (Headlines & Institutional Statements):** Introduces medical humanism, authoritative prestige, and traditional academic rigor. Used for section intros, headline treatments, and clinician citations.
- **Plus Jakarta Sans (Body, Diagnostics, Labels & Actions):** Provides geometric balance, clear numerical rendering for diagnostic metrics, and rapid mobile scannability.
- **Uppercase Labels:** The `label-sm` role uses wide letter-spacing (`0.08em`) exclusively in uppercase for medical categories, specialty designations, and CRM metadata (e.g., "CRM-SP 000.000 / RQE").

## Layout & Spacing

The layout philosophy mirrors private clinic architecture: calm, unhurried, with generous breathing space between procedural domains.

### Grid Architecture
- **Desktop (1200px+):** 12-column layout with a maximum container boundary of `1280px`. Generous `3rem` canvas margins establish an exclusive, gallery-level framing.
- **Tablet (768px - 1199px):** 8-column layout with `2rem` outer margins.
- **Mobile (< 768px):** 4-column fluid layout with `1.25rem` outer gutters. Dense data modules reflow into vertical, tactile cards.

### Spacing Rhythm
Spacious vertical cadences (`space-xl` and above) are mandated between distinct medical programs (e.g., Longevity vs. Hormone Replacement vs. Clinical Nutrition), avoiding clutter and reducing cognitive stress.

## Elevation & Depth

Visual depth is achieved through neutral surface contrast and restrained shadows:

- **Tonal Layering:** The canvas uses `#F5F5F5`; elevated modules sit on `#FFFFFF` with a subtle neutral shadow (`rgba(24, 29, 28, 0.06) 0 8px 30px`).
- **Refined Hairline Borders:** Cards and panels use subtle 1px neutral-gray borders (`rgba(24, 29, 28, 0.12)`), with restrained gold accents (`rgba(197, 168, 105, 0.3)`) for focus and active states.
- **Dark Elegance Inversion:** Select hero segments and footer anchors retain deep forest green with low-opacity white borders and restrained gold highlights.

## Shapes

The design uses a soft, disciplined geometry (`roundedness: 1`). 

- Standard interactive controls, form fields, and medical tags feature a subtle `0.25rem` (4px) corner radius.
- Cards, clinical modal dialogs, and diagnostic containers feature an `8px` (`0.5rem`) soft radius.
- Circles are reserved strictly for physician portraits, monogram insignia, and status indicators.
- This restrained curvature avoids casual playfulness, reinforcing precision, architectural stability, and scientific discipline.

## Components

### Buttons
- **Primary Action (Agendamento / Triagem):** Background in Deep Forest Green (`#132B25`), typography in white Plus Jakarta Sans (`label-md`), 14px vertical padding and 28px horizontal padding. Subtle gold hairline border hover effect (`#C5A869`).
- **Secondary Action (Corpo Clínico / Protocolos):** Ghost style with a 1px border in `#132B25` at 25% opacity, shifting to `#132B25` solid fill with white text on hover.
- **Concierge / WhatsApp Direct:** Muted dark olive surface with gold iconography, conveying high-touch personal medicine.

### Cards & Service Panels
- Built on pure `#FFFFFF` over neutral-gray `#F5F5F5` backgrounds.
- Feature 1px neutral boundary lines in `rgba(24, 29, 28, 0.12)`.
- Cards display treatment pillar, medical scope, and an expandable link to scientific references.

### Chips & Badges
- **Clinical Badges:** Compact pills with a light-gray tint (`#F1F1F1`), `#132B25` text, and subtle 1px border.
- **Specialty Certifications (CFM/RQE):** Framed in a delicate champagne border (`#C5A869`) with 11px uppercase typography.

### Input Fields & Selectors
- Background set to pure `#FFFFFF` with a 1px border in `rgba(30, 35, 34, 0.15)`.
- Active focus state transitions smoothly to an elegant `#132B25` ring with 1px gold outer glow (`#C5A869`).
- Labels sit cleanly above the field in `Plus Jakarta Sans` medium weight.

### Medical Team / Physician Profile Module
- Structured profile framing displaying full academic title, CFM/RQE validation, institutional memberships, and an organic portrait framed with an architectural 4px corner radius.

## Conversão, acessibilidade e qualidade

- **Hierarquia do hero:** apresentar em um único H1 o benefício principal em linguagem clara, acompanhado por uma explicação breve e uma CTA primária visível. Repetir o mesmo texto de CTA ao longo da página e manter links secundários visualmente discretos.
- **Ritmo visual:** organizar o conteúdo em uma sequência curta — proposta de valor, diferenciais, equipe, especialidades, método e agendamento. Consolidar módulos repetidos e limitar grades a poucos itens escaneáveis.
- **Prova social responsável:** usar apenas depoimentos publicados com autorização e informações verificáveis. Não inventar avaliações, resultados clínicos, selos ou credenciais; exibir CRM/RQE somente após confirmação dos dados.
- **Formulários:** pedir apenas nome, telefone e motivo do contato; deixar detalhes adicionais opcionais. Usar rótulos persistentes, indicar campos obrigatórios e explicar o uso dos dados sem solicitar histórico clínico desnecessário.
- **Campanhas e SEO local:** alinhar cada anúncio a uma oferta, headline e CTA consistentes. Usar título e descrição únicos, um H1, conteúdo local útil e dados estruturados somente quando os dados do estabelecimento estiverem confirmados.
- **Mobile e desempenho:** priorizar leitura e CTA em telas pequenas, manter controles com pelo menos 44px de altura, carregar imagens abaixo da primeira dobra sob demanda e priorizar a imagem principal. Reservar dimensões para imagens, oferecer foco visível por teclado e respeitar `prefers-reduced-motion`.
- **Contraste:** manter texto normal com contraste mínimo de 4,5:1 e texto grande com 3:1, sem depender apenas de cor para comunicar estado ou importância.