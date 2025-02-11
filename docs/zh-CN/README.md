# Hexo-Stats-ECharts

<span>[![NPM Version](https://img.shields.io/npm/v/hexo-stats-echarts?color=red&logo=npm&style=flat-square)](https://www.npmjs.com/package/hexo-stats-echarts)</span>
<span>[![NPM Downloads](https://img.shields.io/npm/dm/hexo-stats-echarts?logo=npm&style=flat-square)](https://www.npmjs.com/package/hexo-stats-echarts)</span>
<span>[![License](https://img.shields.io/badge/license-%20MIT-blue?style=flat-square&logo=gnu)](https://github.com/erispyu/hexo-stats-echarts/blob/main/LICENSE)</span>

> **hexo-stats-echarts** 是一个轻量级且视觉精美的 Hexo 插件，旨在帮助你轻松地可视化和分析博客的统计数据。只需 **一行代码**，你就可以在 **任何** Hexo 页面或文章中无缝插入美观且可定制、可交互的图表。

<div align="right">
  语言:
  <a title="英语" href="../../README.md">🇺🇸</a>
  🇨🇳
</div>

## 概述

该插件基于 [Hexo Tag Plugins](https://hexo.io/api/tag) 框架，并利用强大的 [Apache ECharts 库](https://echarts.apache.org/zh/index.html)，将原始的博客统计数据（如文章发布频率、标签和分类）转化为优雅的交互式图表。

图表会根据浏览器的设置动态切换 `深色模式` 和 `浅色模式`，完美适配你的网站主题。无论你是追踪写作习惯，还是展示博客活动，该插件都能提供无缝且引人入胜的体验。

本插件灵感来源于 [hexo-graph](https://github.com/codepzj/hexo-graph)。如果你正在寻找其他解决方案，也可以试试这个！

## 安装

在你的 Hexo 项目目录中运行以下命令以安装插件：

```bash
npm install hexo-stats-echarts
```

## 支持的图表

### 热力图

通过交互式热力图可视化你的每日文章发布情况。

**快速开始**：将以下代码片段插入到 **任何** Hexo 文章或页面中：

```nunjucks
{% heatmapchart %}博客热力图{% endheatmapchart %}
```

详细使用方法和示例请访问：[热力图文档](https://blog.erispyu.fun/hexo-stats-echarts/heatmap-chart/)

### 饼图

按标签或年份可视化你的博客数据。

**快速开始**：将以下代码片段插入到 **任何** Hexo 文章或页面中：

- **按标签统计**：
```nunjucks
{% piechart tags %}标签饼图{% endpiechart %}
```

- **按年份统计**：
```nunjucks
{% piechart years %}年份饼图{% endpiechart %}
```

详细使用方法和示例请访问：[饼图文档](https://blog.erispyu.fun/hexo-stats-echarts/pie-chart/)

### 雷达图

按标签或年份可视化你的博客数据。

**快速开始**：将以下代码片段插入到 **任何** Hexo 文章或页面中：

- **按标签统计**：
```nunjucks
{% radarchart tags %}标签雷达图{% endradarchart %}
```

- **按年份统计**：
```nunjucks
{% radarchart years %}年份雷达图{% endradarchart %}
```

详细使用方法和示例请访问：[雷达图文档](https://blog.erispyu.fun/hexo-stats-echarts/radar-chart/)


## 计划中的功能 (TODO)
- [x] ~~**雷达图**：以雷达图形式展示最常用的文章标签。~~
- [] **文档更新**：添加关于热力图主题、饼图参数、文章标签黑名单和图表背景颜色配置的详细指南。
- [] **折线图**：用折线可视化每月的文章数量。
- [] **旭日图**：用旭日图可视化嵌套的文章分类。

## 反馈与支持

如果你觉得这个插件有用，请在 [GitHub](https://github.com/erispyu/hexo-stats-echarts) 上给它一个 ⭐，以表示支持并帮助更多人发现它！

欢迎贡献和新功能建议, 欢迎在 GitHub 上提交问题或拉取请求。