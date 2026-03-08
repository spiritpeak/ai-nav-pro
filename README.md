# AI 导航 Pro - 精选全球最棒的人工智能工具

🌐 **在线访问**: [你的 GitHub Pages 链接]  
📁 **本地文件**: `index.html`

## 📖 项目介绍

这是一个现代、优雅的 AI 工具导航网站，收录了 30+ 款精选人工智能应用，涵盖：
- 🤖 大语言模型
- 🎨 图像生成
- 💻 编程开发
- 🎵 语音音频
- 🎬 视频制作
- 📊 办公效率
- ✍️ 写作助手
- 🎮 3D 设计

## ✨ 功能特性

- ✅ 实时搜索过滤
- ✅ 分类导航
- ✅ 深色模式切换
- ✅ 收藏功能（本地存储）
- ✅ 一键复制链接
- ✅ 响应式设计（手机/平板/电脑通用）
- ✅ 数据持久化

## 🚀 部署到 GitHub Pages

### 方法 1：使用 GitHub Desktop（推荐新手）

1. **下载并安装** [GitHub Desktop](https://desktop.github.com/)
2. **克隆仓库**到你的电脑
3. **复制文件**：将 `index.html` 复制到仓库文件夹
4. **提交更改**：点击 "Commit to main"
5. **推送上传**：点击右上角 "Push origin"
6. **启用 Pages**：
   - 进入仓库的 **Settings** → **Pages**
   - Source 选择 **main branch**
   - 点击 **Save**
7. **获取链接**：几分钟后，你的网站将在 `https://你的用户名.github.io/仓库名/` 上线

### 方法 2：使用网页上传（最简单）

1. 进入你的 GitHub 仓库页面
2. 点击 **"Add file"** → **"Upload files"**
3. 将 `index.html` 拖入上传区域
4. 点击 **"Commit changes"**
5. 进入 **Settings** → **Pages**
6. Source 选择 **main branch**，保存
7. 等待 1-2 分钟，访问 `https://你的用户名.github.io/仓库名/`

### 方法 3：使用 Git 命令行（推荐开发者）

```bash
# 1. 克隆仓库
git clone https://github.com/你的用户名/你的仓库名.git
cd 你的仓库名

# 2. 复制文件
cp /Users/xiamingzhu/Desktop/index.html .

# 3. 提交并推送
git add index.html
git commit -m "Add AI navigation website"
git push origin main

# 4. 在 GitHub 设置中启用 Pages
# Settings → Pages → Source: main branch → Save
```

## 🎨 自定义内容

### 添加工具

编辑 `index.html` 中的 `toolsData` 数组，按格式添加：

```javascript
{
    name: "工具名称",
    url: "https://工具网址",
    icon: "fa-solid fa-图标类名",  // 从 https://fontawesome.com/icons 查找
    category: "分类标识",  // llm/image/code/audio/video/productivity/writing/3d
    desc: "简短描述（20 字以内）",
    color: "text-颜色 -500",
    bg: "bg-颜色 -50"
}
```

### 修改标题

搜索 `<title>` 和 `<h1>` 标签修改网站标题。

### 更换配色

在 `<script>` 部分修改 `tailwind.config` 中的颜色配置。

## 📊 数据统计

- 工具总数：30+
- 分类数量：8
- 支持功能：搜索/收藏/深色模式/排序

## 🛠️ 技术栈

- HTML5 + Tailwind CSS (CDN)
- FontAwesome (图标库)
- Vanilla JavaScript (无框架依赖)
- LocalStorage (本地数据存储)

## 📝 待办事项

- [ ] 添加工具详情页
- [ ] 支持导入导出收藏
- [ ] 添加用户评分系统
- [ ] 多语言支持
- [ ] PWA 离线访问

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

MIT License

---

**构建时间**: 2026-03-08  
**构建者**: 技术专家助手  
**版本**: v1.0 Pro
