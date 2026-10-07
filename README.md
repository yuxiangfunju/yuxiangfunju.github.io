<!-- 本 README 为中英对照版本：英文原文行下方紧跟中文译文。 -->
> 🌏 **中英对照 / Bilingual**：每段英文原文下方紧跟其中文译文。


<h1 align="center">
AcadHomepage
AcadHomepage　学术主页模板
</h1>

<div align="center">

[![](https://img.shields.io/github/stars/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io)
[![](https://img.shields.io/github/forks/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io)
[![](https://img.shields.io/github/issues/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io)
[![](https://img.shields.io/github/license/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io/blob/main/LICENSE)  | [中文文档](./docs/README-zh.md) 
</div>

<p align="center">A Modern and Responsive Academic Personal Homepage</p>
<p align="center">一个现代、响应式的学术个人主页模板</p>

<p align="center">
    <br>
    <img src="docs/screenshot.png" width="100%"/>
    <br>
</p>

Some examples:
示例：
- [Demo Page](https://rayeren.github.io/acad-homepage.github.io/)
- [演示页面](https://rayeren.github.io/acad-homepage.github.io/)（Demo Page）
- [Personal Homepage of the author](https://rayeren.github.io/)
- [作者个人主页](https://rayeren.github.io/)（Personal Homepage of the author）

## Key Features
## 主要特性（Key Features）
- **Automatically update google scholar citations**: using the google scholar crawler and github action, this REPO can update the author citations and publication citations automatically.
- **自动更新 Google Scholar 引用数**：借助 Google Scholar 爬虫与 GitHub Action，本仓库可自动更新作者引用数与论文引用数。
- **Support Google analytics**: you can trace the traffics of your homepage by easy configuration.
- **支持 Google Analytics**：只需简单配置即可追踪主页访问流量。
- **Responsive**: this homepage automatically adjust for different screen sizes and viewports.
- **响应式布局**：主页会自动适配不同的屏幕尺寸与视口。
- **Beautiful and Simple Design**: this homepage is beautiful and simple, which is very suitable for academic personal homepage.
- **简洁美观的设计**：页面既美观又简洁，非常适合作为学术个人主页。
- **SEO**: search Engine Optimization (SEO) helps search engines find the information you publish on your homepage easily, then rank it against similar websites.
- **SEO（搜索引擎优化）**：帮助搜索引擎更容易地找到你发布在主页上的信息，并在同类网站中获得更好的排名。

## Quick Start
## 快速开始（Quick Start）

1. Fork this REPO and rename to `USERNAME.github.io`, where `USERNAME` is your github USERNAME.
1. Fork 本仓库并重命名为 `USERNAME.github.io`，其中 `USERNAME` 是你的 GitHub 用户名。
1. Configure the google scholar citation crawler:
1. 配置 Google Scholar 引用数爬虫：
    1. Find your google scholar ID in the url of your google scholar page (e.g., https://scholar.google.com/citations?user=SCHOLAR_ID), where `SCHOLAR_ID` is your google scholar ID.
    1. 在 Google Scholar 主页网址中找到你的 scholar ID（例如 https://scholar.google.com/citations?user=SCHOLAR_ID ），其中 `SCHOLAR_ID` 即为你的 Google 学术 ID。
    1. Set GOOGLE_SCHOLAR_ID variable to your google scholar ID in `Settings -> Secrets -> Actions -> New repository secret` of the REPO website with `name=GOOGLE_SCHOLAR_ID` and `value=SCHOLAR_ID`.
    1. 在仓库页面的 `Settings -> Secrets -> Actions -> New repository secret` 中添加变量：`name=GOOGLE_SCHOLAR_ID`、`value=SCHOLAR_ID`（填你的 Google 学术 ID）。
    1. Click the `Action` of the REPO website and enable the workflows by clicking *"I understand my workflows, go ahead and enable them"*. This github action will generate google scholar citation stats data `gs_data.json` in `google-scholar-stats` branch of your REPO. When you update your main branch, this action will be triggered. This action will also be trigger 08:00 UTC everyday.
    1. 打开仓库页面的 `Action`，点击 *"I understand my workflows, go ahead and enable them"* 启用工作流。该 Action 会在仓库的 `google-scholar-stats` 分支生成引用统计数据 `gs_data.json`；每次更新 main 分支时会触发，此外每天 08:00 UTC 也会自动运行一次。
1. Generate favicon using [favicon-generator](https://redketchup.io/favicon-generator) and download all generated files to `REPO/images`.
1. 使用 [favicon-generator](https://redketchup.io/favicon-generator) 生成网站图标，并把生成的全部文件下载到 `REPO/images` 目录。
1. Modify the configuration of your homepage `_config.yml`:
1. 修改主页配置文件 `_config.yml`：
    1. `title`: the title of your homepage
    1. `title`：主页标题
    1. `description`: the description of your homepage
    1. `description`：主页描述
    1. `repository`: USER_NAME/REPO_NAME  
    1. `repository`：USER_NAME/REPO_NAME（用户名/仓库名）
    1. `google_analytics_id` (optional): google analytics ID
    1. `google_analytics_id`（可选）：Google Analytics 的 ID
    1. SEO Related keys (optional): get these keys from search engine consoles (e.g. Google, Bing and Baidu) and paste here.
    1. SEO 相关字段（可选）：从各搜索引擎站长平台（如 Google、Bing、百度）获取后粘贴到此处。
    1. `author`: the author information of this homepage, including some other websites, emails, city and univeristy.
    1. `author`：主页作者信息，包括其他网站链接、邮箱、所在城市与学校。
    1. More configuration details are described in the comments.
    1. 更多配置说明见文件内注释。
1. Add your homepage content in `_pages/about.md`.
1. 在 `_pages/about.md` 中编写主页内容。
    1. You can use html+markdown syntax just same as jekyll.
    1. 可像 Jekyll 一样使用 HTML + Markdown 语法。
    1. You can use a `<span>` tag with class `show_paper_citations` and attribute `data` to display the citations of your paper. Set the data to the google scholar paper ID. For
    1. 可用带 `show_paper_citations` class 与 `data` 属性的 `<span>` 标签显示某篇论文的引用数，`data` 填该论文的 Google 学术 ID。例如：
        ```html
        <span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span>
        ``` 
        > Q: How to get the google scholar paper ID?   
        > A: Enter your google scholar homepage and click the paper name. Then you can see the paper ID from `citation_for_view=XXXX`, where `XXXX` is the required paper ID.
1. Your page will be published at `https://USERNAME.github.io`.
1. 页面将发布在 `https://USERNAME.github.io`。

## Debug Locally
## 本地调试（Debug Locally）

1. Clone your REPO to local using `git clone`.
1. 用 `git clone` 把仓库克隆到本地。
1. Install Jekyll building environment, including `Ruby`, `RubyGems`, `GCC` and `Make` following [the installation guide](https://jekyllrb.com/docs/installation/#requirements).
1. 按[安装指南](https://jekyllrb.com/docs/installation/#requirements)安装 Jekyll 构建环境，包括 `Ruby`、`RubyGems`、`GCC` 与 `Make`。
1. Run `bash run_server.sh` to start Jekyll livereload server.
1. 执行 `bash run_server.sh` 启动 Jekyll 实时重载服务。
1. Open http://127.0.0.1:4000 in your browser.
1. 在浏览器中打开 http://127.0.0.1:4000 。
1. If you change the source code of the website, the livereload server will automatically refresh.
1. 修改网站源码后，实时重载服务会自动刷新。
1. When you finish the modification of your homepage, `commit` your changings and `push` to your remote REPO using `git` command.
1. 修改完成后，用 `git` 命令 `commit` 并 `push` 到远程仓库。

# Acknowledges
# 致谢（Acknowledges）

- AcadHomepage incorporates Font Awesome, which is distributed under the terms of the SIL OFL 1.1 and MIT License.
- AcadHomepage 使用了 Font Awesome，其按 SIL OFL 1.1 与 MIT 许可证分发。
- AcadHomepage is influenced by the github repo [mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes), which is distributed under the MIT License.
- AcadHomepage 参考了 GitHub 仓库 [mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes)，其按 MIT 许可证分发。
- AcadHomepage is influenced by the github repo [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io), which is distributed under the MIT License.
- AcadHomepage 参考了 GitHub 仓库 [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io)，其按 MIT 许可证分发。
