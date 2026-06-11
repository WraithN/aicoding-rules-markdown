# APP 02｜Aurora Diffusion / Aurora Glassmorphism

> **Recommendation**: ⭐⭐⭐⭐⭐
> **Representatives**: Linear Mobile / Notion AI / ChatGPT
> **Top Choice for AI / Tool Apps**
> 
> 

## Use Cases

AI tools, productivity apps, finance, and tech mobile platforms. Lightweight aurora soft glow + low-blur glass cards—transparent, airy, and tech-premium.

## Design Philosophy

Low-saturation gradient halos + frosted glass cards + soft shadows. The standard configuration for AI products.

## Core Characteristics

- ✅ Purple-blue-cyan low-saturation gradient background
- ✅ Semi-transparent frosted glass cards
- ✅ Tri-color flowing gradient buttons
- ✅ Subtle yet premium feel
- ✅ Not heavy, eye-friendly, suitable for high-frequency app usage

## Color System

```Plain Text
Aurora Purple: #7877C6
Aurora Blue:   #5B8DEF
Aurora Cyan:   #3CC8C8
Background:    #FAFAFA + radial gradient
```

## Core CSS

```css
/* Lightweight aurora background for mobile */
.aurora-bg {
  background: 
    radial-gradient(ellipse 60% 40% at 10% 0%, rgba(120, 119, 198, 0.2), transparent),
    radial-gradient(ellipse 60% 40% at 90% 100%, rgba(91, 141, 239, 0.15), transparent),
    #FAFAFA;
}

/* Mobile glass card - lightweight blur */
.app-glass {
  background: rgba(255, 255, 255, 0.6);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  border: 1px solid rgba(255, 255, 255, 0.7);
  border-radius: 20px;
  transition: all 0.2s ease;
}

/* Gradient button */
.btn-gradient {
  background: linear-gradient(135deg, #7877C6, #5B8DEF, #3CC8C8);
  border-radius: 12px;
  color: white;
}

/* Focus soft glow border */
.focus-glow:focus {
  outline: none;
  box-shadow: 0 0 0 4px rgba(120, 119, 198, 0.15);
}
```

## Component Specifications

- **Blur**: 12px (optimal performance on mobile)
- **Card Transparency**: 0.6
- **Border Radius**: 20px
- **Focus Soft Glow Border**: 4px primary color halo
- **Card Border Radius**: 20px
- **Button Border Radius**: 12px
- **Applicable To**: AI tool apps, productivity apps, SaaS mobile, developer tools

## APP Adaptation Guidelines

- Optimize backdrop-filter performance on mobile (use 12px instead of 20px)
- Reduce card transparency to 0.6 to ensure content readability
- Use lightweight glass effect for the navigation bar
- Use tri-color gradient for buttons with background shift animation on hover

---
