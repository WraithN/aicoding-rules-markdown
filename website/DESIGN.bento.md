# Website 02 | Bento Grid Modular Style

> **Rating**: ⭐⭐⭐⭐⭐
> **Representatives**: Linear / Raycast / Vercel
> **Official Mainstream Style**
> 
> 

## Applicable Scenarios

SaaS, developer tools, AI official websites, product landing pages.

## Design Philosophy

Breaks the rigid feel of uniform grids, adopting **varied-size modular cards**. One screen carries multi-dimensional information, with magazine-level layout that is premium and efficient.

## Core Characteristics

- 4-column flexible grid, supporting 2×2, 2×1, 1×1 span layouts
- Unified border-radius, unified glass texture, unified shadow system
- Staggered hierarchy, key sections enlarged for emphasis
- Unified floating hover animation
- Clear information zoning, no redundant elements

## Layout Specifications

```Plain Text
Grid Base: 4 columns desktop / 2 columns tablet / 1 column mobile
Spacing: grid-gap 20px
Card Border Radius: 28px
Padding: 24~32px
```

## Colors

Follows the Aurora low-saturation color system to ensure a premium tech feel

## Core CSS

```css
.bento-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
}

.bento-card {
  background: rgba(255, 255, 255, 0.7);
  backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.8);
  border-radius: 28px;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.03), 0 4px 16px rgba(0, 0, 0, 0.04);
  padding: 24px;
  transition: all 0.3s ease;
}

.bento-card:hover {
  transform: translateY(-4px);
  background: rgba(255, 255, 255, 0.9);
  box-shadow: 0 8px 24px rgba(120, 119, 198, 0.08);
}

/* Span layouts */
.bento-col-2 { grid-column: span 2; }
.bento-row-2 { grid-row: span 2; }
```

## Advantages

1. Core selling points displayed on one screen, reducing scrolling
2. Modular and freely expandable/reducible
3. Visually premium, big-tech quality
4. Adaptable to all tech independent websites

---
