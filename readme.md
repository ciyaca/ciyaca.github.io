# 《Linux 系统编程》大作业文档

[![](https://flat.badgen.net/github/status/ciyaca/ciyaca.github.io/source)]()

![](./source/_static/logo.png)

这个仓库存放大作业文档的源文件，采用 ReStructured Text 写作，Sphinx 排版。

## 使用方式

首先安装 shpinx（其他安装方式详见[官方文档](https://www.sphinx-doc.org/en/master/usage/installation.html)）:

```bash
pip install -U sphinx
```

然后生成 pdf:

```bash
make latexpdf
```

生成的文件在 `build/latex/linuxciyaca.pdf`。

