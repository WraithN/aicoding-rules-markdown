# APP 05｜Soft Neumorphism Soft Light Style

> **Recommendation**: ⭐⭐⭐⭐
> **Representatives**: Calculator Tools / Music Players / Smart Home Control Panels
> 
> 

## Use Cases

Utility apps, smart home control, music players, calculators. Softer than traditional neumorphism, adapted to modern app interfaces.

## Design Philosophy

Creates a relief texture through light and dark shadows on a same-color-family background. Softened treatment reduces visual fatigue, adapted to high-frequency mobile usage scenarios.

## Core Characteristics

- ✅ Same-color-family light and dark shadows (no high contrast)
- ✅ Soft border radius 16-24px
- ✅ Button press indentation feedback
- ✅ Low-saturation color scheme, not tiring for long-term use

## Color System

```Plain Text
Background:    #E8ECF1
Light Shadow:  #FFFFFF
Dark Shadow:   #C5CDD7
Text Color:    #5A6578
Primary Color: #7877C6 (Soft Purple)
```

## Core CSS

```css
.neo-app-card {
  background: #E8ECF1;
  border-radius: 20px;
  box-shadow: 
    6px 6px 12px #C5CDD7, 
    -6px -6px 12px #FFFFFF;
  padding: 20px;
}

.neo-app-btn {
  background: #E8ECF1;
  border-radius: 16px;
  box-shadow: 
    4px 4px 8px #C5CDD7, 
    -4px -4px 8px #FFFFFF;
  transition: all 0.2s ease;
}

.neo-app-btn:active {
  box-shadow: 
    inset 3px 3px 6px #C5CDD7, 
    inset -3px -3px 6px #FFFFFF;
}

.neo-app-input {
  background: #E8ECF1;
  border-radius: 12px;
  box-shadow: 
    inset 3px 3px 6px #C5CDD7, 
    inset -3px -3px 6px #FFFFFF;
  border: none;
  padding: 12px 16px;
}
```

## Component Specifications

- **Border Radius**: 16-24px (cards) / 12-16px (buttons)
- **Shadow Offset**: 4-6px
- **Shadow Blur**: 8-12px
- **Pressed State**: inset shadow replaces outer shadow
- **Applicable To**: Utility apps, smart home, music players, control panels

---
