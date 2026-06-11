# 独立站 03｜Apple 极简留白高端风

> **推荐指数**：⭐⭐⭐⭐⭐
> **代表**：Apple官网 / Airbnb / Arcade.studio
> 
> 

## 适用场景

高端品牌、数码硬件、奢侈品、建筑设计、艺术工作室、高端民宿。

## 设计理念

Less is More，超大留白、极少元素、极强字重对比，去掉所有装饰，用留白和排版营造奢侈高级感。

## 核心特点

- 全局超大间距（常规设计1.5~2倍）
- 纯黑白灰体系，极少点缀色
- 极强字重层级：粗标题、细正文
- 无圆角/极小圆角
- 无复杂阴影、无渐变堆砌

## 色彩系统

```Plain Text
纯黑：#000000
深灰：#1A1A1A
中灰：#666666
浅灰：#999999
边框灰：#E5E5E5
纯白：#FFFFFF
```

## 排版规范

```Plain Text
H1：64~80px / 600 / 1.1行高 / -0.02字间距
H2：32~40px / 500 / 1.2行高
正文：16~18px / 400 / 1.6行高
```

## 核心 CSS

```css
.apple-h1 {
  font-size: clamp(48px, 6vw, 80px);
  font-weight: 600;
  line-height: 1.1;
  letter-spacing: -0.02em;
}

.apple-section {
  padding: 120px 0;
}

.btn-black {
  background: #000;
  color: #fff;
  border-radius: 9999px;
  padding: 18px 40px;
  transition: opacity 0.2s;
}

.btn-black:hover {
  opacity: 0.8;
}

.btn-line {
  border: 1px solid #e5e5e5;
  border-radius: 9999px;
  padding: 18px 40px;
  background: transparent;
}
```

---
