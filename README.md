# DESIGN.md Examples

A curated collection of DESIGN.md examples, templates, and resources for AI coding agents.

DESIGN.md is a plain-text design system file that helps tools like Cursor, Claude Code, Codex, Windsurf, and other AI coding agents generate UI with consistent visual direction instead of generic defaults.

## Browse Examples

- [DesignMD Directory](https://designmd.directory) - curated directory of real-world DESIGN.md files, templates, and guides for AI coding agents.
- [DESIGN.md for Cursor](https://designmd.directory/for/cursor) - examples and guidance for using DESIGN.md with Cursor.
- [DESIGN.md for Claude Code](https://designmd.directory/for/claude-code) - examples and guidance for using DESIGN.md with Claude Code.
- [DESIGN.md for Codex](https://designmd.directory/for/codex) - examples and guidance for using DESIGN.md with Codex.
- [Tailwind DESIGN.md templates](https://designmd.directory/templates/tailwind) - DESIGN.md templates for Tailwind-based projects.
- [shadcn/ui DESIGN.md templates](https://designmd.directory/templates/shadcn) - DESIGN.md templates for shadcn/ui projects.

## Learn

- [What is DESIGN.md?](https://designmd.directory/learn/what-is-design-md)
- [DESIGN.md examples](https://designmd.directory/learn/design-md-examples)
- [DESIGN.md template guide](https://designmd.directory/learn/design-md-template)
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
