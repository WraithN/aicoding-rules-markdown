# APP 02｜极光弥散风 Aurora / 极光玻璃拟态风

> **推荐指数**：⭐⭐⭐⭐⭐
> **代表**：Linear Mobile / Notion AI / ChatGPT
> **AI / 工具类首选**
> 
> 

## 适用场景

AI工具、效率APP、金融、科技移动端。轻量化极光柔光+低模糊玻璃卡片，通透、轻盈、科技高级。

## 设计理念

低饱和渐变光晕 + 毛玻璃卡片 + 柔和阴影。AI 产品标准配置。

## 核心特点

- ✅ 紫蓝青低饱和渐变背景
- ✅ 半透明毛玻璃卡片
- ✅ 三色流动渐变按钮
- ✅ 似有若无，高级感
- ✅ 不厚重、护眼、适配高频使用APP

## 色彩系统

```Plain Text
极光紫：#7877C6
极光蓝：#5B8DEF
极光青：#3CC8C8
背景：  #FAFAFA + 径向渐变
```

## 核心 CSS

```css
/* 移动端轻量化极光背景 */
.aurora-bg {
  background: 
    radial-gradient(ellipse 60% 40% at 10% 0%, rgba(120, 119, 198, 0.2), transparent),
    radial-gradient(ellipse 60% 40% at 90% 100%, rgba(91, 141, 239, 0.15), transparent),
    #FAFAFA;
}

/* 移动端玻璃卡片 - 轻量模糊 */
.app-glass {
  background: rgba(255, 255, 255, 0.6);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  border: 1px solid rgba(255, 255, 255, 0.7);
  border-radius: 20px;
  transition: all 0.2s ease;
}

/* 渐变按钮 */
.btn-gradient {
  background: linear-gradient(135deg, #7877C6, #5B8DEF, #3CC8C8);
  border-radius: 12px;
  color: white;
}

/* 聚焦柔光边框 */
.focus-glow:focus {
  outline: none;
  box-shadow: 0 0 0 4px rgba(120, 119, 198, 0.15);
}
```

## 组件规范

- **模糊**：12px（移动端最优性能）
- **卡片透明度**：0.6
- **圆角**：20px
- **聚焦柔光边框**：4px主色光晕
- **卡片圆角**：20px
- **按钮圆角**：12px
- **适用**：AI 工具 APP、效率类 APP、SaaS 移动端、开发者工具

## APP 适配要点

- 移动端 backdrop-filter 性能优化（使用 12px 而非 20px）
- 卡片透明度降至 0.6 保证内容可读性
- 导航栏使用轻量玻璃效果
- 按钮使用三色渐变，hover 时背景位移动效

---
