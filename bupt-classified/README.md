# 大邮分类集

《大邮分类集》以《大邮数学集》收录的相关往年题为基础，按教材章节与知识点重新编排，为每一章节配备了考点分类及常考题型，并附上（由AI生成的）详细解析。整理这份资料的目的是便于同学们节约翻找同类题型的时间，以更高效的学习、推导和查漏补缺，为期中、期末备考提供一点帮助。

本项目为独立维护的非官方分类整理。

## Demo 1.2.0

这一版补录了工科数学分析的两套期中试卷，同步了原书新版里的勘误，重新核对了分类和部分解析，排版和书写空间也一并做了调整。

- [工科数学分析更新说明](./docs/analysis/CHANGELOG.md)
- [线性代数更新说明](./docs/linear-algebra/CHANGELOG.md)

## 资料下载

| 科目 | 紧凑电子合册 | 留白电子合册 | 打印习题册 | 打印解析册 | 下载入口 |
| --- | ---: | ---: | ---: | ---: | --- |
| 工科数学分析 | 719 | 819 | 409 | 431 | [下载](https://github.com/AuroraRubbish/BuptStudyRoom/releases/tag/analysis-demo-1.2.0) |
| 线性代数 | 275 | 302 | 117 | 201 | [下载](https://github.com/AuroraRubbish/BuptStudyRoom/releases/tag/linear-algebra-demo-1.2.0) |

表中数字为对应 PDF 的实际页数。每科四个文件，均为 Demo 1.2.0。

- `electronic`：紧凑电子合册，便于阅读和批注。
- `electronic-workbook`：留白电子合册，每道题后面留了书写空间。
- `exercises-print`：打印习题册，同样留了书写空间。
- `solutions-print`：打印解析册，与习题册按题号对应。

两种电子版都有目录和书签，题目与解析、相关题与知识点之间都可以点击跳转。打印版两册之间靠页码对照，每个知识点下面都标着它在另一册里的页码；页码排在外侧，适合双面打印。

工科数学分析按《工科数学分析基础》上下册编排，线性代数按《线性代数与几何》编排。题目以《大邮数学集》Release 1.4.3 为底本；工科数学分析新增的两套期中试卷，以及两科同步的勘误，来自 Release 1.5.0。

## 来源与说明

原作是由 [fa_555](https://github.com/FA555) 及各位贡献者编辑的 [《大邮数学集》](https://github.com/ArtveFlinaInBupt/bump-archive)。感谢原编者、贡献者与赞助者的工作和支持。

本项目在原作基础上按知识点重新分类，把习题和解析编成合册，并补写了解析。解析由 AI（ChatGPT 6.1 Sol 和 Claude Opus 5.5）生成，请结合教材和自己的推导核对。

本项目沿用原作的版权口径：依法有权授权的新增原创排版、分类编排及文字说明，以及补充解析中可由整理者授权的原创内容，采用[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)许可。原作已有许可继续按其原有范围和条件适用。

原始试题、其他第三方材料、另有许可声明的资产及未随PDF发布的源代码等，不纳入上述新增内容许可。具体权利边界见各册版权页。

## 勘误与更新

发现题目、答案或排版有问题，请在本仓库 [Issues](https://github.com/AuroraRubbish/BuptStudyRoom/issues/new/choose) 用“勘误反馈”模板提交，写明科目、版本、哪个文件、页码和题号。页码请注明是 PDF 的页序，还是纸面上印的页码。

两个科目的更新记录分开维护：

- [工科数学分析更新记录](./docs/analysis/CHANGELOG.md)
- [线性代数更新记录](./docs/linear-algebra/CHANGELOG.md)
