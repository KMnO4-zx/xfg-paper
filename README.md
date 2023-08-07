# 基于论文摘要的文本分类与关键词抽取挑战赛
基于论文摘要的文本分类与关键词抽取挑战赛 https://challenge.xfyun.cn/topic/info?type=abstract-of-the-paper&ch=ZuoaKcY

# `git-lfs`安装

- 首先更新`apt-get`，防止`apt-get`命令找不到`git-lfs`

```
apt-get update
```

- `apt-get`下载`git-lfs`

```
apt-get install git-lfs
```

- 安装`git-lfs`

注意：必须先`git init`，否则阿里云的服务器`git lfs install`会失败。

聪明的你，一定会先`git init`~

```
git init
git lfs install
```

# QuickStart

- 克隆（下载）本仓库

```
git clone https://github.com/LLLM-Lab/xfg-paper.git
```

- 克隆完成后进入仓库目录

```
cd xfg-paper
```

- `pip`安装环境依赖

```
pip install -r requirements.txt
```

- 下载`ChatGLM2-6B`模型（前提是安装好了` git-lfs`）

此命令有可能会失效，下载失败可以多试几次，总有一次会成功。相信聪明的你，一定可以，加油！

```
git clone https://huggingface.co/THUDM/chatglm-6b
```

