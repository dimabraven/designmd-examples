---
name: Stripe Design System
style: clean, high-density, professional
colors:
  primary: "#635BFF"
  primary-hover: "#4F46E5"
  background: "#FFFFFF"
  surface: "#F6F9FC"
  surface-raised: "#FFFFFF"
  border: "#E3E8EE"
  border-strong: "#C1C9D2"
  text-primary: "#0A2540"
  text-secondary: "#425466"
  text-muted: "#8898AA"
  success: "#09825D"
  error: "#CD3D64"
  warning: "#B5810A"
typography:
  heading: "Inter, -apple-system, sans-serif"
  body: "Inter, -apple-system, sans-serif"
  mono: "Roboto Mono, monospace"
  scale:
    h1: "2rem / 700"
    h2: "1.5rem / 600"
    h3: "1.125rem / 600"
    body: "0.9375rem / 400"
    small: "0.8125rem / 400"
    label: "0.75rem / 500 / uppercase / 0.08em tracking"
spacing:
  base: "4px"
  scale: "4, 8, 12, 16, 20, 24, 32, 40, 48, 64"
radius:
  button: "6px"
  card: "8px"
  input: "6px"
  badge: "4px"
shadows:
  card: "0 2px 5px rgba(60,66,87,0.08), 0 0 0 1px rgba(60,66,87,0.10)"
  elevated: "0 7px 14px rgba(60,66,87,0.08), 0 3px 6px rgba(0,0,0,0.06)"
  modal: "0 15px 35px rgba(60,66,87,0.1), 0 5px 15px rgba(0,0,0,0.07)"
---

# Stripe Design System

## Visual direction

Stripe UI is clean, functional, and trustworthy. Every element earns its place. The palette uses deep navy on white with a single indigo accent. Density is high — expect compact lists, tight padding, and data-rich layouts. Nothing decorative; everything purposeful.

## Layout

- Container max-width: 1120px with 24px horizontal padding
- Page sections use 40–64px vertical spacing
- Dashboard sidebar: 220px fixed, content fills remainder
- Cards use 24px internal padding
- Table rows: 48px height minimum

## Components

### Buttons

```
Primary:   bg-[#635BFF] text-white px-4 py-2 rounded-[6px] text-sm font-medium hover:bg-[#4F46E5]
Secondary: bg-white border border-[#E3E8EE] text-[#0A2540] px-4 py-2 rounded-[6px] text-sm
Danger:    bg-[#CD3D64] text-white px-4 py-2 rounded-[6px] text-sm font-medium
Link:      text-[#635BFF] hover:text-[#4F46E5] no underline by default
```

- No large rounded buttons. Radius stays at 6px.
- Icon-only buttons get a subtle hover background, not a border.
- Loading state: replace label with spinner, same size.

### Cards

```
bg-white border border-[#E3E8EE] rounded-[8px] shadow-[0_2px_5px_rgba(60,66,87,0.08)]
```

- Card headers use a thin bottom border to separate from body.
- Use `surface` (#F6F9FC) for nested/secondary sections inside cards.

### Forms and inputs

```
Input: border border-[#E3E8EE] rounded-[6px] px-3 py-2 text-sm text-[#0A2540]
       focus:border-[#635BFF] focus:ring-2 focus:ring-[#635BFF]/20
Label: text-[0.75rem] font-medium uppercase tracking-[0.08em] text-[#425466] mb-1
Error: border-[#CD3D64] focus:ring-[#CD3D64]/20 + error text in #CD3D64 below input
```

- Labels always uppercase, small, above the input.
- Helper text in `#8898AA`, error text in `#CD3D64`.
- Do not use placeholder as label.

### Tables

```
Header row: bg-[#F6F9FC] text-[0.75rem] uppercase tracking-[0.08em] text-[#8898AA]
Body rows:  border-b border-[#E3E8EE] hover:bg-[#F6F9FC] transition
Cell text:  text-[0.9375rem] text-[#0A2540]
```

- Numeric columns right-align.
- Amounts use tabular numbers (`font-variant-numeric: tabular-nums`).
- Status badges: small, colored background, no border.

### Badges / status

```
Success: bg-[#CBF4C9] text-[#09825D] rounded-[4px] px-2 py-0.5 text-xs font-medium
Error:   bg-[#FFE8EE] text-[#CD3D64] rounded-[4px] px-2 py-0.5 text-xs font-medium
Neutral: bg-[#F6F9FC] text-[#425466] rounded-[4px] px-2 py-0.5 text-xs font-medium
```

### Navigation

- Left sidebar: white bg, 1px right border, items use 12px vertical padding
- Active item: `#635BFF` left border (3px), text in `#0A2540`, bg `#F6F9FC`
- Section labels: uppercase, 0.75rem, `#8898AA`, not clickable

## Spacing rules

- 8px between label and input
- 16px between form fields
- 24px between card sections
- 32–40px between page sections
- Never use margin-top on the first child of a container

## Do

- Use `#0A2540` for all primary text — not black, not gray-900
- Use tabular numbers for any monetary or numeric data
- Use a 1px `#E3E8EE` border for all cards and inputs
- Keep line heights tight: 1.4 for body, 1.2 for headings
- Use `#8898AA` for secondary/metadata text — not lighter

## Don't

- Don't use rounded-full buttons
- Don't use heavy drop shadows — only the defined shadow tokens
- Don't use color fills for section backgrounds — use `#F6F9FC` or white only
- Don't mix font weights heavily — 400, 500, 600, 700 only
- Don't use blue for anything other than primary actions and links

## Agent instructions

Apply this DESIGN.md to all UI components in this project. When generating a new component:

1. Use the exact color hex values — do not substitute with Tailwind color names
2. Apply the uppercase label pattern to all form labels
3. Use the shadow token for cards, not `shadow-md` or custom values
4. Match the button radius (6px) and input radius (6px) — not rounded-md
5. When in doubt about density: go tighter, not looser
