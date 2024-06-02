<!-- markdownlint-disable MD033 MD036 MD041 MD045 -->
<div align="center">
  <a href="https://v2.nonebot.dev/store">
    <img src="./docs/NoneBotPlugin.svg" width="300" alt="logo">
  </a>

</div>

<div align="center">

# NoneBot-Plugin-Beauty-Rater

_✨ NoneBot2 颜值打分插件 ✨_

<a href="">
  <img src="https://img.shields.io/pypi/v/nonebot-plugin-beauty-rater.svg" alt="pypi"
</a>
<img src="https://img.shields.io/badge/python-3.10+-blue.svg" alt="python">
<a href="https://pdm.fming.dev">
  <img src="https://img.shields.io/badge/pdm-managed-blueviolet" alt="pdm-managed">
</a>

</div>

## 📖 介绍

NoneBot2 颜值打分插件，以及 i18n 支持

## 💿 安装

```bash
pip install nonebot-plugin-beauty-rater
# or, use poetry
poetry add nonebot-plugin-beauty-rater
# or, use pdm
pdm add nonebot-plugin-beauty-rater
```

打开 NoneBot 项目根目录下的配置文件, 在 `[plugin]` 部分追加写入

```toml
plugins = ["nonebot_plugin_beauty_rater"]
```

## ⚙️ 配置

在项目的配置文件中添加下表中的可选配置

> `api_key` 和 `secret_key` 可以从 [这里](https://cloud.baidu.com/product/face) 获取

| 配置项 | 必填 | 默认值 |
| :---: | :---: | :---: |
| rate__api_key | 是 | 无 |
| rate__secret_key | 是 | 无 |
| rate__timeout | 否 | 30 |

## 🎉 使用

> [!note]
> 请注意你的 `COMMAND_START` 以及上述配置项。

### 插件本体

指令名：`rate` `颜值评分` `颜值打分`

### i18n

展示支持的语言列表

```bash
/lang list
```

切换语言

```bash
/lang switch <lang>
```

### 效果图

~~理论上，这里应该有几张效果图~~

## 许可证

本项目使用 [MIT](./LICENSE) 许可证开源

```txt
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
