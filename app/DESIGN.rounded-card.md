# APP 08｜圆润治愈卡片风

> **推荐指数**：⭐⭐⭐⭐⭐
> **代表**：Coze / 潮汐 / 小睡眠 / 冥想类APP
> 
> 

## 适用场景

冥想类APP、睡眠辅助、心理健康、生活方式、宠物类APP。极致圆润、治愈配色、无攻击性。

## 设计理念

超大圆角（接近正圆）、柔和治愈配色（低饱和粉蓝绿）、无尖锐元素，营造安全感和治愈感。

## 核心特点

- ✅ 超大圆角卡片（24-32px）
- ✅ 治愈配色：低饱和粉、蓝、绿、米白
- ✅ 无直角、无尖锐线条
- ✅ 大间距、大留白
- ✅ 柔和插画风格图标

## 色彩系统

```Plain Text
背景色：#FFF9F5（暖米白）
卡片色：#FFFFFF
治愈粉：#FFB5B5
治愈蓝：#B5D8FF
治愈绿：#B5E4CA
治愈黄：#FFE4B5
文字主色：#4A4A4A
文字辅色：#9A9A9A
```

## 核心 CSS

```css
.heal-bg {
  background: #FFF9F5;
  min-height: 100vh;
}

.heal-card {
  background: #FFFFFF;
  border-radius: 28px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.04);
  padding: 24px;
}

.heal-btn {
  background: #FFB5B5;
  border-radius: 24px;
  color: #FFFFFF;
  padding: 14px 32px;
  font-weight: 600;
  box-shadow: 0 4px 12px rgba(255, 181, 181, 0.3);
}

.heal-tag {
  background: #B5D8FF;
  border-radius: 20px;
  padding: 6px 16px;
  font-size: 12px;
  color: #4A4A4A;
}

.heal-avatar {
  width: 56px;
  height: 56px;
  border-radius: 50%;
  background: linear-gradient(135deg, #FFB5B5, #B5D8FF);
}
```

## 组件规范

- **卡片圆角**：28-32px
- **按钮圆角**：24px（接近药丸形）
- **配色**：低饱和暖色调为主
- **间距**：大间距，呼吸感强
- **图标**：圆润插画风格，避免线性图标
- **适用**：冥想、睡眠、心理健康、生活方式、宠物

---
