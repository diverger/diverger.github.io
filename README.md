# 个人博客 - Hexo + NexT

这是一个使用 Hexo 静态站点生成器和 NexT 主题构建的个人博客，已成功从 Felix Felicis (liquidluck) 迁移。

## 🎉 迁移完成状态

### ✅ 已完成的功能
- **Hexo 核心**: 完整安装和配置
- **NexT 主题**: Gemini 方案，现代化外观
- **中文优化**: 支持中文内容和 pangu.js 自动排版
- **搜索功能**: 本地搜索支持 (hexo-generator-searchdb)
- **导航菜单**: 首页、关于、标签、分类、归档
- **阅读体验**: 进度条、代码复制按钮
- **内容迁移**: 9 篇博客文章已迁移
- **页面结构**: 关于、标签、分类页面已创建
- **部署配置**: GitHub Pages 部署已配置

### 📊 内容统计
- **博客文章**: 9 篇
- **分类**: life (生活), work (工作)
- **标签**: python, code, blog, web, 技术, FPGA, 硬件开发, 生活, 感悟, 开发工具
- **页面**: 首页 + 5 个导航页面
- **生成文件**: 24 个静态文件

### 🛠 技术栈
- **静态生成器**: Hexo 7.3.0
- **主题**: NexT 8.23.1 (Gemini)
- **语言**: 简体中文 (zh-CN)
- **部署**: GitHub Pages
- **搜索**: 本地搜索
- **字体优化**: 中文字体栈

## 🚀 使用方法

### 开发服务器
```bash
npm run server
# 访问: http://localhost:4000
```

### 构建网站
```bash
npm run build
```

### 部署到 GitHub Pages
```bash
npm run deploy
```

### 创建新文章
```bash
npx hexo new "文章标题"
```

### 清理缓存
```bash
npm run clean
```

## 📁 目录结构

```
├── source/              # 源文件目录
│   ├── _posts/         # 博客文章
│   ├── about/          # 关于页面
│   ├── tags/           # 标签页面
│   ├── categories/     # 分类页面
│   └── _data/          # 自定义数据
├── themes/next/        # NexT 主题
├── public/             # 生成的静态文件
├── _config.yml         # Hexo 主配置
└── package.json        # 依赖和脚本
```

## 🌟 主要特性

- **响应式设计**: 移动端友好
- **中文排版优化**: pangu.js 自动空格
- **搜索功能**: 快速内容搜索
- **代码高亮**: 支持多种编程语言
- **阅读进度**: 顶部进度条显示
- **社交链接**: GitHub 等社交媒体集成
- **SEO 优化**: 搜索引擎友好

## 🔧 配置说明

### 主要配置文件
- `_config.yml`: Hexo 主配置
- `themes/next/_config.yml`: NexT 主题配置

### 关键配置项
- **站点信息**: 中文标题和描述
- **URL**: https://diverger.github.io
- **主题**: NexT Gemini
- **搜索**: 本地搜索启用
- **部署**: Git 部署到 main 分支

## 📝 博客文章

1. **SystemVerilog vs VHDL** (2015-01-29) - 硬件描述语言对比
2. **Tech Reason** (2015-01-06) - 技术思考
3. **Tool Chain** (2014-12-25) - 开发工具链
4. **梦想** (2015-01-19) - 生活感悟
5. **压力** (2015-01-09) - 心情随笔
6. **惊喜** (2015-01-16) - 生活记录
7. **圣诞** (2014-12-25) - 节日感想
8. **Happy** (2014-12-25) - 开心时刻
9. **Hello World** (2014-12-25) - 博客开始

## 🚀 部署选项

### SSH 环境下的访问方式

1. **端口转发** (推荐):
   ```bash
   # 在本地终端运行
   ssh -L 4000:localhost:4000 user@remote-server
   # 然后在浏览器访问 http://localhost:4000
   ```

2. **公网访问**:
   ```bash
   npx hexo server --host 0.0.0.0 --port 4000
   # 通过服务器 IP:4000 访问
   ```

3. **直接部署**:
   ```bash
   npm run deploy
   # 部署到 GitHub Pages，通过 https://diverger.github.io 访问
   ```

## ⚡ 下一步

1. **测试访问**: 确认网站在浏览器中正常显示
2. **内容检查**: 验证所有文章正确渲染
3. **部署上线**: 推送到 GitHub Pages
4. **性能优化**: 图片压缩、CDN 等
5. **功能增强**: 评论系统、统计分析等

## 🎯 迁移成功！

✅ **从 Felix Felicis 到 Hexo 的迁移已成功完成**

- 保持了原有的中文内容和结构
- 提升了现代化程度和用户体验
- 增加了搜索、标签等功能
- 优化了中文排版显示
- 配置了自动部署流程

现在可以开始使用新的 Hexo 博客了！
