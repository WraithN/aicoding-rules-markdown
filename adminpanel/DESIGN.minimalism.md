# 5. Minimalism

> Generous white space / Ultimate simplicity / Premium feel
> 
> 

## Design Philosophy

Generous white space, ultra-thin borders, neutral tones, large typography. Representative style of brands like Apple and Notion.

## Color System

```Plain Text
Pure Black: #000000
Dark Gray: #1A1A1A
Medium Gray: #666666
Light Gray: #999999
Ultra Light Gray: rgba(0, 0, 0, 0.08)
Background: #FFFFFF
```

## Core CSS

```css
.minimal-border {
  border: 0.5px solid rgba(0, 0, 0, 0.08);
}

.minimal-input {
  border: none;
  border-bottom: 1px solid #E5E5E5;
  border-radius: 0;
  background: transparent;
}

.minimal-input:focus {
  border-bottom-color: #000000;
  outline: none;
}

.minimal-btn {
  background: #000000;
  color: #FFFFFF;
  border-radius: 9999px;
  padding: 16px 32px;
  font-weight: 500;
}

.minimal-btn-secondary {
  background: transparent;
  color: #000000;
  border: 1px solid #E5E5E5;
  border-radius: 9999px;
}
```

## Component Guidelines

- **White space priority**: Spacing is 1.5–2× that of standard designs

- **Ultimate simplicity**: Remove all unnecessary decoration

- **Font weight contrast**: Three-level distinction with Light / Regular / Bold

- **Best for**: Premium brands, art projects, luxury websites

---
