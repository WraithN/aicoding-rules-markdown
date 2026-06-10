# 7. Aurora Gradient

> Diffused gradients / Soft halos / 2026's hottest trend ✅ **Highly Recommended**
> 
> 

## Design Philosophy

Multi-layered radial gradient overlays, smooth color transitions, low saturation. Adopted comprehensively by Linear and Notion AI, **the most premium design language available today**

## Color System (Morandi Low Saturation)

```Plain Text
Aurora Purple: #7877C6
Aurora Blue: #5B8DEF
Aurora Cyan: #3CC8C8
Aurora Pink: #E879F9
Background: #FAFAFA
```

## Core CSS

```css
/* Four-layer aurora background */
.aurora-bg {
  background: 
    radial-gradient(ellipse 80% 50% at 20% -20%, rgba(120, 119, 198, 0.3), transparent),
    radial-gradient(ellipse 60% 40% at 80% 0%, rgba(91, 141, 239, 0.25), transparent),
    radial-gradient(ellipse 50% 60% at 110% 90%, rgba(60, 200, 200, 0.2), transparent),
    radial-gradient(ellipse 50% 40% at -10% 70%, rgba(232, 121, 249, 0.15), transparent),
    #FAFAFA;
  background-attachment: fixed;
}

/* Enhanced glassmorphism */
.glass-aurora {
  background: rgba(255, 255, 255, 0.7);
  backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.8);
  box-shadow: 
    0 1px 2px rgba(0, 0, 0, 0.03),
    0 4px 16px rgba(0, 0, 0, 0.04),
    0 8px 32px rgba(120, 119, 198, 0.04);
  transition: all 0.2s cubic-bezier(0.4, 0, 0.2, 1);
}

.glass-aurora:hover {
  background: rgba(255, 255, 255, 0.85);
  transform: translateY(-1px);
}

/* Tri-color flowing gradient button */
.btn-aurora {
  background: linear-gradient(135deg, #7877C6 0%, #5B8DEF 50%, #3CC8C8 100%);
  background-size: 200% 200%;
  box-shadow: 0 2px 8px rgba(120, 119, 198, 0.25);
  transition: all 0.3s ease;
}

.btn-aurora:hover {
  background-position: 100% 100%;
  transform: translateY(-1px);
}

/* Navigation active state */
.nav-aurora.active {
  background: rgba(120, 119, 198, 0.1);
  color: #7877C6;
}

/* Gradient divider */
.divider-aurora {
  height: 1px;
  background: linear-gradient(90deg, transparent, rgba(0, 0, 0, 0.05), transparent);
}

/* Breathing animation */
.status-pulse {
  animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}

@keyframes pulse {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.5; }
}
```

## Component Specifications

- **Border Radius**: 8px (navigation) / 12px (buttons) / 16-20px (cards)

- **Transition Curve**: `cubic-bezier(0.4, 0, 0.2, 1)`

- **Animation Duration**: 200-300ms

- **Best For**: AI products, SaaS tools, B2B systems, developer platforms ✅

---
