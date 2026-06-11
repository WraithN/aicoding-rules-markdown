# 独立站 04｜全屏超大字体冲击风

> **推荐指数**：⭐⭐⭐⭐
> **代表**：品牌发布会 / 新品落地页 / 个人作品集
> 
> 

## 适用场景

品牌发布会、新品落地页、个人作品集、创意工作室、营销单页。

## 设计理念

以文字为视觉主体，超大字号占据屏幕主导，弱化图片、强化文字情绪冲击力，极简、张扬、记忆点极强。

## 核心特征

- 首屏单句超大标题，占据视觉中心
- 极简导航、无冗余元素
- 一屏一主题，滚动即切换内容
- 字重极强对比
- 背景极简，突出文字

## 字号规范

```Plain Text
首屏主标题：80~120px（clamp(60px, 12vw, 110px)）
副标题：24~32px
正文：16px
```

## 色彩

黑白主色 + 单点高饱和点缀

## 核心 CSS

```css
.big-title {
  font-size: clamp(60px, 12vw, 110px);
  font-weight: 700;
  line-height: 1;
  letter-spacing: -0.03em;
}

.big-section {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0 24px;
}
```

## 优势

视觉冲击力顶级、品牌记忆点超强、适配创意类、发布类官网

---
