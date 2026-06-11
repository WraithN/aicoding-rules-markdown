# APP 07｜Micro Gradient Lightweight Texture Style

> **Recommendation**: ⭐⭐⭐⭐
> **Representatives**: Bookkeeping Apps / Health Apps / Schedule Management Tools
> 
> 

## Use Cases

Bookkeeping apps, health apps, schedule management tools, lightweight utility apps. Subtle color transitions, light and non-greasy.

## Design Philosophy

Adopts extremely subtle gradient transitions (rather than strong contrast), paired with lightweight shadows and thin borders, creating a premium feel while keeping the interface clean and fresh.

## Core Characteristics

- ✅ Micro gradient background (same color family 5% difference)
- ✅ Ultra-light shadows (y: 2px, blur: 8px, opacity: 0.06)
- ✅ Thin borders (0.5px or 1px light gray)
- ✅ Border radius 12-16px
- ✅ Icons use linear gradient fill

## Color System

```Plain Text
Background Gradient: #FAFBFC → #F5F6F8
Card Background:     #FFFFFF
Primary Color:       #6366F1 (Indigo)
Secondary Colors:    #8B5CF6 (Purple) / #10B981 (Green)
Primary Text:        #1F2937
Secondary Text:      #6B7280
Border Color:        rgba(0,0,0,0.06)
Shadow Color:        rgba(0,0,0,0.06)
```

## Core CSS

```css
.micro-bg {
  background: linear-gradient(180deg, #FAFBFC 0%, #F5F6F8 100%);
  min-height: 100vh;
}

.micro-card {
  background: #FFFFFF;
  border-radius: 16px;
  border: 0.5px solid rgba(0, 0, 0, 0.06);
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  padding: 16px;
}

.micro-btn {
  background: linear-gradient(135deg, #6366F1, #8B5CF6);
  border-radius: 12px;
  color: white;
  box-shadow: 0 2px 8px rgba(99, 102, 241, 0.25);
}

.micro-icon {
  background: linear-gradient(135deg, #6366F1, #8B5CF6);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
```

## Component Specifications

- **Card Border Radius**: 16px
- **Button Border Radius**: 12px
- **Shadow**: Ultra-light, almost invisible but provides hierarchy
- **Border**: 0.5px light gray, adds a refined feel
- **Gradient Angle**: 135° or 180°
- **Applicable To**: Bookkeeping, health, schedules, lightweight tools

---
