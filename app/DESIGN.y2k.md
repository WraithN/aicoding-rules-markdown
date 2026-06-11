# APP 03｜Y2K 千禧复古风

> **推荐指数**：⭐⭐⭐
> **代表**：啫喱 / 多款社交新产品
> 
> 

## 适用场景

社交 APP、拍照 / 修图 APP、潮牌社区、年轻人工具。Windows95 质感、像素字体、千禧年怀旧美学。

## 设计理念

Windows95 质感、像素字体、千禧年怀旧美学。Y2K 复兴。

## 核心特点

- ✅ Windows95 灰色立体按钮
- ✅ 像素字体 / 点阵
- ✅ 2px 凸起边框（外亮内暗）
- ✅ 高饱和彩虹渐变

## 色彩系统

```Plain Text
Win95灰： #C0C0C0
亮边：    #FFFFFF
暗边：    #808080
渐变：    #FF6B6B → #48DBFB → #FF9FF3
```

## 核心 CSS

```css
.y2k-card {
  background: #C0C0C0;
  border: 2px solid;
  border-color: #FFFFFF #808080 #808080 #FFFFFF;
  border-radius: 4px;
}

.y2k-btn {
  background: #C0C0C0;
  border: 2px solid;
  border-color: #FFFFFF #808080 #808080 #FFFFFF;
  font-family: "MS Sans Serif", sans-serif;
  font-size: 12px;
  padding: 4px 12px;
}

.y2k-btn:active {
  border-color: #808080 #FFFFFF #FFFFFF #808080;
}

.y2k-gradient {
  background: linear-gradient(135deg, #FF6B6B, #48DBFB, #FF9FF3);
  background-size: 200% 200%;
  animation: gradientShift 4s ease infinite;
}

@keyframes gradientShift {
  0%, 100% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
}
```

## 组件规范

- **边框风格**：2px 立体凸起边框
- **字体**：像素字体 / 粗体无衬线
- **配色**：Win95 灰 + 高饱和彩虹渐变点缀
- **适用**：社交 APP、拍照 / 修图 APP、潮牌社区、年轻人工具

---
