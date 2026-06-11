# APP 01｜Claymorphism Soft UI

> **Recommendation**: ⭐⭐⭐⭐⭐
> **Representatives**: Xiaohongshu New Version / Widgetable / Lensa
> **Top Choice for Consumer-Facing Apps**
> 
> 

## Use Cases

Consumer social, tool, lifestyle, and female-oriented apps. Extremely approachable, highest user acceptance, the hottest consumer app style in 2026.

## Design Philosophy

Large border radius + dual-layer shadows + inner highlights to create an inflated, soft 3D texture. Bouncy and healing, suitable for all ages.

## Core Characteristics

- ✅ Super large border radius 20-28px
- ✅ Dual-layer shadows: outer drop shadow + inner highlight
- ✅ Button press indentation for realistic physical feedback
- ✅ Soft inflated feel, bouncy and cute
- ✅ No sharp lines across the entire interface

## Color System

```Plain Text
Background:    #F0F4F8
Card:          #FFFFFF
Shadow:        rgba(13, 37, 72, 0.12)
Inner Highlight: rgba(255, 255, 255, 0.9)
```

## Core CSS

```css
.clay-card {
  background: #FFFFFF;
  border-radius: 24px;
  box-shadow: 
    0 12px 24px rgba(13, 37, 72, 0.12), 
    0 -4px 12px rgba(255, 255, 255, 0.8),
    inset 0 2px 4px rgba(255, 255, 255, 0.9);
  border: 1px solid rgba(255, 255, 255, 0.9);
}

.clay-btn {
  background: linear-gradient(145deg, #FFFFFF, #E6E9EF);
  border-radius: 20px;
  box-shadow: 
    4px 4px 10px rgba(13, 37, 72, 0.15), 
    -2px -2px 8px rgba(255, 255, 255, 0.9);
  transition: all 0.2s;
}

.clay-btn:active {
  box-shadow: 
    inset 2px 2px 5px rgba(13, 37, 72, 0.1), 
    inset -2px -2px 5px rgba(255, 255, 255, 0.8);
}
```

## Component Specifications

- **Card Border Radius**: 20-28px
- **Button Border Radius**: 16-20px
- **Press Feedback**: active state indentation
- **Normal raised, active indented**
- **Applicable To**: All consumer-facing apps, social, tools, female-oriented

## APP Adaptation Guidelines

- Use system safe area to adapt to notch screens
- Apply clay-card style to the bottom navigation bar
- Use 16-20px border radius for list items
- Minimum button tap area 44×44px

---
