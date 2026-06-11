# Website 04 | Full-Screen Oversized Typography Impact Style

> **Rating**: ⭐⭐⭐⭐
> **Representatives**: Brand Launch Events / New Product Landing Pages / Personal Portfolios
> 
> 

## Applicable Scenarios

Brand launch events, new product landing pages, personal portfolios, creative studios, marketing single pages.

## Design Philosophy

Text as the visual protagonist. Oversized fonts dominate the screen, weakening images while strengthening the emotional impact of text. Minimalist, bold, and extremely memorable.

## Core Characteristics

- Single oversized headline on the first screen, occupying the visual center
- Minimal navigation, no redundant elements
- One screen per theme, scrolling switches content
- Strong font weight contrast
- Minimal background to highlight text

## Typography Specifications

```Plain Text
Hero Main Title: 80~120px (clamp(60px, 12vw, 110px))
Subtitle: 24~32px
Body: 16px
```

## Colors

Black and white as primary colors + single high-saturation accent

## Core CSS

```css
.big-title {
  font-size: clamp(60px, 12vw, 110px);
  font-weight: 700;
  line-height: 1;
  letter-spacing: -0.03em;
}

.big-section {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0 24px;
}
```

## Advantages

Top-tier visual impact, super strong brand memorability, suitable for creative and launch event official websites

---
