# LDYSprout

[![GitHub license](https://img.shields.io/github/license/ldyivan/hexo-theme-ldysprout)](LICENSE)

一个清新优雅的 Hexo 主题，专注于写作与阅读体验。

## 预览

[在线预览](https://www.hzv5.cn)

## ✨ 特性

- 🌙 优雅的深色模式支持
- 🔍 内置搜索功能
- 📱 响应式设计，完美适配移动端
- 💬 多款评论系统支持（Gitalk、Utterances、Gitment、Valine）
- 📈 文章字数统计和阅读时间
- 🖼️ 图片灯箱效果
- 📑 文章目录支持
- ⚡️ 代码复制功能
- 🔝 返回顶部按钮
- 💰 文章打赏功能
- 🤝 友情链接页面
- 🌈 可自定义的主题配色
- 📊 侧边栏个人信息展示
- 🔗 丰富的社交媒体图标支持

## 🚀 快速开始

### 安装主题

```bash
cd your-hexo-site
git clone https://github.com/ldyivan/hexo-theme-ldysprout.git themes/ldysprout
```

### 启用主题

修改 Hexo 根目录下的 `_config.yml`：

```yaml
theme: ldysprout
```

### 安装依赖

```bash
npm install --save hexo-renderer-ejs hexo-renderer-stylus
```

## ⚙️ 配置

### 主题配置

主题的配置文件位于 `themes/ldysprout/_config.yml`，主要配置项包括：

1. 主题颜色配置
2. 导航菜单设置
3. 侧边栏配置
4. 评论系统设置
5. 文章功能设置
6. 页脚信息配置
7. CDN 配置等

详细配置说明请参考[主题文档](#)。

### 菜单配置

```yaml
menu:
  home:
    path: /
    text: 首页
    icon: fas fa-home
  archives:
    path: /archives
    text: 归档
    icon: fas fa-archive
  categories:
    path: /categories
    text: 分类
    icon: fas fa-folder-open
  friends:
    path: /friends
    text: 友链
    icon: fas fa-link
  about:
    path: /about
    text: 关于
    icon: fas fa-user
```

### 评论系统

主题支持多种评论系统，包括：
- Gitalk
- Utterances
- Gitment
- Valine

请根据需要在配置文件中设置相应的评论系统参数。

### 社交链接

可在侧边栏配置各种社交媒体链接：

```yaml
social:
  github: 
    url: https://github.com/yourusername
    icon: fab fa-github
  email:
    url: mailto:your@email.com
    icon: fas fa-envelope
```

## 📝 文档

更详细的配置说明和使用教程，请访问[主题文档](#)。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request。

## 📄 开源协议

[MIT License](LICENSE) 