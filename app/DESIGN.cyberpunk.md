# APP 06｜暗黑霓虹赛博APP风

> **推荐指数**：⭐⭐⭐
> **代表**：原神 / 崩坏：星穹铁道 / 游戏类
> 
> 

## 适用场景

游戏 APP、二次元社区、科技媒体、极客工具。深底色 + 霓虹发光字 + 赛博元素。

## 设计理念

深底色 + 霓虹发光字 + 赛博元素。游戏、二次元标配。

## 核心特点

- ✅ 纯黑 / 深灰底色
- ✅ 文字发光 text-shadow
- ✅ 高饱和霓虹色（粉 / 青 / 紫）
- ✅ 扫描线效果

## 色彩系统

```Plain Text
深底色：  #0A0A0F
霓虹粉：  #FF2A6D
霓虹青：  #05D9E8
霓虹紫：  #D300C5
```

## 核心 CSS

```css
.cyber-app-bg {
  background: #0A0A0F;
  color: #E5E5E5;
}

.cyber-glow {
  text-shadow: 
    0 0 10px currentColor, 
    0 0 20px currentColor, 
    0 0 40px currentColor;
}

.cyber-border {
  border: 1px solid #05D9E8;
  box-shadow: 
    0 0 5px #05D9E8, 
    inset 0 0 5px rgba(5, 217, 232, 0.1);
}

.cyber-card {
  background: rgba(20, 20, 30, 0.8);
  border: 1px solid rgba(5, 217, 232, 0.2);
  border-radius: 16px;
  backdrop-filter: blur(10px);
}

.scanline {
  background: linear-gradient(transparent 50%, 
    rgba(5, 217, 232, 0.03) 50%);
  background-size: 100% 4px;
}
```

## 组件规范

- **底色**：#0A0A0F 纯黑
- **发光色**：粉 #FF2A6D / 青 #05D9E8 / 紫 #D300C5
- **边框**：1px 霓虹色 + 外发光
- **字体**：等宽字体 / 粗体无衬线
- **适用**：游戏 APP、二次元社区、科技媒体、极客工具

---
