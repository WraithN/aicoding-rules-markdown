# Website 03 | Apple Minimal White Space Premium Style

> **Rating**: ⭐⭐⭐⭐⭐
> **Representatives**: Apple Official Website / Airbnb / Arcade.studio
> 
> 

## Applicable Scenarios

Premium brands, digital hardware, luxury goods, architectural design, art studios, high-end boutique hotels.

## Design Philosophy

Less is More. Extra-large white space, minimal elements, strong font weight contrast. Remove all decorations, use white space and typography to create a luxurious, premium feel.

## Core Features

- Global extra-large spacing (1.5~2x conventional design)
- Pure black, white, and gray system, minimal accent colors
- Strong font weight hierarchy: bold headings, thin body text
- No border-radius / minimal border-radius
- No complex shadows, no gradient stacking

## Color System

```Plain Text
Pure Black: #000000
Dark Gray: #1A1A1A
Medium Gray: #666666
Light Gray: #999999
Border Gray: #E5E5E5
Pure White: #FFFFFF
```

## Typography Specifications

```Plain Text
H1: 64~80px / 600 / 1.1 line-height / -0.02 letter-spacing
H2: 32~40px / 500 / 1.2 line-height
Body: 16~18px / 400 / 1.6 line-height
```

## Core CSS

```css
.apple-h1 {
  font-size: clamp(48px, 6vw, 80px);
  font-weight: 600;
  line-height: 1.1;
  letter-spacing: -0.02em;
}

.apple-section {
  padding: 120px 0;
}

.btn-black {
  background: #000;
  color: #fff;
  border-radius: 9999px;
  padding: 18px 40px;
  transition: opacity 0.2s;
}

.btn-black:hover {
  opacity: 0.8;
}

.btn-line {
  border: 1px solid #e5e5e5;
  border-radius: 9999px;
  padding: 18px 40px;
  background: transparent;
}
```

---
