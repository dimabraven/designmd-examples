# DESIGN.md Examples

A curated collection of DESIGN.md examples, templates, and resources for AI coding agents.

DESIGN.md is a plain-text design system file that helps tools like Cursor, Claude Code, Codex, Windsurf, and other AI coding agents generate UI with consistent visual direction instead of generic defaults.

Maintained by [Dima Braven](https://dimabraven.com), founder of [Itmeo](https://itmeo.com) and creator of [DesignMD Directory](https://designmd.directory).

## Featured Examples

- [Google DESIGN.md spec](https://designmd.directory/p/google-designmd-spec) - reference for the DESIGN.md format and how agents should read it.
- [Google Stitch workflow](https://designmd.directory/p/google-stitch) - DESIGN.md context for Google Stitch-style UI generation.
- [Cursor workflow reference](https://designmd.directory/p/cursor-workflow-reference) - practical DESIGN.md reference for Cursor projects.
- [Claude Code workflow reference](https://designmd.directory/p/claude-code-workflow-reference) - practical DESIGN.md reference for Claude Code.
- [Codex workflow reference](https://designmd.directory/p/codex-workflow-reference) - practical DESIGN.md reference for Codex-style agents.
- [Minimal SaaS dashboard DESIGN.md](https://designmd.directory/p/minimal-saas-dashboard-designmd) - compact dashboard-oriented DESIGN.md example.
- [AI app starter DESIGN.md](https://designmd.directory/p/ai-app-starter-designmd) - starter visual system for AI product interfaces.
- [Landing page DESIGN.md](https://designmd.directory/p/landing-page-designmd) - DESIGN.md example for marketing pages.
- [Admin panel DESIGN.md](https://designmd.directory/p/admin-panel-designmd) - admin and dashboard interface reference.
- [Analytics dashboard DESIGN.md](https://designmd.directory/p/analytics-dashboard-designmd) - data-heavy product UI reference.

## Templates

- [Tailwind design memory reference](https://designmd.directory/p/tailwind-design-memory-reference) - Tailwind-focused DESIGN.md reference.
- [shadcn/ui reference](https://designmd.directory/p/shadcnui-reference) - component-system reference for shadcn/ui projects.
- [Tailwind DESIGN.md template](https://designmd.directory/p/tailwind-designmd-template) - reusable template for Tailwind projects.
- [shadcn/ui DESIGN.md starter](https://designmd.directory/p/shadcnui-designmd-starter) - starter DESIGN.md for shadcn/ui projects.
- [All Tailwind templates](https://designmd.directory/templates/tailwind) - browse Tailwind-oriented templates.
- [All shadcn/ui templates](https://designmd.directory/templates/shadcn) - browse shadcn/ui-oriented templates.

## Tool Guides

- [DESIGN.md for Cursor](https://designmd.directory/learn/design-md-for-cursor) - how to use DESIGN.md as persistent design context in Cursor.
- [DESIGN.md for Claude Code](https://designmd.directory/learn/design-md-for-claude-code) - how to use DESIGN.md with Claude Code for frontend work.
- [DESIGN.md for Codex](https://designmd.directory/learn/design-md-for-codex) - how to use DESIGN.md with Codex-style coding agents.

## Learn More

- [DesignMD Directory](https://designmd.directory) - full catalog of DESIGN.md examples, templates, and guides.
- [Browse all examples](https://designmd.directory/examples)
- [What is DESIGN.md?](https://designmd.directory/learn/what-is-design-md)
- [DESIGN.md examples](https://designmd.directory/learn/design-md-examples)
- [DESIGN.md vs design tokens](https://designmd.directory/learn/design-md-vs-design-tokens)
- [DESIGN.md vs Claude.md](https://designmd.directory/learn/design-md-vs-claude-md)
- [Why AI agents make generic UI](https://designmd.directory/learn/why-ai-agents-make-ugly-ui)

## What Makes a Good DESIGN.md?

A useful DESIGN.md should include:

- Color tokens with clear roles, not only raw hex values.
- Typography scale with font families, weights, sizes, and intended usage.
- Spacing and radius rules that map to real UI decisions.
- Component guidance for buttons, cards, forms, navigation, and empty states.
- Layout principles that explain density, rhythm, responsive behavior, and hierarchy.
- Do and don't rules that prevent common AI-generated UI mistakes.
- Short prompt guidance that tells an agent how to apply the file.

## Example Structure

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

## Related Topics

- AI coding agents
- Cursor design rules
- Claude Code design systems
- Codex UI generation
- Tailwind templates
- shadcn/ui templates
- Design tokens
- Agent instructions

## Contributing

Suggestions are welcome. Open an issue with a link to a useful DESIGN.md resource, example, template, or article.

Please include:

- URL
- Short description
- Why it is useful for people writing DESIGN.md files

## License

MIT
