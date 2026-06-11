# Website 06 | 3D Parallax Immersive Interaction Style

> **Rating**: ⭐⭐⭐⭐
> **Representatives**: Hardware Products / Automotive Official Websites / Metaverse
> 
> 

## Applicable Scenarios

Hardware products, automotive official websites, metaverse, AI visual products, premium brand landing pages.

## Design Philosophy

Through parallax scrolling, mouse-follow 3D displacement, and layer separation, create web-level immersive 3D effects that break the limitations of two-dimensional planes.

## Core Characteristics

- Multi-layer parallax scrolling
- Mouse hover subtle 3D tilt
- 3D models / stereoscopic graphics paired
- Soft light and shadow gradients
- Smooth and coherent scroll animations

## Technical Points

```Plain Text
transform perspective perspective
translateZ layer displacement
Scroll listener layered movement
Low-saturation light and shadow enhance 3D depth
```

## Core CSS

```css
.parallax-container {
  perspective: 1000px;
}

.parallax-card {
  transition: transform 0.2s ease;
  transform-style: preserve-3d;
}

.parallax-layer-1 { transform: translateZ(50px); }
.parallax-layer-2 { transform: translateZ(100px); }
.parallax-layer-3 { transform: translateZ(150px); }

/* Mouse-follow 3D tilt */
.tilt-3d {
  transform-style: preserve-3d;
  transition: transform 0.1s ease-out;
}
```

## Applicability

Premium hardware, tech flagship products, launch event official websites, metaverse projects

---
