# 成都理工大学飞跃手册

由 determine 发起的学生共建手册，面向成都理工大学，非学校官方文件。整理日期：2026-10-03。

围绕在校学习、发展选择与办理事务提供可执行的清单。内容优先，作者背景仅在个人案例中说明。

## 项目缘起与致谢

本项目受到[上海交通大学生存手册](https://github.com/SurviveSJTU/SurviveSJTUManual)与[上海交通大学飞跃手册](https://github.com/SurviveSJTU/SJTU-Application)的启发，分为成都理工大学生存指南与飞跃手册两个独立仓库，希望持续收录成都理工大学各院系同学不同出路的真实经验。

内容组织参考[南方科技大学飞跃手册](https://github.com/SUSTech-Application/2019-Fall)和[成理工程生存指南 & 飞跃手册](https://github.com/cdutetc-tieba/CDUTETC-Guide)。感谢这些项目的作者与贡献者，也感谢 Codex、Claude Code、DeepSeek Harness 等 AI 开发工具为个人学习与初版探索提供的帮助。本站实际代码与文字整理由 Codex 辅助完成；这项致谢不代表这些工具提供方参与维护或认可本站内容。

早期保留上述项目的**参考样本入口**，供投稿者理解结构与写法；这些入口标明原校与原作者，不计为成理案例。取得转载许可前不复制全文。待成理原创投稿逐步充实后，减少首页样本入口，保留来源与致谢记录。

## 从这里开始

- [升学与就业：主方案与备用方案](docs/planning/routes.md)
- [准备时间线与材料账本](docs/planning/timeline.md)
- [考研：选校、备考与复试](docs/domestic/exam.md)
- [推免、夏令营与预推免](docs/domestic/recommendation.md)
- [选导师与科研匹配](docs/domestic/supervisor.md)
- [境外申请：项目、文书与预算](docs/abroad/overview.md)
- [简历与作品集](docs/career/resume.md)
- [寻找实习与投递复盘](docs/career/internships.md)
- [面试准备与结果复盘](docs/career/interview.md)
- [人工智能、开发与交叉方向](docs/career/ai.md)
- [本科到研究生的过渡](docs/graduate/transition.md)
- [determine：2022 成理到 2026 上交](docs/experience/determine.md)

## 深入阅读

- [考研复习计划与自测方法](docs/domestic/exam-plan.md)
- [申请材料核对与公开分享边界](docs/planning/materials.md)
- [把项目变成能被理解的能力证据](docs/career/project-proof.md)
- [录取、退出与转向之后怎样复盘](docs/planning/decision-review.md)

## 使用说明
先看适用背景，再用问题清单向学院或目标单位核对。顶部支持全文搜索，侧栏提供完整导航。政策定位见[来源记录](docs/resources/sources.md)，投稿见[贡献说明](docs/contribute/index.md)。

本册通用方法已成文，真实案例目前只有作者一例。未经核实的年份、门槛与案例不编写成事实。

## 参考样本

[查看原项目样本入口](docs/resources/samples.md)

## 另一册
[成都理工大学生存指南](https://determine123.github.io/CDUT-Survival-Guide/) 独立维护，与本册互相链接。


## 在线与本地阅读
[在线阅读](https://determine123.github.io/CDUT-Application/) · [另一仓库](https://github.com/determine123/CDUT-Survival-Guide)

网页编辑无需安装工具。可选本地环境为 Python 3.12：

```sh
python -m venv .venv
# Windows PowerShell: .venv/Scripts/Activate.ps1
# macOS / Linux: source .venv/bin/activate
python -m pip install -r requirements.txt
python tools/check_links.py
python -m mkdocs serve
```

严格构建：`python -m mkdocs build --strict`。推送 main 后 Actions 构建发布；Pages 来源设置 GitHub Actions。PR 只验证，site/ 不提交。

## 投稿与许可
阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。原创文档 [CC BY 4.0](LICENSE)，参考项目注明来源，未复制其他学校内容。文字与实现使用 AI 辅助，事实来自作者确认及核查来源。
