# 📚 我的 Obsidian 知识库

> 一个为学生打造的个人知识管理系统，基于 Obsidian 构建

## ✨ 项目简介

这是一个精心配置的 Obsidian 知识库，专为学习和知识管理而设计。通过合理的插件组合和主题配置，帮助你更高效地记录笔记、管理知识、建立知识网络。

## 🔰 手把手使用教程

如果你是第一次使用 Obsidian 和 Git，请按照以下步骤操作：

### 步骤 1：下载并安装 Obsidian

#### Windows 用户：

1. **访问 Obsidian 官网**
   - 打开浏览器，访问：https://obsidian.md/download

2. **下载 Windows 版本**
   - 点击 **Windows** 按钮（Windows 图标）
   - 会自动下载安装程序（`.exe` 文件）

3. **安装 Obsidian**
   - 双击下载的 `.exe` 文件
   - 按照安装向导的提示，点击"下一步"完成安装
   - 安装完成后，桌面上会出现 Obsidian 图标

4. **启动 Obsidian**
   - 双击桌面图标启动 Obsidian
   - 首次启动会显示欢迎页面，点击"创建新仓库"或"打开文件夹"

---

#### Mac 用户：

1. **访问 Obsidian 官网**
   - 打开浏览器，访问：https://obsidian.md/download

2. **下载 Mac 版本**
   - 点击 **macOS** 按钮（Apple 图标）
   - 会自动下载 `.dmg` 文件

3. **安装 Obsidian**
   - 双击下载的 `.dmg` 文件
   - 将 Obsidian 图标拖拽到"应用程序"文件夹

4. **启动 Obsidian**
   - 在"应用程序"文件夹中找到 Obsidian
   - 双击启动

---

### 步骤 2：下载并安装 Git（用于克隆仓库）

#### Windows 用户：

1. **访问 Git 官网**
   - 打开浏览器，访问：https://git-scm.com/download/win

2. **下载 Git 安装程序**
   - 会自动下载 `.exe` 安装文件

3. **安装 Git**
   - 双击下载的 `.exe` 文件
   - 全部点击"Next"（默认配置即可）
   - 点击"Install"开始安装
   - 安装完成后点击"Finish"

4. **验证 Git 是否安装成功**
   - 打开 **命令提示符**（按 `Win + R`，输入 `cmd`，回车）
   - 输入：
     ```bash
     git --version
     ```
   - 如果显示版本号（如 `git version 2.x.x`），说明安装成功

---

#### Mac 用户：

Mac 通常已经内置了 Git，无需额外安装。

验证是否已安装：
```bash
git --version
```

如果提示未安装，会自动弹出安装提示，点击"安装"即可。

---

### 步骤 3：克隆仓库到本地

#### 使用命令行克隆（推荐）：

**Windows 用户**：

1. **打开命令提示符**
   - 按 `Win + R`
   - 输入 `cmd`，回车

2. **导航到你想存放仓库的文件夹**
   ```bash
   # 例如：放到文档文件夹
   cd %USERPROFILE%\Documents
   ```

3. **克隆本仓库**
   ```bash
   git clone https://github.com/CK-bantang/Obsidian-Template.git
   ```

4. **进入克隆的文件夹**
   ```bash
   cd Obsidian-Template
   ```

**Mac/Linux 用户**：

1. **打开终端**
   - 按下 `Command + Space`
   - 输入 `Terminal`，回车

2. **导航到你想存放仓库的文件夹**
   ```bash
   # 例如：放到文档文件夹
   cd ~/Documents
   ```

3. **克隆本仓库**
   ```bash
   git clone https://github.com/CK-bantang/Obsidian-Template.git
   ```

4. **进入克隆的文件夹**
   ```bash
   cd Obsidian-Template
   ```

---

#### 使用 GitHub Desktop 克隆（不熟悉命令行的用户）：

1. **下载并安装 GitHub Desktop**
   - 访问：https://desktop.github.com
   - 下载并安装 GitHub Desktop

2. **登录 GitHub 账号**
   - 启动 GitHub Desktop
   - 使用 GitHub 账号登录

3. **克隆仓库**
   - 点击 **File** → **Clone Repository**
   - 在 URL 栏输入：`https://github.com/CK-bantang/Obsidian-Template.git`
   - 选择本地存放路径
   - 点击 **Clone**

---

### 步骤 4：用 Obsidian 打开文件夹

1. **启动 Obsidian**
   - 双击桌面图标启动 Obsidian

2. **打开文件夹**
   - 在欢迎页面，点击 **"打开文件夹"** 按钮
   - 导航到刚才克隆的 `Obsidian-Template` 文件夹
   - 选择该文件夹，点击 **"打开"**

   **Windows 示例路径**：
   ```
   C:\Users\[你的用户名]\Documents\Obsidian-Template
   ```

   **Mac 示例路径**：
   ```
   /Users/[你的用户名]/Documents/Obsidian-Template
   ```

3. **验证打开成功**
   - 左侧会显示文件列表（README.md、Obsidian 文件夹等）
   - 中间显示 README.md 的内容
   - 右侧显示大纲或反向链接

---

### 步骤 5：首次使用检查清单

打开 Obsidian 后，检查以下内容：

- [ ] ✅ 左侧文件列表正常显示
- [ ] ✅ 可以看到 README.md、LICENSE、Obsidian 文件夹
- [ ] ✅ .obsidian 文件夹自动加载（不会在文件列表中显示，但插件已启用）
- [ ] ✅ Obsidian 提示安装缺失的插件（如果有）
- [ ] ✅ 可以正常创建、编辑、删除笔记

---

### 🎉 恭喜！

完成以上步骤后，你已经成功：
- ✅ 安装了 Obsidian
- ✅ 下载了本模板
- ✅ 用 Obsidian 打开了知识库

现在可以开始记录你的学习笔记了！

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

### 🚀 快速开始

修改远程地址后，用 Obsidian 打开这个文件夹即可开始使用！

## 🎯 核心特性

- 📝 **双向链接** - 建立笔记之间的关联，构建知识网络
- 🎨 **多主题支持** - 9 款精选主题，随心切换
- 🔌 **强大插件** - 10+ 精选插件，提升笔记体验
- 📊 **可视化** - 白板、手绘图表、关系图谱等多种展示方式
- 🔄 **Git 同步** - 支持多设备同步，数据安全可靠
- 🌐 **Markdown 增强** - 支持表格、公式、代码高亮等

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

## 🚀 快速开始

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


## 💡 使用建议

1. **从简单开始** - 不要一开始就追求完美的结构
2. **保持一致** - 建立自己的命名和组织习惯
3. **定期回顾** - 每周整理收件箱和更新链接
4. **善用模板** - 为常用笔记类型创建模板
5. **多用搜索** - Obsidian 的搜索功能很强大
6. **备份数据** - 定期备份到云端或外部硬盘

## 📝 更新日志

- 2026-01-14: 初始化知识库，配置基础插件和主题
---

⭐ 如果这个配置对你有帮助，欢迎 Star！
💬 有问题或建议？欢迎提 Issue！
🎓 祝你学习愉快，知识管理更高效！
