# Website 01 | Aurora Diffusion Style

> **Rating**: ⭐⭐⭐⭐⭐
> **Representatives**: Linear / Notion / OpenAI
> **2026 Top Trending Mainstream Style**
> 
> 

## Applicable Scenarios

AI official websites, SaaS, tech brands, developer tools. Low-saturation multi-layer radial glow diffusion, clean center, soft light around the edges.

## Design Philosophy

Low-saturation multi-layer radial glow diffusion, clean center with soft surrounding light, combined with glassmorphism and micro-animations. Restrained, premium, tech-elegant, and gentle — comfortable for long browsing sessions without fatigue.

## Core Characteristics

- Four layers of low-saturation gradient glow, fixed background
- Frosted glass semi-transparent cards + thin white borders
- Purple/blue/cyan flowing gradients
- Soft light shadows, no hard drop shadows
- Global refined hover animations

## Color System

```Plain Text
Aurora Purple: #7877C6
Aurora Blue: #5B8DEF
Aurora Cyan: #3CC8C8
Aurora Pink: #E879F9
Background: #FAFAFA
Primary Text: #171717
Secondary Text: #737373
```

## Core CSS

```css
.aurora-bg {
  background: 
    radial-gradient(ellipse 80% 50% at 20% -20%, rgba(120, 119, 198, 0.3), transparent),
    radial-gradient(ellipse 60% 40% at 80% 0%, rgba(91, 141, 239, 0.25), transparent),
    radial-gradient(ellipse 50% 60% at 110% 90%, rgba(60, 200, 200, 0.2), transparent),
    radial-gradient(ellipse 50% 40% at -10% 70%, rgba(232, 121, 249, 0.15), transparent),
    #FAFAFA;
  background-attachment: fixed;
}

.glass {
  background: rgba(255, 255, 255, 0.7);
  backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.8);
  border-radius: 24px;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.03), 0 4px 16px rgba(0, 0, 0, 0.04);
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

.glass:hover {
  transform: translateY(-4px);
  background: rgba(255, 255, 255, 0.9);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.06), 0 12px 40px rgba(120, 119, 198, 0.1);
}

.btn-aurora {
  background: linear-gradient(135deg, #7877C6, #5B8DEF, #3CC8C8);
  background-size: 200% 200%;
  transition: all 0.3s ease;
}

.btn-aurora:hover {
  background-position: 100% 100%;
  transform: translateY(-2px);
}

.text-aurora {
  background: linear-gradient(135deg, #7877C6, #5B8DEF);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
```

## Component Specifications

- **Cards**: 24px border-radius, blur 20, semi-transparent white background
- **Buttons**: 200% gradient size flowing on hover
- **Animations**: cubic-bezier(0.4,0,0.2,1) 300ms

## Adaptation

Light mode by default, dark mode reduces glow opacity

---
