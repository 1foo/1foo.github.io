# Ryan Foo 的个人博客

🌏 Fuwari 原文档
[**中文**](https://github.com/saicaca/fuwari/blob/main/docs/README.zh-CN.md) /
[**English**](https://github.com/saicaca/fuwari/blob/main/docs/README.en.md) /
[**日本語**](https://github.com/saicaca/fuwari/blob/main/docs/README.ja.md) /
[**한국어**](https://github.com/saicaca/fuwari/blob/main/docs/README.ko.md) /
[**Español**](https://github.com/saicaca/fuwari/blob/main/docs/README.es.md) /
[**ไทย**](https://github.com/saicaca/fuwari/blob/main/docs/README.th.md) /
[**Tiếng Việt**](https://github.com/saicaca/fuwari/blob/main/docs/README.vi.md) /
[**Bahasa Indonesia**](https://github.com/saicaca/fuwari/blob/main/docs/README.id.md) (Provided by the community and may not always be up-to-date)

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

在 `./src/config.ts` 文件中修改博客站点的配置，参考 [config.ts](./src/config.ts) 文件。

上传代码之前，先在本地构建，看看是否有错误：

```bash
npm run build
```

构建完成后，预览站点：

```bash
npm run preview
```

## 编写文章

### 博客文章

将您最喜欢的文章写在 `src/content/posts` 文件夹中。每个文章都应该是一个 Markdown 文件，文件开头需要包含文章的元数据，参考 `src/content/posts` 文件夹中的示例文章。

### 特殊页面

您可以在 `src/content/spec` 文件夹中添加特殊页面，例如关于页面、联系页面等。每个特殊页面都应该是一个 Markdown 文件，文件开头需要包含页面的元数据，参考 `src/content/spec` 文件夹中的示例文章。

### 文章上传

文章上传有多种方法：

* 克隆到本地后，添加文章，然后提交到 GitHub 仓库的 `master` 分支。
* 直接在 GitHub 仓库的 `master` 分支中添加文章，在 [./src/content/posts](https://github.com/1foo/1foo.github.io/tree/master/src/content/posts) 文件夹中添加即可。
