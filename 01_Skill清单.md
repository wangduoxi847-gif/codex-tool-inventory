# Codex Skill 清单

盘点日期为 2026 年 11 月 25 日（北京时间）。

**126 个，全部启用。** Skill 是按需加载的工作说明，可能附带脚本、模板和验收步骤。

本机扫描包括 100 个顶层本地 Skill、2 个本地示例、6 个系统 Skill 和 18 个插件随附 Skill。云端插件按会话提供的额外 Skill 以对应会话为准。

## 个人助理与本机维护（16 项）

| Skill | 来源 | 作用 |
| --- | --- | --- |
| `wang-duoxi-toolbox:wang-duoxi-assistant` | 插件 | 按你的偏好和协作规则处理任务，按需读取个人档案与工具索引。 |
| `wang-duoxi-toolbox:codex-health-check` | 插件 | 只读检查 Codex 的运行时、配置、Skill、插件、MCP 和权限。 |
| `wang-duoxi-toolbox:task-handoff` | 插件 | 整理任务进度、交付物和后续提示，供新聊天或其他助手接续。 |
| `keep-codex-fast` | 本地 | 报告 Codex 的会话、日志和工作树占用，并支持可恢复的本机维护。 |
| `wd-app-tuning` | 本地 | 调整浏览器和手机应用的通知、首页、同步及阅读体验。 |
| `wd-daily-brief` | 本地 | 整理 AI、考研、编程副业与上海就业简报，核对定时交付。 |
| `wd-document-handoff` | 本地 | 核对课程作业的模板、局部修改、跨文件一致性和打印交付要求。 |
| `wd-mail-reconcile` | 本地 | 对 Gmail 或 QQ 邮箱做可恢复的整理，并逐封核对结果。 |
| `wd-network-check` | 本地 | 分层排查代理、TUN、丢包、重连和网页访问速度。 |
| `wd-study-review` | 本地 | 按真实做题、错题和时长做考研复盘，调整下一阶段安排。 |
| `wd-windows-care` | 本地 | 盘点磁盘、迁移数据、检查后台与自启，并验收清理结果。 |
| `wd-workflow-miner` | 本地 | 回看获得授权的历史任务，把可复用做法整理到 Skill，核对重复项。 |
| `define-goal` | 本地 | 把模糊目标整理成可衡量、可验收的任务目标。 |
| `discernment-nudge` | 本地 | 在有实际决策影响的答案后补能检验关键假设的问题。 |
| `deepseek-cache-max` | 本地 | 针对 DeepSeek 模型优化提示词缓存、上下文复用及 token 开销。 |
| `create-statusline` | 系统 | 为 Codex CLI 设计和启用自定义终端状态栏。 |

## 文档、演示、图像与影音（21 项）

| Skill | 来源 | 作用 |
| --- | --- | --- |
| `documents:documents` | 插件 | 创建、编辑、批注、修订和渲染核验 Word 文档。 |
| `docx` | 本地 | 在本地处理 Word 文件与模板，附带批注、修订和结构校验脚本。 |
| `doc-coauthoring` | 本地 | 协作编写文档、提案、规范和决策说明，从梳理结构到读者复核。 |
| `internal-comms` | 本地 | 写团队更新、内部简报、FAQ 等内部沟通材料。 |
| `pdf:pdf` | 插件 | 生成、提取、渲染和检查 PDF，也支持可填写表单。 |
| `presentations:Presentations` | 插件 | 创建或编辑演示文稿，按 Spaces、PowerPoint 或 Google Slides 的交付目标走相应流程。 |
| `pptx` | 本地 | 本地创建、读取、编辑以及验证 PowerPoint 文件和模板。 |
| `ppt-document-converter` | 本地 | 为 PPT、PDF、图片和讲稿转换提供流程与验收清单。 |
| `ppt-speech-writer` | 本地 | 按真实幻灯片逐页写讲稿，可将讲稿写入演讲者备注。 |
| `image-to-editable-ppt` | 本地 | 把截图、扫描版 PDF 或图片型幻灯片还原成可编辑的 PPT 对象。 |
| `beamer-academic` | 本地 | 用 LaTeX Beamer 制作论文汇报、答辩和学术演示。 |
| `template-creator:template-creator` | 插件 | 把参考材料提炼成后续可反复使用的文档、演示或其他交付模板。 |
| `canvas-design` | 本地 | 制作海报、封面等静态设计，交付 PNG 或 PDF。 |
| `brand-guidelines` | 本地 | 把 Anthropic 的品牌色、字体和风格应用到指定材料。 |
| `theme-factory` | 本地 | 为文档、幻灯片、报告或网页选用并应用配色与字体主题。 |
| `algorithmic-art` | 本地 | 用 p5.js 和可复现随机种子创作交互式生成艺术。 |
| `imagegen` | 系统 | 生成或编辑照片、插画、素材、透明 PNG 等位图。 |
| `slack-gif-creator` | 本地 | 制作或压缩适合 Slack 使用的动图。 |
| `speech` | 本地 | 把文字转成音频，用于配音、旁白和朗读。 |
| `transcribe` | 本地 | 把录音或视频转为文字，可附说话人标记。 |
| `lecture-to-notes` | 本地 | 把课程视频整理成带插图的 LaTeX 笔记并编译 PDF。 |

## 表格、分析、研究与信息检索（16 项）

| Skill | 来源 | 作用 |
| --- | --- | --- |
| `spreadsheets:Spreadsheets` | 插件 | 制作和修改 Excel、CSV 等表格，处理公式、格式、图表与结果核验。 |
| `spreadsheets:excel-live-control` | 插件 | 操作已连接的 Excel 实时会话或打开中的工作簿。 |
| `xlsx` | 本地 | 本地创建、清理和修改电子表格，附带公式重算和验证脚本。 |
| `data-analysis-skill` | 本地 | 分析 CSV、Excel 等数据，做探索、统计检验和报告，可产出交互式 HTML。 |
| `jupyter-notebook` | 本地 | 创建或整理可交互运行的 Jupyter Notebook。 |
| `visualize:visualize` | 插件 | 制作会话内交互图，让读者探索关系、情景或参数变化。 |
| `engineering-figure-agent` | 本地 | 制作工程架构图、科研流程图、基准比较和可发表的图表。 |
| `anysearch` | 本地 | 执行网页或垂直搜索、批量检索和网页内容提取。 |
| `people-search` | 本地 | 按职位、公司和行业搜索人员、候选人或企业资料。 |
| `cnki-mcp:cnki-research` | 插件 | 上游设计用于知网题录、引文和文献处理。当前按你的规则，仅使用你手动提供的知网资料。 |
| `paper-lifecycle` | 本地 | 从论文选题、文献和提纲推进到方法、修订及 GB/T 7714 参考文献。 |
| `review-revision` | 本地 | 从同行评审角度核对论文的论据、方法、实验、统计和可复现性。 |
| `rebuttal-response` | 本地 | 逐条拆解审稿意见，拟定回复与修改清单。 |
| `notion-knowledge-capture` | 本地 | 把对话、决策和经验整理成 Notion 知识条目。 |
| `notion-research-documentation` | 本地 | 从 Notion 资料汇总调研结果，写简报、对比和研究文档。 |
| `lessie-email` | 本地 | 通过对应服务管理邮箱、草稿和邮件工作流。 |

## 开发、评审与工具集成（30 项）

| Skill | 来源 | 作用 |
| --- | --- | --- |
| `agents-template` | 本地 | 编写、审查或精简 AGENTS.md 项目指令。 |
| `adversarial-execution` | 本地 | 在实现接近交付时，从独立视角复查实现与验收证据。 |
| `code-reviewer` | 本地 | 审查改动中的缺陷、回归、测试缺口和可维护性问题。 |
| `review-agent` | 系统 | 接收明确的代码审查任务，按可操作性提报缺陷。 |
| `complexity-optimizer` | 本地 | 找出算法和性能热点，并给出保持现有行为的优化方法。 |
| `security-best-practices` | 本地 | 按语言与框架审查代码的安全实践，提供防御性修复建议。 |
| `pm-dev-workflow` | 本地 | 把功能需求串成产品范围、实现、测试和交付流程。 |
| `ponytail` | 本地 | 寻找满足要求的最简实现，控制新增代码和依赖。 |
| `codex-subagent-planner` | 本地 | 按任务拆分、评审需要和并行性规划子代理角色。 |
| `gh-address-comments` | 本地 | 按 GitHub PR 的反馈逐条定位并处理评审意见。 |
| `gh-fix-ci` | 本地 | 查看 GitHub Actions 失败记录，定位并修复 CI 问题。 |
| `github-scout` | 本地 | 查找并评估 GitHub 项目的用途、维护情况和接入成本。 |
| `codex-skill-miner` | 本地 | 从开源仓库提取可复用流程，整理并校验成 Codex Skill。 |
| `yeet` | 本地 | 执行已明确要求的 Git 暂存、提交、推送及创建 PR 流程。 |
| `skill-creator` | 系统 | 创建或改进 Skill 的触发条件、步骤、脚本和参考资料。 |
| `skill-installer` | 系统 | 从指定来源列出或安装 Codex Skill。 |
| `mcp-builder` | 本地 | 设计并实现 MCP 服务器、工具定义和服务集成。 |
| `cli-creator` | 本地 | 把 API、现有脚本或服务封装成可组合的命令行工具。 |
| `chatgpt-apps` | 本地 | 构建或排查由 MCP 服务器和网页组件组成的 ChatGPT 应用。 |
| `openai-docs` | 系统 | 查 OpenAI 官方资料，回答 API、Codex 和 Work 使用问题。 |
| `openai-cookbook-workflows` | 本地 | 用官方示例实现或排查 OpenAI API、Agents、工具调用和结构化输出。 |
| `claude-api` | 本地 | 处理 Anthropic API、SDK、模型调用和工具集成。 |
| `academy-guide` | 本地 | 为 Claude 产品的问题匹配学习课程、教程或入门资源。 |
| `frontend-design` | 本地 | 规划和改善页面的视觉方向、排版与界面细节。 |
| `web-artifacts-builder` | 本地 | 用 React 等工具制作带状态和多组件的 HTML 应用。 |
| `playwright` | 本地 | 用 Playwright CLI 自动化网页导航、表单和界面检查。 |
| `playwright-interactive` | 本地 | 保留浏览器或 Electron 会话，方便多轮界面迭代调试。 |
| `webapp-testing` | 本地 | 测试本地 Web 应用，支持服务联测、截图和浏览器日志。 |
| `computer-use:computer-use` | 插件 | 通过 Windows 界面操作可访问的桌面应用。 |
| `screenshot` | 本地 | 按需获取指定桌面、窗口或屏幕区域截图。 |

## 数学建模与论文流水线（27 项）

| Skill | 来源 | 作用 |
| --- | --- | --- |
| `workflow-orchestrator` | 本地 | 安排数模竞赛从读题到成稿的阶段，并追踪依赖和验收状态。 |
| `problem-parser` | 本地 | 拆解每一问的目标、数据、约束和要求交付的结果。 |
| `problem-classifier` | 本地 | 把子题归为预测、优化、评价等建模类型。 |
| `related-paper-analyzer` | 本地 | 检索和比较相关论文与报告，提取能借鉴的方法。 |
| `symbol-table-builder` | 本地 | 统一题目、代码和论文中各变量的符号及含义。 |
| `data-auditor-cleaner` | 本地 | 核查并处理赛题数据的缺失、重复、异常和量纲。 |
| `method-selector` | 本地 | 比较备选模型的适配度、解释性和实施代价。 |
| `model-assumptions-builder` | 本地 | 梳理共同建模假设、简化条件和适用边界。 |
| `decision-prompt-builder` | 本地 | 提出必须由建模者取舍的关键问题。 |
| `modeler-decision-logger` | 本地 | 记录并定版建模者已确认的选择，供后续引用核对。 |
| `model-code-analyzer` | 本地 | 把选定算法整理成语言无关的流程、模块和输入输出规格。 |
| `python-model-code-generator` | 本地 | 按验证过的方案生成可运行的 Python 建模代码。 |
| `matlab-model-code-generator` | 本地 | 按验证过的方案生成 MATLAB 或北太天元兼容代码。 |
| `python-code-reviewer` | 本地 | 审查 Python 建模代码与方法、数据和预期产物是否一致。 |
| `matlab-code-reviewer` | 本地 | 核查 MATLAB 或北太天元代码能否正确实现选定方案。 |
| `robustness-checker` | 本地 | 运行或设计敏感性、鲁棒性、误差和基线对照。 |
| `result-report-generator` | 本地 | 汇总模型实验指标并解释各方法的结果差异。 |
| `figure-table-planner` | 本地 | 安排支撑核心论证的图表，确定每张图要回答的问题。 |
| `math-figure-generator` | 本地 | 使用 Matplotlib 绘制数模论文所需的曲线、预测图和对比图。 |
| `final-method-explainer` | 本地 | 整理最终方法、取舍、假设和实现证据，供论文作者复用。 |
| `solution-package-builder` | 本地 | 把最终方法、实验和支撑材料合成可续写的论文交接包。 |
| `paper-section-writer` | 本地 | 按已核实的方法、数据和图表起草数学建模论文章节。 |
| `paper-polisher` | 本地 | 润色数模论文，校对术语、符号、公式和结论表述。 |
| `reference-manager` | 本地 | 核实数模论文参考文献、BibTeX 和正文引用是否对应。 |
| `consistency-auditor` | 本地 | 交叉核对论文、代码、数据、图表和附录中的数字与符号。 |
| `completeness-auditor` | 本地 | 检查各步骤声称完成的审查材料和验收项是否确实存在。 |
| `quality-assurance-auditor` | 本地 | 提交前复核整套数模成品，找出影响交付的缺陷。 |

## Mem0 记忆（12 项）

| Skill | 来源 | 作用 |
| --- | --- | --- |
| `mem0` | 本地 | 为应用接入 Mem0 平台的 SDK、记忆写入和检索。 |
| `mem0-cli` | 本地 | 通过 Mem0 的命令行工具执行记忆相关操作。 |
| `mem0-integrate` | 本地 | 给现有代码库接入 Mem0 记忆层。 |
| `mem0-oss-to-platform` | 本地 | 把 Mem0 开源自托管接入迁移到托管平台 API。 |
| `mem0-test-integration` | 本地 | 检查已有 Mem0 集成的依赖、测试和记忆读写。 |
| `mem0-vercel-ai-sdk` | 本地 | 为 Vercel AI SDK 集成 Mem0 记忆能力。 |
| `mem0:forget` | 插件 | 在明确请求后删除该用户和仓库的 Mem0 记忆。 |
| `mem0:pause` | 插件 | 暂停本机 Mem0 记忆采集。 |
| `mem0:remember` | 插件 | 记录用户明确要求记住的事项。 |
| `mem0:resume` | 插件 | 恢复已暂停的 Mem0 记忆采集。 |
| `mem0:search` | 插件 | 按任务需要检索以往保存的 Mem0 记忆。 |
| `mem0:status` | 插件 | 检查 Mem0 的配置、采集状态和待同步记录。 |

## 思考视角与材料分析（4 项）

| Skill | 来源 | 作用 |
| --- | --- | --- |
| `cangjie` | 本地 | 从提供的书、访谈或文章中提炼一个人的决策和思考方法。 |
| `adler-perspective` | 本地示例 | 借阿德勒心理学视角分析人际关系、自卑和个人选择。 |
| `paul-graham-perspective` | 本地示例 | 借 Paul Graham 的思考视角分析创业、产品、工作与成长。 |
| `funeralai` | 本地 | 用证据拆解项目、文章或产品的实际能力与局限。 |
