# 2\. Glassmorphism

> Frosted glass / Transparent / Mainstream since 2021
> 
> 

## Design Philosophy

Semi-transparent background + blur + thin border creates a sense of layering and depth. A favorite in iOS and Web3 projects

## Color System

```Plain Text
White glass: rgba(255, 255, 255, 0.25)
Dark glass: rgba(15, 23, 42, 0.7)
Border color: rgba(255, 255, 255, 0.18)
Background blur: blur(20px)
```

## Core CSS

```css
.glass-card {
  background: rgba(255, 255, 255, 0.25);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.18);
  box-shadow: 0 8px 32px rgba(31, 38, 135, 0.15);
  border-radius: 16px;
}

.glass-dark {
  background: rgba(15, 23, 42, 0.7);
  backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.1);
}
```

## Component Guidelines

- **Blur amount**: 12\-20px

- **Transparency**: 0\.2\-0\.3 (light) / 0\.6\-0\.8 (dark)

- **Background**: Must be paired with a colorful gradient background

- **Best for**: Modals, sidebars, cards, Web3 wallets

---
