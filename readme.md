
## Introduction

现实世界的数据通常都不干净。使用 Python 以及 Python 的库，可以收集各种来源、各种格式的数据，评估数据的质量和整洁度，然后进行清洗。这个过程叫做数据整理。本项目主要是在在 Jupyter Notebook 中记录并展示数据整理的过程，然后使用 Python (及其库) 和/或 SQL 进行分析和可视化。

需要整理 (以及分析和可视化) 的数据集是推特用户 @dog_rates 的档案, 推特昵称为 WeRateDogs。WeRateDogs 是一个推特主，他以诙谐幽默的方式对人们的宠物狗评分。这些评分通常以 10 作为分母。但是分子则一般大于 10：11/10、12/10、13/10 等等。为什么会有这样的评分？因为 "They're good dogs Brent." WeRateDogs 拥有四百多万关注者，曾受到国际媒体的报道。

WeRateDogs 下载了他们的推特档案，并通过电子邮件发送给优达学城，专门为本项目使用。这个档案是基本的推特数据（推特 ID、时间戳、推特文本等），包含了截止到 2017 年 4 月 1 日的 5000 多条推特。

## 我们需要什么软件？
使用这里提供的 Jupyter Notebook workspace，在优达学城课堂的 项目 workspace 页面可以完成整个项目。

如果想在优达学城课堂以外操作，你需要满足以下软件要求：

你需要在电脑上用 Jupyter Notebook 操作。请再次访问纳米学位课程中的 Anaconda 和 Jupyter Notebook 教程，作为安装指南。
需要安装下列软件包（即 Python 库）。你可以通过 conda 或 pip 安装这些库。请再次访问纳米学位课程中的 Anaconda 和 Jupyter Notebook 教程，作为文件包的安装指南。
pandas
numpy
requests
tweepy
json
你需要创建包含图片的书面文档，并且把这些文档导出为 PDF 文件。这个任务可以在 Jupyter Notebook 中进行，但是最好使用文字处理软件，如免费软件 Google Docs 或 Microsoft Word。

**同时，你可以直接打开wrangle_act.ipynb 通过源代码直接了解数据整理的过程**
