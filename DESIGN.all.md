# Complete UI Design Style Specifications

> Covers the 7 mainstream design styles of 2026

---

## Table of Contents

1. [Neumorphism](#1-neumorphism)
2. [Glassmorphism](#2-glassmorphism)
3. [Cyberpunk](#3-cyberpunk)
4. [Claymorphism](#4-claymorphism)
5. [Minimalism](#5-minimalism)
6. [Retro Futurism](#6-retro-futurism)
7. [Aurora Gradient](#7-aurora-gradient) ✅ **Highly Recommended**

---

# 1\. Neumorphism

> Soft UI / Embossed Effect / Trending since 2020
> 
> 

## Design Philosophy

Light and dark shadows in the same color family create an embossed, pressable feel that is soft and easy on the eyes. **Drawback: low contrast, poor accessibility; not recommended for large-area use**

## Color System

```Plain Text
Background: #E0E5EC
Light shadow: #FFFFFF
Dark shadow: #A3B1C6
Text color: #4A5568
```

## Core CSS

```css
.neo-card {
  background: #E0E5EC;
  box-shadow: 8px 8px 16px #A3B1C6, -8px -8px 16px #FFFFFF;
  border-radius: 20px;
}

.neo-btn {
  background: #E0E5EC;
  box-shadow: 6px 6px 12px #A3B1C6, -6px -6px 12px #FFFFFF;
  border-radius: 12px;
}

.neo-btn:active, .neo-btn.active {
  box-shadow: inset 4px 4px 8px #A3B1C6, inset -4px -4px 8px #FFFFFF;
}

.neo-input {
  background: #E0E5EC;
  box-shadow: inset 4px 4px 8px #A3B1C6, inset -4px -4px 8px #FFFFFF;
  border-radius: 10px;
}
```

## Component Guidelines

- **Border radius**: 12\-20px

- **Button states**: Raised by default, indented when pressed

- **Best for**: Players, control panels, widgets

- **Not suitable for**: Long text, data tables

---

---

# 2\. Glassmorphism

> Frosted glass / Transparent / Mainstream since 2021
> 
> 

## Design Philosophy

Semi-transparent background + blur + thin border creates a sense of layering and depth. A favorite in iOS and Web3 projects

## Color System

```Plain Text
White glass: rgba(255, 255, 255, 0.25)
Dark glass: rgba(15, 23, 42, 0.7)
Border color: rgba(255, 255, 255, 0.18)
Background blur: blur(20px)
```

## Core CSS

```css
.glass-card {
  background: rgba(255, 255, 255, 0.25);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.18);
  box-shadow: 0 8px 32px rgba(31, 38, 135, 0.15);
  border-radius: 16px;
}

.glass-dark {
  background: rgba(15, 23, 42, 0.7);
  backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.1);
}
```

## Component Guidelines

- **Blur amount**: 12\-20px

- **Transparency**: 0\.2\-0\.3 (light) / 0\.6\-0\.8 (dark)

- **Background**: Must be paired with a colorful gradient background

- **Best for**: Modals, sidebars, cards, Web3 wallets

---

---

# 3\. Cyberpunk

> Neon / Glitch Art / High Contrast / Gaming Style
> 
> 

## Design Philosophy

High-saturation neon colors, glow effects, beveled corners, scanlines. Suitable for games, tech, and metaverse projects

## Color System

```Plain Text
Neon Pink: #FF2A6D
Neon Cyan: #05D9E8
Neon Purple: #D300C5
Neon Yellow: #FEE800
Dark Base: #120458
```

## Core CSS

```css
.cyber-glow {
  text-shadow: 0 0 10px currentColor, 
               0 0 20px currentColor, 
               0 0 40px currentColor;
}

.cyber-border {
  border: 1px solid #05D9E8;
  box-shadow: 0 0 5px #05D9E8, 
              inset 0 0 5px rgba(5, 217, 232, 0.1);
}

.cyber-btn {
  background: linear-gradient(135deg, #FF2A6D, #D300C5);
  box-shadow: 0 0 20px rgba(255, 42, 109, 0.5);
  clip-path: polygon(10px 0, 100% 0, 
                     100% calc(100% - 10px), 
                     calc(100% - 10px) 100%, 
                     0 100%, 0 10px);
}

.scanline {
  background: linear-gradient(transparent 50%, 
                rgba(5, 217, 232, 0.03) 50%);
  background-size: 100% 4px;
  pointer-events: none;
}
```

## Component Guidelines

- **Glow Effect**: Multi-layered text-shadow / box-shadow

- **Beveled Corners**: clip-path angled shapes

- **Scanlines**: Background stripe overlay

- **Use Cases**: Game interfaces, metaverse, hacker themes, music festivals

---

---

# 4\. Claymorphism

> Rounded / 3D Soft Texture / Emerged in 2022 ✅ **Recommended**
> 
> 

## Design Philosophy

Large rounded corners, double-layer shadows, light backgrounds, inflated feel. Higher contrast than neumorphism, more friendly and lively

## Color System

```Plain Text
Background: #F0F4F8
Card: #FFFFFF / #F7FAFC
Shadow: rgba(13, 37, 72, 0.12)
Inner Highlight: rgba(255, 255, 255, 0.9)
```

## Core CSS

```css
.clay-card {
  background: #F0F4F8;
  border-radius: 24px;
  box-shadow: 
    0 12px 24px rgba(13, 37, 72, 0.12), 
    0 -4px 12px rgba(255, 255, 255, 0.8),
    inset 0 2px 4px rgba(255, 255, 255, 0.9);
  border: 1px solid rgba(255, 255, 255, 0.9);
}

.clay-btn {
  background: linear-gradient(145deg, #FFFFFF, #E6E9EF);
  border-radius: 16px;
  box-shadow: 
    4px 4px 10px rgba(13, 37, 72, 0.15), 
    -2px -2px 8px rgba(255, 255, 255, 0.9);
  transition: all 0.2s;
}

.clay-btn:active {
  box-shadow: 
    inset 2px 2px 5px rgba(13, 37, 72, 0.1), 
    inset -2px -2px 5px rgba(255, 255, 255, 0.8);
}
```

## Component Guidelines

- **Large Rounded Corners**: 16-24px

- **Double-layer Shadows**: Outer shadow + inner highlight

- **Inflated Feel**: Create 3D bulge through light and shadow

- **Use Cases**: Consumer-facing apps, children's products, consumer-grade tools

---

---

# 5. Minimalism

> Generous white space / Ultimate simplicity / Premium feel
> 
> 

## Design Philosophy

Generous white space, ultra-thin borders, neutral tones, large typography. Representative style of brands like Apple and Notion.

## Color System

```Plain Text
Pure Black: #000000
Dark Gray: #1A1A1A
Medium Gray: #666666
Light Gray: #999999
Ultra Light Gray: rgba(0, 0, 0, 0.08)
Background: #FFFFFF
```

## Core CSS

```css
.minimal-border {
  border: 0.5px solid rgba(0, 0, 0, 0.08);
}

.minimal-input {
  border: none;
  border-bottom: 1px solid #E5E5E5;
  border-radius: 0;
  background: transparent;
}

.minimal-input:focus {
  border-bottom-color: #000000;
  outline: none;
}

.minimal-btn {
  background: #000000;
  color: #FFFFFF;
  border-radius: 9999px;
  padding: 16px 32px;
  font-weight: 500;
}

.minimal-btn-secondary {
  background: transparent;
  color: #000000;
  border: 1px solid #E5E5E5;
  border-radius: 9999px;
}
```

## Component Guidelines

- **White space priority**: Spacing is 1.5–2× that of standard designs

- **Ultimate simplicity**: Remove all unnecessary decoration

- **Font weight contrast**: Three-level distinction with Light / Regular / Bold

- **Best for**: Premium brands, art projects, luxury websites

---

---

# 6. Retro Futurism

> 80s retro / Vaporwave / Gradient grid / Y2K
> 
> 

## Design Philosophy

High-saturation gradients, grids, retro computer fonts, neon. A revival of Y2K aesthetics.

## Color System

```Plain Text
Coral Red: #FF6B6B
Lemon Yellow: #FECA57
Sky Blue: #48DBFB
Cherry Blossom Pink: #FF9FF3
```

## Core CSS

```css
.retro-gradient {
  background: linear-gradient(135deg, 
    #FF6B6B, #FECA57, #48DBFB, #FF9FF3);
  background-size: 400% 400%;
  animation: gradientShift 8s ease infinite;
}

@keyframes gradientShift {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}

.retro-grid {
  background-image: 
    linear-gradient(rgba(255,107,107,0.1) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,107,107,0.1) 1px, transparent 1px);
  background-size: 20px 20px;
}

.retro-text {
  background: linear-gradient(135deg, #FF6B6B, #48DBFB);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  font-weight: 900;
  letter-spacing: -0.02em;
}
```

## Component Guidelines

- **Gradient flow**: Slow animated background colors

- **Grid backgrounds**: Perspective grids / flat grids

- **Bold type**: Black / Heavy font weights

- **Best for**: Brand marketing pages, music festivals, streetwear websites

---

---

# 7. Aurora Gradient

> Diffused gradients / Soft halos / 2026's hottest trend ✅ **Highly Recommended**
> 
> 

## Design Philosophy

Multi-layered radial gradient overlays, smooth color transitions, low saturation. Adopted comprehensively by Linear and Notion AI, **the most premium design language available today**

## Color System (Morandi Low Saturation)

```Plain Text
Aurora Purple: #7877C6
Aurora Blue: #5B8DEF
Aurora Cyan: #3CC8C8
Aurora Pink: #E879F9
Background: #FAFAFA
```

## Core CSS

```css
/* Four-layer aurora background */
.aurora-bg {
  background: 
    radial-gradient(ellipse 80% 50% at 20% -20%, rgba(120, 119, 198, 0.3), transparent),
    radial-gradient(ellipse 60% 40% at 80% 0%, rgba(91, 141, 239, 0.25), transparent),
    radial-gradient(ellipse 50% 60% at 110% 90%, rgba(60, 200, 200, 0.2), transparent),
    radial-gradient(ellipse 50% 40% at -10% 70%, rgba(232, 121, 249, 0.15), transparent),
    #FAFAFA;
  background-attachment: fixed;
}

/* Enhanced glassmorphism */
.glass-aurora {
  background: rgba(255, 255, 255, 0.7);
  backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.8);
  box-shadow: 
    0 1px 2px rgba(0, 0, 0, 0.03),
    0 4px 16px rgba(0, 0, 0, 0.04),
    0 8px 32px rgba(120, 119, 198, 0.04);
  transition: all 0.2s cubic-bezier(0.4, 0, 0.2, 1);
}

.glass-aurora:hover {
  background: rgba(255, 255, 255, 0.85);
  transform: translateY(-1px);
}

/* Tri-color flowing gradient button */
.btn-aurora {
  background: linear-gradient(135deg, #7877C6 0%, #5B8DEF 50%, #3CC8C8 100%);
  background-size: 200% 200%;
  box-shadow: 0 2px 8px rgba(120, 119, 198, 0.25);
  transition: all 0.3s ease;
}

.btn-aurora:hover {
  background-position: 100% 100%;
  transform: translateY(-1px);
}

/* Navigation active state */
.nav-aurora.active {
  background: rgba(120, 119, 198, 0.1);
  color: #7877C6;
}

/* Gradient divider */
.divider-aurora {
  height: 1px;
  background: linear-gradient(90deg, transparent, rgba(0, 0, 0, 0.05), transparent);
}

/* Breathing animation */
.status-pulse {
  animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}

@keyframes pulse {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.5; }
}
```

## Component Specifications

- **Border Radius**: 8px (navigation) / 12px (buttons) / 16-20px (cards)

- **Transition Curve**: `cubic-bezier(0.4, 0, 0.2, 1)`

- **Animation Duration**: 200-300ms

- **Best For**: AI products, SaaS tools, B2B systems, developer platforms ✅

---

# 🎯 Style Selection Guide

| Product Type | Recommended Style | Rationale |
|-------------|-------------------|-----------|
| **B2B / Enterprise** | Aurora Gradient + Glassmorphism | Professional, efficient, accessible |
| **B2C / Consumer** | Claymorphism | Friendly, lively, warm |
| **Web3 / Metaverse** | Glassmorphism + Cyberpunk | Tech-forward, futuristic |
| **Brand / Marketing** | Retro Futurism + Aurora Gradient | Strong visual impact |
| **AI / SaaS** | Aurora Gradient ✅ | Linear / Notion AI standard, timeless |
| **Luxury / High-end** | Minimalism | Premium feel, whitespace aesthetics |

---

## 2026 Best Practices

**Top Pick: Aurora Gradient**

- Timeless, at least 2–3 years ahead of the industry
- Great accessibility with sufficient contrast
- Perfect tech feel for the AI era
- Used by Linear, Vercel, and Notion AI
- Seamless light/dark mode switching

> *(Note: Portions of this document may be AI-generated.)*
