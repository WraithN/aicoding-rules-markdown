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
