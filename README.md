# Tokimawa_Yanhuii 个人网站

欢迎！这是你的个人作品集网站。

## 📁 文件结构

```
你的网站/
├── index.html          # 首页
├── fanworks.html       # 同人创作页面
├── original.html       # 原创世界页面
├── about.html          # 关于页面
├── styles.css          # 所有样式
├── script.js           # 交互效果
├── README.md           # 这个文件
└── images/             # 图片文件夹（需要你创建）
    ├── fanworks/       # 同人作品的图片
    └── original/       # 原创作品的图片
```

## 🚀 如何部署到 GitHub Pages

### 第一步：上传文件到 GitHub

1. 打开你的 GitHub 账号：https://github.com/sitiyamooerca-Yanhui
2. 点击右上角的 "+" 号，选择 "New repository"
3. Repository 名字**必须**是：`sitiyamooerca-Yanhui.github.io`
4. 勾选 "Public"（公开）
5. 点击 "Create repository"

6. 在新页面，点击 "uploading an existing file"
7. 把我给你的所有文件（index.html, fanworks.html, original.html, about.html, styles.css, script.js, README.md）拖拽到上传区域
8. 点击底部绿色按钮 "Commit changes"

### 第二步：等待几分钟

- GitHub 需要几分钟来构建你的网站
- 然后访问：https://sitiyamooerca-Yanhui.github.io
- 你的网站就上线了！

## 📝 如何添加内容

### 添加文字作品

1. 打开 `fanworks.html` 或 `original.html`
2. 找到 `<div class="works-grid">` 部分
3. 复制这段代码模板：

```html
<div class="work-card">
    <h3>你的作品标题</h3>
    <div class="work-meta">2024年 · 25,000字</div>
    <p class="work-excerpt">
        作品简介或开头节选...
    </p>
</div>
```

4. 修改标题、字数、简介
5. 保存文件
6. 重新上传到 GitHub（替换旧文件）

### 添加图片作品

1. 先在你的电脑上创建文件夹结构：
   ```
   images/
   ├── fanworks/
   │   ├── 图片1.jpg
   │   └── 图片2.jpg
   └── original/
       ├── 图片3.jpg
       └── 图片4.jpg
   ```

2. 把图片放进对应文件夹

3. 打开 `fanworks.html` 或 `original.html`

4. 找到 `<div class="gallery-grid">` 部分

5. 复制这段代码模板：

```html
<div class="gallery-item">
    <img src="images/fanworks/你的图片名.jpg" alt="作品名称">
    <div class="gallery-caption">
        作品名称 · 2024
    </div>
</div>
```

6. 修改图片路径和说明

7. 保存文件

8. 把整个 images 文件夹和修改后的 HTML 文件一起上传到 GitHub

### 修改"关于"页面

1. 打开 `about.html`
2. 找到内容区域，直接修改文字
3. 保存并上传

## 🎨 如何自定义样式

如果你想改颜色、字体等：

1. 打开 `styles.css`
2. 最上面的 `:root` 部分定义了所有颜色：

```css
:root {
    --midnight-blue: #0a1628;      /* 深夜蓝 */
    --deep-ocean: #132640;         /* 深海蓝 */
    --twilight-blue: #1a3a52;      /* 暮光蓝 */
    --muted-azure: #2d4f6d;        /* 柔和天蓝 */
    --silver-mist: #8b9fb5;        /* 银灰雾 */
    --frost-white: #e8eef5;        /* 霜白 */
    --accent-gold: #c9a961;        /* 金色强调 */
}
```

3. 修改这些颜色代码（可以用取色器或者搜索"颜色代码"）
4. 保存并上传

## 💡 小提示

- **图片大小**：建议每张图片不超过 2MB，这样网站加载更快
- **图片格式**：推荐用 .jpg（照片）或 .png（插画）
- **备份**：记得在自己电脑上也保留一份文件备份
- **更新**：每次修改后，去 GitHub 仓库直接上传新文件就会覆盖旧的

## ❓ 遇到问题？

- 网站没显示？等 5-10 分钟再刷新
- 图片不显示？检查路径是否正确（区分大小写）
- 样式乱了？检查 HTML 文件里的 `<link rel="stylesheet" href="styles.css">` 是否存在

## 🎉 享受你的网站！

你现在有了一个完全属于自己的作品集空间。慢慢填充内容，让它成长为你创作世界的窗口。
