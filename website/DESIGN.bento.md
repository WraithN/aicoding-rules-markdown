# 独立站 02｜Bento 网格模块化风

> **推荐指数**：⭐⭐⭐⭐⭐
> **代表**：Linear / Raycast / Vercel
> **官方主力风格**
> 
> 

## 适用场景

SaaS、开发者工具、AI官网、产品落地页。

## 设计理念

打破均匀栅格呆板感，采用**大小错落模块化卡片**，一屏承载多维信息，杂志级排版、高级且高效。

## 核心特征

- 4列弹性网格，支持 2×2、2×1、1×1 跨域布局
- 统一圆角、统一玻璃质感、统一阴影体系
- 错落层级，重点区块放大突出
- 悬浮统一上浮动效
- 信息分区清晰，无冗余元素

## 布局规范

```Plain Text
网格基础：4列桌面 / 2列平板 / 1列移动端
间距：grid-gap 20px
卡片圆角：28px
内边距：24~32px
```

## 色彩

沿用极光低饱和色系，保证科技高级感

## 核心 CSS

```css
.bento-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
}

.bento-card {
  background: rgba(255, 255, 255, 0.7);
  backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.8);
  border-radius: 28px;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.03), 0 4px 16px rgba(0, 0, 0, 0.04);
  padding: 24px;
  transition: all 0.3s ease;
}

.bento-card:hover {
  transform: translateY(-4px);
  background: rgba(255, 255, 255, 0.9);
  box-shadow: 0 8px 24px rgba(120, 119, 198, 0.08);
}

/* 跨域布局 */
.bento-col-2 { grid-column: span 2; }
.bento-row-2 { grid-row: span 2; }
```

## 优势

1. 一屏展示核心卖点，减少滚动
2. 模块化可自由增减
3. 视觉高级、大厂质感
4. 适配所有科技类独立站

---
