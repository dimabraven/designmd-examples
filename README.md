# DESIGN.md — The Directory

A curated collection of DESIGN.md files, templates, and resources for AI coding agents.

**DESIGN.md** is a plain-text design system file that tells AI coding agents (Cursor, Claude Code, Codex, Windsurf) how to generate UI with consistent visual direction instead of generic defaults.

Browse the full directory → [designmd.directory](https://designmd.directory)

Maintained by [Dima Braven](https://dimabraven.com), creator of [DesignMD Directory](https://designmd.directory).

---

## Install any DESIGN.md in one command

```bash
npx designmd-cli install stripe
npx designmd-cli install linear
npx designmd-cli install vercel
```

Or install globally:

```bash
npm install -g designmd-cli
designmd-cli install <slug>
```

### CLI commands

| Command | Description |
|---|---|
| `designmd-cli install <slug>` | Download a DESIGN.md into your project |
| `designmd-cli list` | Browse all available files |
| `designmd-cli search <query>` | Search by brand, style, or category |
| `designmd-cli install <slug> --path ./my-design.md` | Custom output path |

After installing, tell your agent: **"Follow the design system in DESIGN.md"**

→ [designmd-cli on npm](https://www.npmjs.com/package/designmd-cli)

---

## Example files in this repo

Ready-to-use DESIGN.md files you can copy directly into your project:

- [`examples/stripe.md`](examples/stripe.md) — Clean, high-density fintech UI
- [`examples/linear.md`](examples/linear.md) — Dark, minimal productivity tool style
- [`examples/minimal-saas.md`](examples/minimal-saas.md) — Neutral SaaS starter for any product

---

## Featured examples

- [Google DESIGN.md spec](https://designmd.directory/p/google-designmd-spec) — reference for the DESIGN.md format.
- [Google Stitch workflow](https://designmd.directory/p/google-stitch) — DESIGN.md context for Google Stitch-style UI.
- [Cursor workflow reference](https://designmd.directory/p/cursor-workflow-reference) — practical reference for Cursor projects.
- [Claude Code workflow reference](https://designmd.directory/p/claude-code-workflow-reference) — practical reference for Claude Code.
- [Codex workflow reference](https://designmd.directory/p/codex-workflow-reference) — practical reference for Codex-style agents.
- [Minimal SaaS dashboard DESIGN.md](https://designmd.directory/p/minimal-saas-dashboard-designmd) — compact dashboard example.
- [AI app starter DESIGN.md](https://designmd.directory/p/ai-app-starter-designmd) — starter visual system for AI products.
- [Landing page DESIGN.md](https://designmd.directory/p/landing-page-designmd) — example for marketing pages.
- [Admin panel DESIGN.md](https://designmd.directory/p/admin-panel-designmd) — admin interface reference.
- [Analytics dashboard DESIGN.md](https://designmd.directory/p/analytics-dashboard-designmd) — data-heavy product UI.

## Templates

- [Tailwind DESIGN.md template](https://designmd.directory/p/tailwind-designmd-template) — reusable template for Tailwind projects.
- [shadcn/ui DESIGN.md starter](https://designmd.directory/p/shadcnui-designmd-starter) — starter for shadcn/ui projects.
- [All Tailwind templates](https://designmd.directory/templates/tailwind)
- [All shadcn/ui templates](https://designmd.directory/templates/shadcn)

## Tool guides

- [DESIGN.md for Cursor](https://designmd.directory/learn/design-md-for-cursor) — using DESIGN.md as persistent design context in Cursor.
- [DESIGN.md for Claude Code](https://designmd.directory/learn/design-md-for-claude-code) — using DESIGN.md with Claude Code for frontend work.
- [DESIGN.md for Codex](https://designmd.directory/learn/design-md-for-codex) — using DESIGN.md with Codex-style agents.

---

## What makes a good DESIGN.md?

A useful DESIGN.md should include:

- **Color tokens** with clear roles (primary, surface, border, muted), not only raw hex values.
- **Typography scale** with font families, weights, sizes, and usage.
- **Spacing and radius rules** that map to real UI decisions.
- **Component guidance** for buttons, cards, forms, navigation, and empty states.
- **Layout principles** covering density, rhythm, responsive behavior, and hierarchy.
- **Do / don't rules** that prevent common AI-generated UI mistakes.
- **Agent instructions** that tell the model exactly how to apply the file.

## Example structure

```md
---
name: Product Design System
colors:
  primary: "#111827"
  accent: "#5B5EF4"
  background: "#FFFFFF"
  surface: "#F8FAFC"
typography:
  heading: "Inter, sans-serif"
  body: "Inter, sans-serif"
radius:
  card: "8px"
  button: "999px"
---

# Product Design System

## Visual Direction

Describe the visual personality, density, and hierarchy.

## Components

Define buttons, cards, forms, navigation, and common states.

## Agent Instructions

Explain how Cursor, Claude Code, Codex, or another agent should apply the system.
```

---

## Learn more

- [What is DESIGN.md?](https://designmd.directory/learn/what-is-design-md)
- [DESIGN.md examples](https://designmd.directory/learn/design-md-examples)
- [DESIGN.md vs design tokens](https://designmd.directory/learn/design-md-vs-design-tokens)
- [DESIGN.md vs Claude.md](https://designmd.directory/learn/design-md-vs-claude-md)
- [Why AI agents make generic UI](https://designmd.directory/learn/why-ai-agents-make-ugly-ui)
- [Browse all examples](https://designmd.directory/examples)

---

## Contributing

Suggestions are welcome. Open an issue with a link to a useful DESIGN.md resource, example, or template.

Include:
- URL
- Short description
- Why it is useful for people writing DESIGN.md files

## License

MIT
