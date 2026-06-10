# AI Coding Rules Markdown

> A centralized specification repository for AI coding assistants, containing agent behavior rules, UI design system guidelines, and project management conventions.

## Purpose

This project serves as the **single source of truth** for AI programming assistants when working on codebases. It defines:

1. **Agent Rules** (`AGENTS.user.md`) — Mandatory quality gates, code structure standards, documentation conventions, debugging protocols, and TODO management workflows that every AI assistant must follow.
2. **UI Design System** (`DESIGN.{style}.md`) — Complete specifications for 7 mainstream UI design styles (Neumorphism, Glassmorphism, Cyberpunk, Claymorphism, Minimalism, Retro Futurism, Aurora) with color systems, core CSS, and component guidelines.
3. **Project TODO Convention** (`TODO.md`) — Standardized format for tracking pending, in-progress, and completed work items.

## File Structure

```
.
├── README.md                  # This file — project overview
├── AGENTS.user.md             # AI agent behavior rules & constraints
├── TODO.md                    # Project todo list (auto-managed by agents)
├── DESIGN.neumorphism.md      # Neumorphism design spec
├── DESIGN.glassmorphism.md    # Glassmorphism design spec
├── DESIGN.cyberpunk.md        # Cyberpunk design spec
├── DESIGN.claymorphism.md     # Claymorphism design spec
├── DESIGN.minimalism.md       # Minimalism design spec
├── DESIGN.retro-futurism.md   # Retro Futurism design spec
├── DESIGN.aurora.md           # Aurora gradient design spec
└── styles.preview.html        # Interactive HTML preview (open locally in browser)
```

## Usage

- **For AI Assistants**: Read `AGENTS.user.md` before starting any task. Follow all 6 rules strictly.
- **For Developers**: Reference `DESIGN.{style}.md` when implementing UI. Choose the style that matches your product type.
- **For Project Tracking**: Agents auto-update `TODO.md` with `PENDING` / `IN_PROGRESS` / `COMPLETED` statuses.

## Design Style Quick Reference

| Product Type | Recommended Style | Rationale |
|-------------|-------------------|-----------|
| B2B / Enterprise | Aurora + Glassmorphism | Professional, efficient, accessible |
| B2C / Consumer | Claymorphism | Friendly, lively, warm |
| Web3 / Metaverse | Glassmorphism + Cyberpunk | Tech-forward, futuristic |
| Brand / Marketing | Retro Futurism + Aurora | Strong visual impact |
| AI / SaaS | Aurora ✅ | Linear / Notion AI standard, timeless |
| Luxury / High-end | Minimalism | Premium feel, whitespace aesthetics |

---

> *(Note: Portions of design documentation may be AI-generated.)*
