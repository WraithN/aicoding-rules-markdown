# APP 08｜Rounded Healing Card Style

> **Recommendation**: ⭐⭐⭐⭐⭐
> **Representatives**: Coze / Tide / Little Sleep / Meditation Apps
> 
> 

## Use Cases

Meditation apps, sleep aids, mental health, lifestyle, pet apps. Extremely rounded, healing color palette, non-aggressive.

## Design Philosophy

Extra large border radius (nearly circular), soft healing color palette (low-saturation pink, blue, green), no sharp elements, creating a sense of safety and healing.

## Core Characteristics

- ✅ Extra large border radius cards (24-32px)
- ✅ Healing color palette: low-saturation pink, blue, green, off-white
- ✅ No right angles, no sharp lines
- ✅ Large spacing, abundant white space
- ✅ Soft illustration-style icons

## Color System

```Plain Text
Background:       #FFF9F5 (Warm Off-White)
Card:             #FFFFFF
Healing Pink:     #FFB5B5
Healing Blue:     #B5D8FF
Healing Green:    #B5E4CA
Healing Yellow:   #FFE4B5
Primary Text:     #4A4A4A
Secondary Text:   #9A9A9A
```

## Core CSS

```css
.heal-bg {
  background: #FFF9F5;
  min-height: 100vh;
}

.heal-card {
  background: #FFFFFF;
  border-radius: 28px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.04);
  padding: 24px;
}

.heal-btn {
  background: #FFB5B5;
  border-radius: 24px;
  color: #FFFFFF;
  padding: 14px 32px;
  font-weight: 600;
  box-shadow: 0 4px 12px rgba(255, 181, 181, 0.3);
}

.heal-tag {
  background: #B5D8FF;
  border-radius: 20px;
  padding: 6px 16px;
  font-size: 12px;
  color: #4A4A4A;
}

.heal-avatar {
  width: 56px;
  height: 56px;
  border-radius: 50%;
  background: linear-gradient(135deg, #FFB5B5, #B5D8FF);
}
```

## Component Specifications

- **Card Border Radius**: 28-32px
- **Button Border Radius**: 24px (nearly pill-shaped)
- **Color Palette**: Low-saturation warm tones as primary
- **Spacing**: Large spacing, strong breathing room
- **Icons**: Rounded illustration style, avoid linear icons
- **Applicable To**: Meditation, sleep, mental health, lifestyle, pets

---
