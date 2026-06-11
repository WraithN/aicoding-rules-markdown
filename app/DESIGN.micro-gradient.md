# APP 07｜微渐变轻质感风

> **推荐指数**：⭐⭐⭐⭐
> **代表**：记账类APP / 健康类APP / 日程管理工具
> 
> 

## 适用场景

记账类APP、健康类APP、日程管理工具、轻量工具类。微妙的色彩过渡，轻盈不油腻。

## 设计理念

采用极微妙的渐变过渡（而非强烈对比），配合轻量阴影和细边框，营造高级感的同时保持界面清爽。

## 核心特点

- ✅ 微渐变背景（同色系 5% 差异）
- ✅ 极轻阴影（y: 2px, blur: 8px, opacity: 0.06）
- ✅ 细边框（0.5px 或 1px 浅灰）
- ✅ 圆角 12-16px
- ✅ 图标使用线性渐变填充

## 色彩系统

```Plain Text
背景渐变：#FAFBFC → #F5F6F8
卡片背景：#FFFFFF
主色调：#6366F1（靛蓝）
辅助色：#8B5CF6（紫）/ #10B981（绿）
文字主色：#1F2937
文字辅色：#6B7280
边框色：rgba(0,0,0,0.06)
阴影色：rgba(0,0,0,0.06)
```

## 核心 CSS

```css
.micro-bg {
  background: linear-gradient(180deg, #FAFBFC 0%, #F5F6F8 100%);
  min-height: 100vh;
}

.micro-card {
  background: #FFFFFF;
  border-radius: 16px;
  border: 0.5px solid rgba(0, 0, 0, 0.06);
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
  padding: 16px;
}

.micro-btn {
  background: linear-gradient(135deg, #6366F1, #8B5CF6);
  border-radius: 12px;
  color: white;
  box-shadow: 0 2px 8px rgba(99, 102, 241, 0.25);
}

.micro-icon {
  background: linear-gradient(135deg, #6366F1, #8B5CF6);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
```

## 组件规范

- **卡片圆角**：16px
- **按钮圆角**：12px
- **阴影**：极轻，几乎不可见但提供层次
- **边框**：0.5px 浅灰，增加精致感
- **渐变角度**：135° 或 180°
- **适用**：记账、健康、日程、轻量工具

---
