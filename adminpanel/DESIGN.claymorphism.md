# 4\. Claymorphism

> Rounded / 3D Soft Texture / Emerged in 2022 ✅ **Recommended**
> 
> 

## Design Philosophy

Large rounded corners, double-layer shadows, light backgrounds, inflated feel. Higher contrast than neumorphism, more friendly and lively

## Color System

```Plain Text
Background: #F0F4F8
Card: #FFFFFF / #F7FAFC
Shadow: rgba(13, 37, 72, 0.12)
Inner Highlight: rgba(255, 255, 255, 0.9)
```

## Core CSS

```css
.clay-card {
  background: #F0F4F8;
  border-radius: 24px;
  box-shadow: 
    0 12px 24px rgba(13, 37, 72, 0.12), 
    0 -4px 12px rgba(255, 255, 255, 0.8),
    inset 0 2px 4px rgba(255, 255, 255, 0.9);
  border: 1px solid rgba(255, 255, 255, 0.9);
}

.clay-btn {
  background: linear-gradient(145deg, #FFFFFF, #E6E9EF);
  border-radius: 16px;
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

## Component Guidelines

- **Large Rounded Corners**: 16-24px

- **Double-layer Shadows**: Outer shadow + inner highlight

- **Inflated Feel**: Create 3D bulge through light and shadow

- **Use Cases**: Consumer-facing apps, children's products, consumer-grade tools

---
