# 独立站 01｜极光弥散风 Aurora Web Design

> **推荐指数**：⭐⭐⭐⭐⭐
> **代表**：Linear / Notion / OpenAI
> **2026顶流主流风格**
> 
> 

## 适用场景

AI官网、SaaS、科技品牌、开发者工具。低饱和多层径向光晕弥散，中心干净、四周柔光。

## 设计理念

低饱和多层径向光晕弥散，中心干净、四周柔光，结合玻璃拟态与微动效，克制高级、科技温柔，长时间浏览不疲劳。

## 核心特征

- 四层低饱和渐变光晕，固定背景
- 毛玻璃半透卡片 + 细白边框
- 紫/蓝/青三色流动渐变
- 弱柔光阴影，无硬投影
- 全局细腻悬浮动效

## 色彩系统

```Plain Text
极光紫：#7877C6
极光蓝：#5B8DEF
极光青：#3CC8C8
极光粉：#E879F9
背景：#FAFAFA
文字主：#171717
文字辅：#737373
```

## 核心 CSS

```css
.aurora-bg {
  background: 
    radial-gradient(ellipse 80% 50% at 20% -20%, rgba(120, 119, 198, 0.3), transparent),
    radial-gradient(ellipse 60% 40% at 80% 0%, rgba(91, 141, 239, 0.25), transparent),
    radial-gradient(ellipse 50% 60% at 110% 90%, rgba(60, 200, 200, 0.2), transparent),
    radial-gradient(ellipse 50% 40% at -10% 70%, rgba(232, 121, 249, 0.15), transparent),
    #FAFAFA;
  background-attachment: fixed;
}

.glass {
  background: rgba(255, 255, 255, 0.7);
  backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.8);
  border-radius: 24px;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.03), 0 4px 16px rgba(0, 0, 0, 0.04);
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

.glass:hover {
  transform: translateY(-4px);
  background: rgba(255, 255, 255, 0.9);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.06), 0 12px 40px rgba(120, 119, 198, 0.1);
}

.btn-aurora {
  background: linear-gradient(135deg, #7877C6, #5B8DEF, #3CC8C8);
  background-size: 200% 200%;
  transition: all 0.3s ease;
}

.btn-aurora:hover {
  background-position: 100% 100%;
  transform: translateY(-2px);
}

.text-aurora {
  background: linear-gradient(135deg, #7877C6, #5B8DEF);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
```

## 组件规范

- **卡片**：24px圆角、blur20、半透明白底
- **按钮**：200%渐变尺寸流动hover
- **动效**：cubic-bezier(0.4,0,0.2,1) 300ms

## 适配

浅色默认、深色光晕降透明度

---
