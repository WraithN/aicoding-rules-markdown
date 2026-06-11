# APP 04｜Minimalist White Space Lightweight Style

> **Recommendation**: ⭐⭐⭐⭐⭐
> **Representatives**: Apple Music / Airbnb / ByteDance New Products
> **Best User Experience**
> 
> 

## Use Cases

All iOS apps, productivity tools, content reading, and e-commerce apps. Extra large white space, thin font weight, no decoration.

## Design Philosophy

Extra large white space, thin font weight, no decoration. Official iOS design language.

## Core Characteristics

- ✅ Spacing is 1.5x that of standard design
- ✅ Abundant white space, strong breathing room
- ✅ Clear font weight contrast
- ✅ System native fonts

## Color System

```Plain Text
Pure Black:     #000000
Dark Gray:      #1C1C1E
Medium Gray:    #8E8E93
Light Gray:     #C7C7CC
Background White: #FFFFFF
System Blue:    #007AFF
```

## Core CSS

```css
.large-title {
  font-size: 34px;
  font-weight: 700;
  padding: 8px 20px 16px;
}

.list-item {
  background: #FFFFFF;
  padding: 12px 20px;
  border-bottom: 0.5px solid #C7C7CC;
}

.section-header {
  font-size: 13px;
  color: #8E8E93;
  text-transform: uppercase;
  letter-spacing: 0.02em;
  padding: 8px 20px;
}

.system-btn {
  color: #007AFF;
  font-size: 17px;
}

.minimal-card {
  background: #FFFFFF;
  border-radius: 12px;
  padding: 16px;
  margin: 8px 16px;
}
```

## Component Specifications

- **Border Radius**: 12px (cards) / 10px (buttons)
- **Spacing**: 1.5x standard spacing
- **Font**: System native fonts (-apple-system, San Francisco)
- **Dividers**: 0.5px light gray lines
- **Applicable To**: All iOS apps, productivity tools, content reading, e-commerce apps

---
