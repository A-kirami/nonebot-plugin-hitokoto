<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot-plugin-hitokoto

_✨ 总有一句话能打动你的心 ✨_


<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/A-kirami/nonebot-plugin-hitokoto.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/nonebot-plugin-hitokoto">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-hitokoto.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="python">

</div>

## 📖 介绍

不论在哪里，总有那么几个句子能穿透你的心。把这些句子汇聚起来，传递更多的感动。简单来说，一言指的就是一句话，可以是动漫中的台词，也可以是网络上的各种小段子。留下你所喜欢的那一句话，与大家分享，这就是一言存在的目的。

数据来源于[Hitokoto](https://hitokoto.cn/)

## 💿 安装

<details>
<summary>使用 nb-cli 安装</summary>
在 nonebot2 项目的根目录下打开命令行, 输入以下指令即可安装

    nb plugin install nonebot-plugin-hitokoto

</details>

<details>
<summary>使用包管理器安装</summary>
在 nonebot2 项目的插件目录下, 打开命令行, 根据你使用的包管理器, 输入相应的安装命令

<details>
<summary>pip</summary>

    pip install nonebot-plugin-hitokoto
</details>
<details>
<summary>pdm</summary>

    pdm add nonebot-plugin-hitokoto
</details>
<details>
<summary>poetry</summary>

    poetry add nonebot-plugin-hitokoto
</details>
<details>
<summary>conda</summary>

    conda install nonebot-plugin-hitokoto
</details>

打开 nonebot2 项目的 `bot.py` 文件, 在其中写入

    nonebot.load_plugin('nonebot_plugin_hitokoto')

</details>

<details>
<summary>从 github 安装</summary>
在 nonebot2 项目的插件目录下, 打开命令行, 输入以下命令克隆此储存库

    git clone https://github.com/A-kirami/nonebot-plugin-hitokoto.git

打开 nonebot2 项目的 `bot.py` 文件, 在其中写入

    nonebot.load_plugin('src.plugins.nonebot_plugin_hitokoto')

</details>

## 🎉 使用
### 指令表
| 指令 | 说明 |
|:-----:|:----:|
| 一言 | 来一条一言 |
