# SARENTH 网站图片管理指南

## 📁 文件结构

```
sarenth/
├── index.html          # 主页面
├── images/             # 所有图片放这里
│   ├── hero-bg.jpg              # Hero 区域背景图
│   ├── cta-bg.jpg               # CTA 区域背景图
│   ├── hero-product.jpg         # Hero 右侧产品图
│   ├── about-facility.jpg       # 关于我们-工厂图
│   ├── product-wheel-module.jpg # 产品1: 轮毂模块电池
│   ├── product-high-voltage.jpg # 产品2: 高压机架电池
│   ├── product-stackable.jpg    # 产品3: 可堆叠电池
│   ├── product-powerwall.jpg    # 产品4: 家庭储能墙
│   ├── product-high-voltage-2.jpg # 产品5: 高压机架(另一角度)
│   ├── product-telecom.jpg      # 产品6: 通信基站电池
│   ├── solution-offgrid.jpg     # 方案1: 离网太阳能
│   ├── solution-home.jpg        # 方案2: 家庭储能
│   ├── solution-commercial.jpg  # 方案3: 商业电站
│   └── solution-industrial.jpg  # 方案4: 工业储能
└── README.md
```

## 🔄 替换图片步骤

### 方法：直接覆盖文件

1. **准备新图片**
   - 格式：JPG 或 WebP（推荐）
   - 尺寸建议：
     - 背景图：1920×1080 或更大
     - 产品图：800×600 或 600×600
     - 方案图：800×600

2. **重命名**
   - 把新图片改成对应文件名（必须完全一致）
   - 例如：`my-photo.jpg` → `hero-bg.jpg`

3. **复制到 images 文件夹**
   - 直接覆盖原文件

4. **刷新网站**
   - 按 `Ctrl+F5` 强制刷新
   - 或清除浏览器缓存

## 📝 图片命名规则

| 文件名 | 用途 | 建议尺寸 |
|--------|------|----------|
| `hero-bg.jpg` | 首页大背景 | 1920×1080 |
| `cta-bg.jpg` | 底部CTA背景 | 1920×600 |
| `hero-product.jpg` | Hero产品展示 | 600×800 |
| `about-facility.jpg` | 关于我们-工厂 | 800×600 |
| `product-*.jpg` | 6个产品卡片 | 600×450 |
| `solution-*.jpg` | 4个应用场景 | 600×450 |

## 💡 图片优化建议

1. **压缩图片**：用 [tinypng.com](https://tinypng.com) 压缩，减少文件大小
2. **WebP格式**：如果浏览器支持，可用 .webp 后缀，体积更小
3. **替换后测试**：手机、电脑都要看，确保显示正常

## ⚠️ 注意事项

- **不要改文件名**，只覆盖内容
- **保持格式一致**，原来是 .jpg 就还用 .jpg
- **备份原图**，改之前复制一份备用
- **大小写敏感**：`hero-bg.jpg` 和 `Hero-BG.JPG` 是不同的文件

## 🆘 图片不显示怎么办

1. 检查文件名是否完全一致
2. 检查是否在 `images/` 文件夹内
3. 按 `Ctrl+F5` 强制刷新
4. 检查图片格式（.jpg / .png / .webp）
5. 打开浏览器 F12 → Console 看报错信息
