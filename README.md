# 📚 我的 Obsidian 知识库

> 一个为学生打造的个人知识管理系统，基于 Obsidian 构建

## ✨ 项目简介

这是一个精心配置的 Obsidian 知识库，专为学习和知识管理而设计。通过合理的插件组合和主题配置，帮助你更高效地记录笔记、管理知识、建立知识网络。

## 🚀 快速开始

### 1. 下载 Obsidian

访问 https://obsidian.md/download，下载并安装适合你系统的版本。

---

### 2. 克隆仓库

```bash
# 克隆模板到本地
git clone https://github.com/CK-bantang/Obsidian-Template.git
cd Obsidian-Template
```

---

### 3. 用 Obsidian 打开文件夹

启动 Obsidian，点击"打开文件夹"，选择 `Obsidian-Template` 文件夹即可开始使用！

---

## 📥 如何使用本模板

### 🎯 方式一：克隆并修改远程地址（推荐，最简单）

这种方式适合大多数用户，操作简单：

```bash
# 1. 克隆模板
git clone https://github.com/CK-bantang/Obsidian-Template.git
cd Obsidian-Template

# 2. 修改为你自己的仓库地址
git remote set-url origin <你的仓库地址>

# 例如：
# git remote set-url origin https://github.com/你的用户名/你的仓库名.git
```

**注意**：如果你没有自己的仓库，需要先在 GitHub 创建一个新仓库，然后使用新仓库的地址。

---

### 🔧 方式二：Fork（适合 GitHub 用户）

如果你熟悉 GitHub，可以 Fork 本仓库：

1. 访问本仓库页面：[https://github.com/CK-bantang/Obsidian-Template](https://github.com/CK-bantang/Obsidian-Template)
2. 点击右上角的 **Fork** 按钮
3. 将仓库 Fork 到你的账号下
4. 克隆你的 Fork 仓库：
   ```bash
   git clone https://github.com/[你的用户名]/Obsidian-Template.git
   ```

**优点**：
- ✅ 可以随时同步模板的更新
- ✅ 你拥有完全的控制权

---

### ⚠️ 重要说明

- **不要尝试直接推送到原仓库**，会因为没有权限而失败
- 如果看到 `Permission denied` 错误，说明你需要先修改远程仓库地址或 Fork
- 模板中的 Git 插件已禁用推送功能，避免误推送和错误提示

## 🎯 核心特性

- 📝 **双向链接** - 建立笔记之间的关联，构建知识网络
- 🎨 **多主题支持** - 9 款精选主题，随心切换
- 🔌 **强大插件** - 10+ 精选插件，提升笔记体验
- 📊 **可视化** - 白板、手绘图表、关系图谱等多种展示方式
- 🔄 **Git 同步** - 支持多设备同步，数据安全可靠
- 🌐 **Markdown 增强** - 支持表格、公式、代码高亮等

## 📁 文件结构

```
Obsidian-Template/
├── README.md              # 项目说明文档
├── LICENSE               # MIT 开源协议
├── .gitignore           # Git 忽略规则
├── .obsidian/           # Obsidian 配置文件夹（隐藏）
│   ├── plugins/          # 已安装的插件
│   │   ├── obsidian-git/
│   │   ├── tasks/
│   │   ├── excalidraw/
│   │   └── ...
│   └── themes/           # 已安装的主题
│       ├── Minimal/
│       ├── Blue Topaz/
│       └── ...
└── Obsidian/            # 教程和文档
    ├── 教程.md          # 完整的 Obsidian 使用教程
    ├── 讲解思路.md      # 教程大纲
    └── assets/          # 图片资源
```

## 🔌 已安装插件

### 核心插件（Obsidian 内置）

- **文件管理器** (file-explorer) - 浏览和管理文件
- **全局搜索** (global-search) - 快速搜索笔记内容
- **快速切换** (switcher) - 快速跳转到其他笔记
- **关系图谱** (graph) - 可视化笔记之间的连接
- **反向链接** (backlink) - 查看引用当前笔记的其他笔记
- **白板** (canvas) - 无限画布，自由组织想法
- **标签面板** (tag-pane) - 管理和浏览标签
- **页面预览** (page-preview) - 悬停预览链接内容
- **日记** (daily-notes) - 每日笔记功能
- **模板** (templates) - 笔记模板系统
- **大纲** (outline) - 显示当前笔记大纲
- **字数统计** (word-count) - 实时字数统计
- **工作区** (workspaces) - 保存和切换工作布局
- **书签** (bookmarks) - 收藏常用笔记和搜索

### 社区插件

#### 核心功能
- **Obsidian Git** - Git 版本控制和自动同步
- **Excalidraw** - 手绘图表和白板绘图
- **Tasks** - 强大的任务管理系统

#### 编辑增强
- **Easy Typing** - 中文输入优化，自动格式化
- **Enhanced Editing** - 编辑功能增强
- **Linter** - Markdown 格式化和规范化

#### 界面定制
- **Style Settings** - 主题样式自定义
- **Minimal Settings** - Minimal 主题专用设置
- **MySnippets** - 自定义 CSS 代码片段管理

#### 开发工具
- **BRAT** - Beta 插件测试和安装工具

#### 实用工具
- **Clear Unused Images** - 清理未使用的图片附件

[查看完整插件列表](https://github.com/obsidianmd/obsidian-releases/blob/master/community-plugins.json)

## 🎨 已安装主题

| 主题名称             | 风格    | 特点            |
| ---------------- | ----- | ------------- |
| **Minimal**      | 简约现代  | 高度可定制，性能优秀    |
| **Blue Topaz**   | 优雅蓝调  | 中文优化，功能丰富     |
| **AnuPpuccin**   | 柔和色彩  | 护眼配色，细节精致     |
| **Things**       | 清新简洁  | 类 Things 应用风格 |
| **Dracula**      | 暗色经典  | 程序员最爱的配色      |
| **Border**       | 边框设计  | 独特的视觉风格       |
| **Primary**      | 专业商务  | 适合正式场合        |
| **Typora-Vue**   | 编辑器风格 | 类 Typora 体验   |
| **Yin-and-Yang** | 阴阳平衡  | 黑白对比，禅意设计     |

**切换主题**: 设置 → 外观 → 主题

## 📖 基础教程

### 1. 创建第一个笔记

```markdown
# 我的第一篇笔记

这是一个 [[双向链接]] 示例。

## 任务列表
- [ ] 学习 Obsidian 基础
- [ ] 配置 Git 同步
- [ ] 建立知识体系

## 代码示例
​```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello Obsidian!");
    }
}
​```
```

### 2. 使用双向链接

- 输入 `[[` 开始创建链接
- 输入笔记名称，回车确认
- 点击链接可跳转或创建新笔记
- 使用 `![[笔记名]]` 嵌入整个笔记

### 3. 配置 Git 同步

1. 打开设置 → Obsidian Git
2. 配置 Git 仓库地址
3. 设置自动提交间隔（推荐 10 分钟）
4. 启用自动拉取和推送

```bash
# 手动初始化 Git（如需要）
git init
git remote add origin https://github.com/CK-bantang/Obsidian-Template.git
git add .
git commit -m "Initial commit"
git push -u origin main
```

## ❓ 常见问题

### 如何切换主题？

1. 点击左下角设置图标 ⚙️
2. 选择「外观」
3. 在「主题」下拉菜单中选择喜欢的主题
4. 可以在「Style Settings」插件中进一步自定义

### 如何添加新插件？

1. 设置 → 第三方插件
2. 关闭「安全模式」
3. 点击「浏览」
4. 搜索并安装需要的插件
5. 在「已安装插件」中启用

### 如何同步到多设备？

**方法一：使用 Obsidian Git 插件**
- 在所有设备上安装 Git
- 配置相同的远程仓库
- 启用自动同步

**方法二：使用云盘**
- 将知识库放在 OneDrive/iCloud/Dropbox
- 在其他设备上打开该文件夹

**方法三：Obsidian Sync（官方付费）**
- 最稳定但需要订阅

### 克隆后如何配置 Git 同步？

1. **先修改远程仓库地址**（必须）
   ```bash
   git remote set-url origin <你的仓库地址>
   ```

2. **打开 Obsidian 设置**
   - 点击设置图标 ⚙️
   - 找到"Obsidian Git"插件

3. **配置自动同步**
   - Auto commit interval: 30（分钟）
   - Auto push interval: 30（分钟）
   - Auto pull interval: 60（分钟）
   - Auto pull on boot: 开启

4. **首次推送**
   ```bash
   git push -u origin main
   ```

**注意**：模板中的 Git 插件已禁用推送功能，配置时需要手动启用。

### 插件显示为灰色怎么办？

**原因**：插件未启用

**解决方法**：
1. 设置 → 第三方插件
2. 找到对应的插件
3. 点击开关，启用插件
4. 重启 Obsidian（如果提示）

### 如何导入其他 Obsidian 仓库的笔记？

1. **复制笔记文件**
   - 直接复制 `.md` 文件到本仓库
   - 或者复制整个文件夹

2. **更新链接**（如果有）
   - 搜索并替换链接地址
   - 检查双向链接是否正确

3. **提交到 Git**
   ```bash
   git add .
   git commit -m "Import notes from another vault"
   git push
   ```

## 💡 使用建议

1. **从简单开始** - 不要一开始就追求完美的结构
2. **保持一致** - 建立自己的命名和组织习惯
3. **定期回顾** - 每周整理收件箱和更新链接
4. **善用模板** - 为常用笔记类型创建模板
5. **多用搜索** - Obsidian 的搜索功能很强大
6. **备份数据** - 定期备份到云端或外部硬盘

## 📝 更新日志

### 2026-02-02
- 添加完整的使用教程（下载 Obsidian、克隆仓库、打开文件夹）
- 添加详细的使用说明（Fork 和修改远程地址两种方式）
- 优化 Git 插件配置（禁用自动推送和拉取）
- 添加 MIT License 开源协议
- 优化 README 结构，提升用户体验
- 添加文件结构说明

### 2026-01-14
- 初始化知识库
- 配置 15 个精选插件
- 配置 9 款热门主题
- 移除大文件，优化仓库大小（从 40MB 降到 5MB）

---

## 🤝 贡献指南

欢迎对本项目做出贡献！如果你有改进建议或发现了 bug：

### 报告问题

1. 访问 [Issues](https://github.com/CK-bantang/Obsidian-Template/issues)
2. 点击"New Issue"
3. 详细描述问题或建议
4. 如果是 bug，请提供：
   - 复现步骤
   - 预期行为
   - 实际行为
   - 截图（如有）

### 提交代码

1. **Fork 本仓库**
   - 点击仓库右上角的"Fork"按钮

2. **创建特性分支**
   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. **提交更改**
   ```bash
   git add .
   git commit -m "Add some feature"
   ```

4. **推送到分支**
   ```bash
   git push origin feature/YourFeatureName
   ```

5. **开启 Pull Request**
   - 访问你的 Fork 仓库
   - 点击"Compare & pull request"
   - 填写 PR 描述
   - 点击"Create pull request"

---

## 📝 开发规范

- 保持代码风格一致
- 添加必要的注释
- 更新相关文档
- 确保所有链接有效
- 提交信息清晰明了

## 🔗 有用链接

- [Obsidian 官方文档](https://help.obsidian.md/)
- [Obsidian 社区论坛](https://forum.obsidian.md/)
- [Obsidian 插件商店](https://obsidian.md/plugins)
- [Obsidian 发布说明](https://forum.obsidian.md/c/announcements/12)

---

⭐ 如果这个配置对你有帮助，欢迎 Star！
💬 有问题或建议？欢迎提 Issue！
🎓 祝你学习愉快，知识管理更高效！
