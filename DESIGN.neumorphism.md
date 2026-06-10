# 1\. Neumorphism

> Soft UI / Embossed Effect / Trending since 2020
> 
> 

## Design Philosophy

Light and dark shadows in the same color family create an embossed, pressable feel that is soft and easy on the eyes. **Drawback: low contrast, poor accessibility; not recommended for large-area use**

## Color System

```Plain Text
Background: #E0E5EC
Light shadow: #FFFFFF
Dark shadow: #A3B1C6
Text color: #4A5568
```

## Core CSS

```css
.neo-card {
  background: #E0E5EC;
  box-shadow: 8px 8px 16px #A3B1C6, -8px -8px 16px #FFFFFF;
  border-radius: 20px;
}

.neo-btn {
  background: #E0E5EC;
  box-shadow: 6px 6px 12px #A3B1C6, -6px -6px 12px #FFFFFF;
  border-radius: 12px;
}

.neo-btn:active, .neo-btn.active {
  box-shadow: inset 4px 4px 8px #A3B1C6, inset -4px -4px 8px #FFFFFF;
}

.neo-input {
  background: #E0E5EC;
  box-shadow: inset 4px 4px 8px #A3B1C6, inset -4px -4px 8px #FFFFFF;
  border-radius: 10px;
}
```

## Component Guidelines

- **Border radius**: 12\-20px

- **Button states**: Raised by default, indented when pressed

- **Best for**: Players, control panels, widgets

- **Not suitable for**: Long text, data tables

---
