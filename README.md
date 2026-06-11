# AI Coding Rules Markdown

> A centralized specification repository for AI coding assistants, containing agent behavior rules, UI design system guidelines, and project management conventions.

## Purpose

This project serves as the **single source of truth** for AI programming assistants when working on codebases. It defines:

1. **Agent Rules** (`AGENTS.user.md`) — Mandatory quality gates, code structure standards, documentation conventions, debugging protocols, and TODO management workflows that every AI assistant must follow.
2. **UI Design System** (`DESIGN-SYSTEM.md`) — Complete design system index covering B2B SaaS, C-end APP, and Website design styles with color systems, core CSS, and component guidelines.
3. **Project TODO Convention** (`TODO.md`) — Standardized format for tracking pending, in-progress, and completed work items.

## File Structure

```
.
├── README.md                  # This file — project overview
├── DESIGN-SYSTEM.md           # Design system master index
├── AGENTS.user.md             # AI agent behavior rules & constraints
├── TODO.md                    # Project todo list (auto-managed by agents)
│
├── adminpanel/                # B2B SaaS Admin Panel design specs (7 styles)
│   ├── DESIGN.neumorphism.md
│   ├── neumorphism.preview.html
│   ├── DESIGN.glassmorphism.md
│   ├── glassmorphism.preview.html
│   ├── DESIGN.cyberpunk.md
│   ├── cyberpunk.preview.html
│   ├── DESIGN.claymorphism.md
│   ├── claymorphism.preview.html
│   ├── DESIGN.minimalism.md
│   ├── minimalism.preview.html
│   ├── DESIGN.retro-futurism.md
│   ├── retro-futurism.preview.html
│   ├── DESIGN.aurora.md
│   └── aurora.preview.html
│
├── app/                       # C-end APP design specs (8 styles)
│   ├── DESIGN.claymorphism.md + claymorphism.preview.html
│   ├── DESIGN.aurora.md + aurora.preview.html
│   ├── DESIGN.y2k.md + y2k.preview.html
│   ├── DESIGN.minimalism.md + minimalism.preview.html
│   ├── DESIGN.neumorphism.md + neumorphism.preview.html
│   ├── DESIGN.cyberpunk.md + cyberpunk.preview.html
│   ├── DESIGN.micro-gradient.md + micro-gradient.preview.html
│   └── DESIGN.rounded-card.md + rounded-card.preview.html
│
└── website/                   # Website design specs (8 styles)
    ├── DESIGN.aurora.md + aurora.preview.html
    ├── DESIGN.bento.md + bento.preview.html
    ├── DESIGN.apple-minimal.md + apple-minimal.preview.html
    ├── DESIGN.big-type.md + big-type.preview.html
    ├── DESIGN.brutalism.md + brutalism.preview.html
    ├── DESIGN.3d-parallax.md + 3d-parallax.preview.html
    ├── DESIGN.magazine.md + magazine.preview.html
    └── DESIGN.dark-cyber.md + dark-cyber.preview.html
```

## Usage

- **For AI Assistants**: Read `AGENTS.user.md` before starting any task. Follow all 6 rules strictly.
- **For Developers**: Reference `DESIGN-SYSTEM.md` to find the right style for your product type, then check the corresponding `DESIGN.{style}.md` for implementation details.
- **For Project Tracking**: Agents auto-update `TODO.md` with `PENDING` / `IN_PROGRESS` / `COMPLETED` statuses.

## Design Style Quick Reference

### B2B / SaaS (7 styles)

| # | Style | File | Preview |
|---|-------|------|---------|
| 1 | **Neumorphism** | [adminpanel/DESIGN.neumorphism.md](adminpanel/DESIGN.neumorphism.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/adminpanel/neumorphism.preview.html) |
| 2 | **Glassmorphism** | [adminpanel/DESIGN.glassmorphism.md](adminpanel/DESIGN.glassmorphism.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/adminpanel/glassmorphism.preview.html) |
| 3 | **Cyberpunk** | [adminpanel/DESIGN.cyberpunk.md](adminpanel/DESIGN.cyberpunk.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/adminpanel/cyberpunk.preview.html) |
| 4 | **Claymorphism** | [adminpanel/DESIGN.claymorphism.md](adminpanel/DESIGN.claymorphism.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/adminpanel/claymorphism.preview.html) |
| 5 | **Minimalism** | [adminpanel/DESIGN.minimalism.md](adminpanel/DESIGN.minimalism.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/adminpanel/minimalism.preview.html) |
| 6 | **Retro Futurism** | [adminpanel/DESIGN.retro-futurism.md](adminpanel/DESIGN.retro-futurism.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/adminpanel/retro-futurism.preview.html) |
| 7 | **Aurora Gradient** | [adminpanel/DESIGN.aurora.md](adminpanel/DESIGN.aurora.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/adminpanel/aurora.preview.html) |

### C-end APP (8 styles)

| # | Style | File | Preview |
|---|-------|------|---------|
| 1 | **Claymorphism** | [app/DESIGN.claymorphism.md](app/DESIGN.claymorphism.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/app/claymorphism.preview.html) |
| 2 | **Aurora** | [app/DESIGN.aurora.md](app/DESIGN.aurora.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/app/aurora.preview.html) |
| 3 | **Y2K Retro** | [app/DESIGN.y2k.md](app/DESIGN.y2k.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/app/y2k.preview.html) |
| 4 | **Minimalism** | [app/DESIGN.minimalism.md](app/DESIGN.minimalism.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/app/minimalism.preview.html) |
| 5 | **Neumorphism** | [app/DESIGN.neumorphism.md](app/DESIGN.neumorphism.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/app/neumorphism.preview.html) |
| 6 | **Cyberpunk** | [app/DESIGN.cyberpunk.md](app/DESIGN.cyberpunk.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/app/cyberpunk.preview.html) |
| 7 | **Micro Gradient** | [app/DESIGN.micro-gradient.md](app/DESIGN.micro-gradient.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/app/micro-gradient.preview.html) |
| 8 | **Rounded Card** | [app/DESIGN.rounded-card.md](app/DESIGN.rounded-card.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/app/rounded-card.preview.html) |

### Website (8 styles)

| # | Style | File | Preview |
|---|-------|------|---------|
| 1 | **Aurora** | [website/DESIGN.aurora.md](website/DESIGN.aurora.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/website/aurora.preview.html) |
| 2 | **Bento Grid** | [website/DESIGN.bento.md](website/DESIGN.bento.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/website/bento.preview.html) |
| 3 | **Apple Minimal** | [website/DESIGN.apple-minimal.md](website/DESIGN.apple-minimal.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/website/apple-minimal.preview.html) |
| 4 | **Big Typography** | [website/DESIGN.big-type.md](website/DESIGN.big-type.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/website/big-type.preview.html) |
| 5 | **Neo Brutalism** | [website/DESIGN.brutalism.md](website/DESIGN.brutalism.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/website/brutalism.preview.html) |
| 6 | **3D Parallax** | [website/DESIGN.3d-parallax.md](website/DESIGN.3d-parallax.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/website/3d-parallax.preview.html) |
| 7 | **Magazine Grid** | [website/DESIGN.magazine.md](website/DESIGN.magazine.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/website/magazine.preview.html) |
| 8 | **Dark Cyber** | [website/DESIGN.dark-cyber.md](website/DESIGN.dark-cyber.md) | [Preview](https://wraithn.github.io/awesome-aicoding-designnrules/website/dark-cyber.preview.html) |

## Style Selection Guide

| Product Type | B2B Recommended | APP Recommended | Website Recommended |
|-------------|-----------------|-----------------|---------------------|
| AI / SaaS | Aurora + Glassmorphism | Aurora | Aurora / Bento |
| B2B Enterprise | Minimalism + Aurora | Minimalism | Apple Minimal / Magazine |
| B2C Consumer | Claymorphism | Claymorphism / Rounded Card | Bento / Big Typography |
| Web3 / Metaverse | Glassmorphism + Cyberpunk | Cyberpunk | Dark Cyber |
| Gaming | Cyberpunk | Cyberpunk | 3D Parallax |
| Luxury / High-end | Minimalism | Minimalism | Apple Minimal |
| Lifestyle | — | Rounded Card | Magazine |
| Tools / Efficiency | Neumorphism + Aurora | Micro Gradient / Neumorphism | Bento |

> **Tip:** Open the [Design System Index](DESIGN-SYSTEM.md) for the complete cross-terminal style mapping and detailed selection guide.

---
