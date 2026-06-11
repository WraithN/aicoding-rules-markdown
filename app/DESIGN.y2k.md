# APP 03｜Y2K Millennium Retro Style

> **Recommendation**: ⭐⭐⭐
> **Representatives**: Jelly / Multiple New Social Products
> 
> 

## Use Cases

Social apps, photo / editing apps, streetwear communities, youth tools. Windows 95 texture, pixel fonts, millennium nostalgia aesthetics.

## Design Philosophy

Windows 95 texture, pixel fonts, millennium nostalgia aesthetics. Y2K revival.

## Core Characteristics

- ✅ Windows 95 gray 3D buttons
- ✅ Pixel fonts / dot matrix
- ✅ 2px raised borders (outer light, inner dark)
- ✅ High-saturation rainbow gradients

## Color System

```Plain Text
Win95 Gray:  #C0C0C0
Light Edge:  #FFFFFF
Dark Edge:   #808080
Gradient:    #FF6B6B → #48DBFB → #FF9FF3
```

## Core CSS

```css
.y2k-card {
  background: #C0C0C0;
  border: 2px solid;
  border-color: #FFFFFF #808080 #808080 #FFFFFF;
  border-radius: 4px;
}

.y2k-btn {
  background: #C0C0C0;
  border: 2px solid;
  border-color: #FFFFFF #808080 #808080 #FFFFFF;
  font-family: "MS Sans Serif", sans-serif;
  font-size: 12px;
  padding: 4px 12px;
}

.y2k-btn:active {
  border-color: #808080 #FFFFFF #FFFFFF #808080;
}

.y2k-gradient {
  background: linear-gradient(135deg, #FF6B6B, #48DBFB, #FF9FF3);
  background-size: 200% 200%;
  animation: gradientShift 4s ease infinite;
}

@keyframes gradientShift {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}
```

## Component Specifications

- **Border Style**: 2px 3D raised border
- **Font**: Pixel font / bold sans-serif
- **Color Palette**: Win95 gray + high-saturation rainbow gradient accents
- **Applicable To**: Social apps, photo / editing apps, streetwear communities, youth tools

---
