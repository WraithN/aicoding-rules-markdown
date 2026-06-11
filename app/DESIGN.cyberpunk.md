# APP 06｜Dark Neon Cyberpunk App Style

> **Recommendation**: ⭐⭐⭐
> **Representatives**: Genshin Impact / Honkai: Star Rail / Game Apps
> 
> 

## Use Cases

Game apps, ACG (anime, comic, game) communities, tech media, geek tools. Dark base + neon glowing text + cyberpunk elements.

## Design Philosophy

Dark base + neon glowing text + cyberpunk elements. Standard for games and ACG.

## Core Characteristics

- ✅ Pure black / dark gray base
- ✅ Glowing text with text-shadow
- ✅ High-saturation neon colors (pink / cyan / purple)
- ✅ Scanline effect

## Color System

```Plain Text
Dark Base:     #0A0A0F
Neon Pink:     #FF2A6D
Neon Cyan:     #05D9E8
Neon Purple:   #D300C5
```

## Core CSS

```css
.cyber-app-bg {
  background: #0A0A0F;
  color: #E5E5E5;
}

.cyber-glow {
  text-shadow: 
    0 0 10px currentColor, 
    0 0 20px currentColor, 
    0 0 40px currentColor;
}

.cyber-border {
  border: 1px solid #05D9E8;
  box-shadow: 
    0 0 5px #05D9E8, 
    inset 0 0 5px rgba(5, 217, 232, 0.1);
}

.cyber-card {
  background: rgba(20, 20, 30, 0.8);
  border: 1px solid rgba(5, 217, 232, 0.2);
  border-radius: 16px;
  backdrop-filter: blur(10px);
}

.scanline {
  background: linear-gradient(transparent 50%, 
    rgba(5, 217, 232, 0.03) 50%);
  background-size: 100% 4px;
}
```

## Component Specifications

- **Base Color**: #0A0A0F pure black
- **Glow Colors**: Pink #FF2A6D / Cyan #05D9E8 / Purple #D300C5
- **Border**: 1px neon color + outer glow
- **Font**: Monospace / bold sans-serif
- **Applicable To**: Game apps, ACG communities, tech media, geek tools

---
