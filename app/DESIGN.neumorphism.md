# APP 05｜新拟态柔色柔光风

> **推荐指数**：⭐⭐⭐⭐
> **代表**：计算器类工具 / 音乐播放器 / 智能家居控制面板
> 
> 

## 适用场景

工具类 APP、智能家居控制、音乐播放器、计算器。比传统新拟态更柔和，适配现代APP界面。

## 设计理念

在同色系背景上通过明暗阴影创造浮雕质感，柔化处理降低视觉疲劳，适配移动端高频使用场景。

## 核心特点

- ✅ 同色系明暗阴影（无高对比）
- ✅ 柔和圆角 16-24px
- ✅ 按钮按压凹陷反馈
- ✅ 低饱和配色，长时间使用不疲劳

## 色彩系统

```Plain Text
背景色：#E8ECF1
亮阴影：#FFFFFF
暗阴影：#C5CDD7
文字色：#5A6578
主色调：#7877C6（柔紫）
```

## 核心 CSS

```css
.neo-app-card {
  background: #E8ECF1;
  border-radius: 20px;
  box-shadow: 
    6px 6px 12px #C5CDD7, 
    -6px -6px 12px #FFFFFF;
  padding: 20px;
}

.neo-app-btn {
  background: #E8ECF1;
  border-radius: 16px;
  box-shadow: 
    4px 4px 8px #C5CDD7, 
    -4px -4px 8px #FFFFFF;
  transition: all 0.2s ease;
}

.neo-app-btn:active {
  box-shadow: 
    inset 3px 3px 6px #C5CDD7, 
    inset -3px -3px 6px #FFFFFF;
}

.neo-app-input {
  background: #E8ECF1;
  border-radius: 12px;
  box-shadow: 
    inset 3px 3px 6px #C5CDD7, 
    inset -3px -3px 6px #FFFFFF;
  border: none;
  padding: 12px 16px;
}
```

## 组件规范

- **圆角**：16-24px（卡片）/ 12-16px（按钮）
- **阴影偏移**：4-6px
- **阴影模糊**：8-12px
- **按压态**：inset 阴影替代外阴影
- **适用**：工具 APP、智能家居、音乐播放器、控制面板

---
