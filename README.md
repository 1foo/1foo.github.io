# Rynn Foo 的个人博客

查看模板文档：[[English]](./README-EN.md) | [[简体中文]](./README-ZH-CN.md)

## 本地测试

拉取项目代码：

```bash
git clone https://github.com/1foo/1foo.github.io.git
```

进入项目目录：

```bash
cd 1foo.github.io
```

全局安装 pnpm：

```bash
npm install -g pnpm
```

安装依赖：

```bash
pnpm i
```

启动本地开发服务器：

```bash
npm run dev
```

在 `./src/consts.ts` 文件中修改博客站点的配置，参考 [consts.ts](./src/consts.ts) 文件。

## 编写文章

### 博客文章

将您最喜欢的文章写在 `src/content/blog` 文件夹中。每个文章都应该是一个 Markdown 文件，文件开头需要包含文章的元数据，参考 [markdown-elements.md](./src/content/blog/markdown-elements.md) 和 [new-features.md](./src/content/blog/new-features.md) 两篇示例文章。

### 动态内容

在 `src/content/feed` 文件夹中编写您想发布的动态内容。每个动态项都应该是一个 Markdown 文件，文件开头需要包含动态项的元数据，参考 [2024-01-23.md](./src/content/feed/2024-01-23.md) 示例动态。

### 文章上传

文章上传有多种方法：

* 克隆到本地后，添加文章，然后提交到 GitHub 仓库的 `master` 分支。
* 直接在 GitHub 仓库的 `master` 分支中添加文章，在 [./src/content/blog](https://github.com/1foo/1foo.github.io/tree/master/src/content/blog) 或 [./src/content/feed](https://github.com/1foo/1foo.github.io/tree/master/src/content/feed) 文件夹中添加即可。
