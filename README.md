# Typora Nord Theme Toolkit

[English](#english) | [中文](#中文)

---

## 中文

### 🎨 Nord风格Typora主题

这是一个基于Nord调色板的Typora主题，将Obsidian的Blue-Topaz主题风格迁移到Typora平台。主题采用了优雅的Nord配色方案，提供了舒适的深色阅读体验。

### ✨ 主要特性

- **🌙 Nord深色主题**: 基于流行的Nord调色板，护眼且优雅
- **🎯 精心调色的标题**: H1-H5使用Nord Aurora配色系统
  - H1: `#bf616a` (Aurora Red) - 红色
  - H2: `#d08770` (Aurora Orange) - 橙色  
  - H3: `#ebcb8b` (Aurora Yellow) - 黄色，带下划线
  - H4: `#a3be8c` (Aurora Green) - 绿色
  - H5: `#b48ead` (Aurora Purple) - 紫色
- **💫 文本强调样式**:
  - *斜体*: `#a3be8c` (与H4同色)
  - **粗体**: `#E8B4B4` (温柔粉色)
  - ***粗斜体***: `#F55354` (鲜艳红橙色)
- **📝 优化的列表样式**: 有序列表数字使用 `#81a1c1` (Nord蓝)
- **💻 代码高亮**:
  - 行内代码: `#88c0d0` (明亮Nord蓝)
  - 代码块: Material Palenight语法高亮
  - 独特的双窗口代码标签效果
- **📋 大纲面板**: 统一的Nord深色主题
- **🖨️ 打印优化**: 针对打印输出优化的配色

### 📦 安装方法

1. **下载主题文件**
   ```bash
   git clone https://github.com/your-username/typora-theme-toolkit.git
   cd typora-theme-toolkit
   ```

2. **安装到Typora**
   - 复制 `nord-obsidian-typora.css` 到Typora主题文件夹
   - 在Typora中: `文件` → `偏好设置` → `外观` → `打开主题文件夹`
   - 重启Typora并选择 `Nord Obsidian` 主题


### 🎯 设计理念

本主题致力于将Obsidian的优秀视觉体验带到Typora平台，同时保持Nord调色板的一致性和美感。每个元素的配色都经过精心调校，确保在长时间使用中提供舒适的视觉体验。

### 📸 预览效果

- 优雅的标题层级显示
- 清晰的代码块语法高亮
- 舒适的文本强调效果
- 统一的界面风格

### 🛠️ 自定义

如需个性化调整，可以修改CSS文件中的颜色变量：

```css
:root {
  --bg-color-primary: #2e3440;    /* 主背景色 */
  --text-color-primary: #d8dee9;  /* 主文本色 */
  --accent-cyan: #88c0d0;         /* 强调色 */
  /* ... 更多变量 */
}
```

### 🤝 贡献

欢迎提交Issue和Pull Request！

### 📄 许可证

MIT License

---

## English

### 🎨 Nord-Style Typora Theme

A Typora theme based on the Nord color palette, migrating the Obsidian Blue-Topaz theme style to the Typora platform. This theme uses an elegant Nord color scheme to provide a comfortable dark reading experience.

### ✨ Key Features

- **🌙 Nord Dark Theme**: Based on the popular Nord color palette, eye-friendly and elegant
- **🎯 Carefully Colored Headings**: H1-H5 using Nord Aurora color system
  - H1: `#bf616a` (Aurora Red)
  - H2: `#d08770` (Aurora Orange)  
  - H3: `#ebcb8b` (Aurora Yellow) with underline
  - H4: `#a3be8c` (Aurora Green)
  - H5: `#b48ead` (Aurora Purple)
- **💫 Text Emphasis Styles**:
  - *Italic*: `#a3be8c` (same as H4)
  - **Bold**: `#E8B4B4` (gentle pink)
  - ***Bold Italic***: `#F55354` (vibrant red-orange)
- **📝 Optimized List Styles**: Ordered list numbers use `#81a1c1` (Nord blue)
- **💻 Code Highlighting**:
  - Inline code: `#88c0d0` (bright Nord blue)
  - Code blocks: Material Palenight syntax highlighting
  - Unique dual-window code label effect
- **📋 Outline Panel**: Unified Nord dark theme
- **🖨️ Print Optimized**: Color scheme optimized for print output

### 📦 Installation

1. **Download Theme Files**
   ```bash
   git clone https://github.com/your-username/typora-theme-toolkit.git
   cd typora-theme-toolkit
   ```

2. **Install to Typora**
   - Copy `nord-obsidian-typora.css` to Typora theme folder
   - In Typora: `File` → `Preferences` → `Appearance` → `Open Theme Folder`
   - Restart Typora and select `Nord Obsidian` theme

   ```

### 🎯 Design Philosophy

This theme aims to bring Obsidian's excellent visual experience to the Typora platform while maintaining the consistency and aesthetics of the Nord color palette. Each element's color scheme has been carefully calibrated to ensure a comfortable visual experience during extended use.

### 📸 Preview Effects

- Elegant heading hierarchy display
- Clear code block syntax highlighting
- Comfortable text emphasis effects
- Unified interface style

### 🛠️ Customization

For personalized adjustments, you can modify the color variables in the CSS file:

```css
:root {
  --bg-color-primary: #2e3440;    /* Primary background */
  --text-color-primary: #d8dee9;  /* Primary text */
  --accent-cyan: #88c0d0;         /* Accent color */
  /* ... more variables */
}
```

### 🤝 Contributing

Issues and Pull Requests are welcome!

### 📄 License

MIT License

---

## 🔧 Technical Details

### Color Palette Reference

Based on the [Nord Color Palette](https://www.nordtheme.com/docs/colors-and-palettes):

| Category | Colors | Usage |
|----------|--------|-------|
| **Polar Night** | `#2e3440` `#3b4252` `#434c5e` `#4c566a` | Backgrounds, UI elements |
| **Snow Storm** | `#d8dee9` `#e5e9f0` `#eceff4` | Text, foregrounds |
| **Frost** | `#8fbcbb` `#88c0d0` `#81a1c1` `#5e81ac` | Accents, highlights |
| **Aurora** | `#bf616a` `#d08770` `#ebcb8b` `#a3be8c` `#b48ead` | Headings, emphasis |

### Compatibility

- **Typora Version**: 1.0+
- **Platform**: macOS, Windows, Linux
- **Export**: PDF, HTML, Word (with print-optimized colors)

### Dependencies

- Nord Color Palette
- Material Palenight (for code syntax highlighting)
- CodeMirror (Typora's code editor)
