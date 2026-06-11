# Website 07 | Magazine Grid Editorial Style

> **Rating**: ⭐⭐⭐⭐
> **Representatives**: Media Official Websites / Blogs / Design Magazines
> 
> 

## Applicable Scenarios

Media official websites, blogs, design magazines, content platforms, image-text showcase sites.

## Design Philosophy

Strict grid system, staggered image-text layout, restrained white space, clear hierarchy. Replicates the typographic quality of premium magazines, with excellent reading experience.

## Core Characteristics

- Strict 12-column grid layout
- Large images with small text, large text with small images alternating
- Unified baseline alignment
- Elegant image-text mixed layout
- No flashy animations, focus on reading

## Typography

```Plain Text
Bold titles, thin body text, generous line-height
Unified image border-radius, unified white space
```

## Core CSS

```css
.magazine-grid {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 24px;
}

.magazine-hero {
  grid-column: span 7;
}

.magazine-sidebar {
  grid-column: span 5;
}

.magazine-card {
  background: #FFFFFF;
  border-radius: 16px;
  overflow: hidden;
}

.magazine-text h1 {
  font-size: 48px;
  font-weight: 700;
  line-height: 1.2;
  letter-spacing: -0.02em;
}

.magazine-text p {
  font-size: 18px;
  line-height: 1.7;
  color: #4B5563;
}
```

## Advantages

Professional, artistic, premium, suitable for content-based independent websites

---
