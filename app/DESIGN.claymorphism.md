# APP 01｜粘土软 UI Claymorphism

> **推荐指数**：⭐⭐⭐⭐⭐
> **代表**：小红书新版 / Widgetable / Lensa
> **C 端 APP 首选**
> 
> 

## 适用场景

C端社交、工具、生活、女性向APP。亲和力极强，用户接受度最高，2026最火C端APP风格。

## 设计理念

大圆角 + 双层阴影 + 内高光，创造膨胀柔软的 3D 质感。Q弹治愈，老少皆宜。

## 核心特点

- ✅ 超级大圆角 20-28px
- ✅ 双层阴影：外投影 + 内高光
- ✅ 按钮按压内凹，真实物理反馈
- ✅ 柔和膨胀感，Q 弹可爱
- ✅ 全界面无尖锐线条

## 色彩系统

```Plain Text
背景色：#F0F4F8
卡片色：#FFFFFF
阴影色：rgba(13, 37, 72, 0.12)
内高光：rgba(255, 255, 255, 0.9)
```

## 核心 CSS

```css
.clay-card {
  background: #FFFFFF;
  border-radius: 24px;
  box-shadow: 
    0 12px 24px rgba(13, 37, 72, 0.12), 
    0 -4px 12px rgba(255, 255, 255, 0.8),
    inset 0 2px 4px rgba(255, 255, 255, 0.9);
  border: 1px solid rgba(255, 255, 255, 0.9);
}

.clay-btn {
  background: linear-gradient(145deg, #FFFFFF, #E6E9EF);
  border-radius: 20px;
  box-shadow: 
    4px 4px 10px rgba(13, 37, 72, 0.15), 
    -2px -2px 8px rgba(255, 255, 255, 0.9);
  transition: all 0.2s;
}

.clay-btn:active {
  box-shadow: 
    inset 2px 2px 5px rgba(13, 37, 72, 0.1), 
    inset -2px -2px 5px rgba(255, 255, 255, 0.8);
}
```

## 组件规范

- **卡片圆角**：20-28px
- **按钮圆角**：16-20px
- **按压反馈**：active 状态内凹
- **常态凸起、active内凹**
- **适用**：所有 C 端 APP、社交、工具、女性向

## APP 适配要点

- 使用系统安全区适配刘海屏
- 底部导航栏采用 clay-card 样式
- 列表项使用 16-20px 圆角
- 按钮最小点击区域 44×44px

---
