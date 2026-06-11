# Website 05 | Neo Brutalism

> **Rating**: ⭐⭐⭐
> **Representatives**: Streetwear Brands / Designer Personal Sites / Art Studios
> 
> 

## Applicable Scenarios

Streetwear brands, designer personal sites, art studios, Gen Z creative products.

## Design Philosophy

Anti-refinement, anti-mainstream soft aesthetics. Thick black outlines, high-saturation color clashes, offset shadows, pixel-style typography. Bold personality, youthful rebellion.

## Core Characteristics

- 2~3px thick solid black outlines
- Offset floating shadows (no blur, solid projection)
- High-saturation solid color blocks, no gradients
- Irregular typography, slight misalignment
- No border-radius / small border-radius

## Colors

```Plain Text
Bright Yellow: #FFE500
Vivid Blue: #0066FF
Orange Red: #FF6B35
Pure Black: #000000
Pure White: #FFFFFF
```

## Core CSS

```css
.brutal-card {
  border: 2px solid #000;
  box-shadow: 6px 6px 0 #000;
  transition: all 0.2s ease;
}

.brutal-card:hover {
  transform: translate(-2px, -2px);
  box-shadow: 8px 8px 0 #000;
}

.brutal-btn {
  border: 2px solid #000;
  box-shadow: 4px 4px 0 #000;
  transition: all 0.2s ease;
}

.brutal-btn:hover {
  transform: translate(-2px, -2px);
  box-shadow: 6px 6px 0 #000;
}

.brutal-yellow { background: #FFE500; }
.brutal-blue { background: #0066FF; color: white; }
.brutal-orange { background: #FF6B35; color: white; }
```

## Component Specifications

- **Cards**: Solid outline + bottom-right offset shadow
- **Buttons**: Thick borders + solid fill
- **Fonts**: Bold sans-serif, bold and powerful

## Advantages

Extremely memorable, youthful, niche premium, suitable for trendy brands

---
