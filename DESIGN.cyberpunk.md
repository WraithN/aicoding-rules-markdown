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
