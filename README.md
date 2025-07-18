# 📚 教育数据集汇总 (Education Dataset Collection)

欢迎来到我们的教育数据集中心！本仓库致力于为所有热衷于**通过数据推动教育创新**的研究者、开发者、教师和学生，提供一个全面、精选的公开数据集导航。

高质量、适用的数据是教育研究的第一步，也是最关键的一步。因此，我们精心梳理了来自全球的教育数据资源，涵盖从 **K-12** 到**高等教育**，从**在线学习平台**到**真实课堂交互**的广泛场景。

无论您是想构建前沿的**知识追踪模型**，探索公平而高效的**学习分析**方法，还是希望开发下一代**个性化教育工具**，我们都希望这个列表能为您节省宝贵的时间，激发您的研究灵感。

---

## 💾 数据集列表

| 名称                                                         | 备注                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [ASSISTments (2009-2010, 2012-2013, 2015, 2017)](https://sites.google.com/site/assistmentsdata/) | **ASSISTments 教育平台** 的公开数据集主要用于研究， 学生在线学习行为、教学干预效果 和 个性化教育推荐。这些数据集主要来自美国 K-12 阶段的数学教育场景，涵盖了学生的答题过程、实验干预条件和教师辅导记录等。包含14 个主要数据集。**主要包含以下字段：**1、学生信息：匿名 ID、班级、年级等。2、问题信息：题目 ID、知识点标签 3、时间戳 4、互动行为：答题次数、hint 请求、反馈类型 5、答题结果：正确/错误、答题时长 6、实验相关信息：实验 ID、干预类型、群组分配 7、拓展字段：情感标签（情绪）、教师反馈等 |
| [KDD Cup 2010](https://pslcdatashop.web.cmu.edu/KDDCup/downloads.jsp) | **KDD Cup 2010** 教育数据挖掘竞赛数据集。包含开发集和挑战集。**开发集（Development Sets）**：3 个数据集，含 2005–2007 年的完整训练 + 正确率标签。用于熟悉数据格式与模型调试。**挑战集（Challenge Sets）**：2 个数据集，训练集提供全部标签，测试集隐藏“Correct First Attempt”列。比赛期间提交模型进行预测。 |
| [OLI Engineering Statics 2011](https://pslcdatashop.web.cmu.edu/DatasetInfo?datasetId=507) | **STATICS2011（Dataset 507）** 是一份由 CMU OLI 系统采集的工科静力学课程交互数据集，包括约 333 名学生在约 1,224 道题目（步骤）上的近 20 万次答题记录，附带知识点、时间戳、答题正确性与辅助信息。它在教育技术领域中具有高度价值，被广泛用于知识追踪模型中作为经典实验基准。**主要包含以下字段：**1、匿名学生标识 2、题目id 3、知识点标签 4、提交或尝试时间 5、是否答对 |
| [JunyiAcademy Math Practicing Log](https://pslcdatashop.web.cmu.edu/DatasetInfo?datasetId=1198) | **Dataset 1198** 是一个富含标签与多样元信息的台湾数学在线练习日志，记录学生解题行为、知识点映射、答题成果与背景结构（主题/领域）等。它在 AI 教育研究（如知识追踪、学习路径推荐）方面具有很高的数据价值。如果需进一步探究完整字段列表与样本数据，可登录 DataShop 并通过 “Files” 或 “Sample Selector” 工具查看。**主要包含以下字段：**匿名学生标识、某题的标识或子步骤、知识点标签、答题时间、是否答对 |
| [slepemapy.cz](https://www.fi.muni.cz/adaptivelearning/?a=data) | **Adaptive Geography Practice** 数据集是一个大规模、高质量的真实在线学习日志，记录了超过 90,000 名地理学习者在自适应练习系统中的行为。它不仅能支持常见的知识追踪研究，也非常适用于探索学习记忆、反应时间分析与系统优化策略验证，是一个教育数据挖掘与自适应学习领域的经典资源。**主要包含以下字段：**匿名用户 ID、问题 ID、答题时间、回答是否正确、题型。 |
| [synthetic](https://github.com/chrispiech/DeepKnowledgeTracing/tree/master/data/synthetic) | 用来支持 **Deep Knowledge Tracing (DKT)** 模型实验的 **合成模拟数据集**，用于测试模型在已知结构的理想环境下的表现。数据规模适中（几千学生、数万交互），配置里设置知识概念个数和IRT示例方式，便于控制干预实验。 |
| [EdNet](https://github.com/riiid/ednet)                      | **EdNet** 是由 Riiid 发布的大规模在线教育数据集，收集了约 78 万名学生在 TOEIC 练习平台上的 1.3 亿条交互记录。数据涵盖答题行为、视频学习、购买操作等多种类型，支持知识追踪、路径推荐与学习行为建模等研究。其分层结构与丰富字段使其成为教育人工智能领域的重要基准数据集，广泛用于学术研究与竞赛。**主要包含以下字段：**匿名用户 ID、学习内容编号（题目/讲座）、交互时间戳、答题结果、行为类型（例如题目回答、视频浏览、课程购买）、行为持续时间（如视频观看时长）、对应的知识点标签、是否从推荐系统被展现 |
| [pisa2015math](https://drive.google.com/drive/folders/1ja9P5yzeUDyzzm748p5JObAEs_Evysgc) | **PISA 2015 Math** 数据集涵盖学生答题成绩（10 值多重赋值）、详尽背景变量（学生/家庭/学校/教师）、题目信息和权重设计，支持国际比较、教育分析和模型研究。适合用于统计分析、建模、政策评估及机器学习研究。PISA 2015 的数学数据主要包括以下几类文件：学生成绩数据、背景问卷（学生层面）、学校与教师问卷、测试题目信息、数据格式与使用 |
| [critlangacq](https://drive.google.com/drive/folders/1ja9P5yzeUDyzzm748p5JObAEs_Evysgc) | **CritLangAcq** 是一个用于研究第二语言习得关键期的教育数据集，包含大量用户在语言学习任务中的表现数据。该数据集由 Stanford 大学的 Chris Piech 等人创建，旨在探讨语言学习能力与年龄之间的关系。**主要包含以下字段：**用户 ID、题目 ID、回答正确性、年龄 |
| [math23k](http://base.ustc.edu.cn/data/math23k.zip)          | **Math23K** 是一个中文数学应用题数据集，包含 23,164 个小学数学应用题，主要用于数学问题求解（Math Word Problem Solving, MWPS）研究。该数据集由腾讯 AI Lab 于 2017 年发布，广泛应用于自然语言处理（NLP）和教育 AI 领域。**主要包含以下字段：**问题编号、原始问题文本、分词后的文本、数学方程式、答案 |
| [MOOCCube](http://moocdata.cn/data/MOOCCube)                 | **MOOCCube** 是一个面向大规模在线开放课程（MOOC）研究的开放数据仓库，旨在为自然语言处理（NLP）、知识图谱构建、数据挖掘等领域的研究者提供丰富的教育数据资源。**MOOCCube 的主要包含以下字段：**1、课程信息：包括课程 ID、名称、简介、授课教师、开课机构等。2、视频信息：包括视频 ID、标题、时长、字幕文本等。3、概念信息：包括概念 ID、名称、定义、所属学科、相关论文等。4、学生行为记录：包括学生 ID、观看视频的时间戳、观看时长、学习进度等。 |
| [NIPS2020](https://www.microsoft.com/en-us/research/academic-program/diagnostic-questions/) | **Diagnostic Questions** 是微软研究院于 2020 年主办的 NeurIPS 教育挑战赛所使用的数据集，旨在通过分析学生对教育性多项选择题（MCQ）的回答，深入了解学生的误解类型，并推动个性化学习的自动化。该数据集的核心数据结构包括：1、**学生信息**：匿名化的学生 ID、年龄、性别、是否享受免费午餐等 2、**题目信息**：题目 ID、文本内容、所属学科、子主题、题目层级结构 3、**回答记录**：学生对特定题目的回答（A、B、C 或 D）、回答时间戳、学生对答案的信心程度 4、**作业信息**：题目所属的测验、班级、是否属于更长的教学计划等 |
| [OpenLUNA](http://base.ustc.edu.cn/data/OpenLUNA/)           | **OpenLUNA** 是中国科技大学（USTC）发布的一个教育数据集，旨在为教育领域的研究人员提供丰富的学习数据资源，特别是在学生学习行为分析和教育数据挖掘方面。OpenLUNA 数据集的核心数据结构包括：1、**学生信息**：匿名化的学生 ID、年级、性别等 2、**学习行为记录**：学生在学习平台上的操作记录，如登录时间、学习时长、完成的任务等 3、**任务信息**：任务 ID、任务类型、任务难度等 |
| [ASSISTments 2009-2020](https://drive.google.com/drive/folders/0B8VPP_XVUjoaaGhvOV9rVERrY0E?resourcekey=0-L4-rsmCvBht-Sp_kQzjbiQ) | **ASSISTments Data Mining Competition Dataset** 是由美国 ASSISTments 教育平台于 2017 年举办的数据挖掘竞赛所使用的公开数据集。**主要包含以下字段：**1、**学生行为记录**：每条记录包含学生在 ASSISTments 平台上完成数学题目的行为数据，如作答时间、是否答对、所用提示次数等 2、**学生信息**：匿名化的学生 ID、性别、年级等 3、**题目信息**：题目 ID、所属知识点、难度等 4、**目标变量**：学生毕业后第一份工作是否属于 STEM 领域（1 表示是，0 表示否） |
| [TalkMoves](https://github.com/sumnerlab/talkmoves)          | **TalkMoves 数据集** 是由 SumnerLab 团队构建的一个 K–12 数学课堂对话数据集，旨在深入分析教师与学生在课堂讨论中的互动模式，尤其关注“谈话移动”（talk moves）在促进学生参与和数学理解方面的作用。包含 567 篇由人工注释的 K–12 数学课堂教学转录文本，涵盖完整课程或课程片段。所有转录文本还被标注了对话行为标签（dialogue acts）。 |
| [TIMSS ](https://www.timssvideo.com/)                        | **TIMSS Video Study**包含超过 1,000 节八年级数学和科学课堂的录像，涵盖 7 个国家。1、内容包括：每节课的完整录像，展示教师的教学活动和学生的互动过程 2、对课堂录像的逐字转录，便于文本分析和对比研究 3、包括教师使用的教材页面、教案、学生作业等材料 4、收集教师和学生的背景信息、教学理念和学习态度等数据 5、用于分析课堂教学的观察量表和评分标准 |
| [Dana Center](https://www.utdanacenter.org/)                 | Dana Center 不提供特定的**原始课堂或行为日志数据**，而是通过设计教学框架、教育资源和专业培训，推动数学教育体系的改革与发展。它是推动 K–16 整体教学卓越的策略中枢，尤其在课程路径设计、教育公平和教师支持方面发挥着核心作用。包含少量但是详细的课程视频，视频转录的文字、教师使用的教材页面、教案、学生作业。 |
| [The NCTE Transcripts](https://github.com/ddemszky/classroom-transcript-analysis) | **NCTE Transcripts** 数据集是目前**最大规模的美国小学数学课堂转录文本数据集。1,660 个完整的 45-60 分钟小学4-5 年级数学课堂录音转录文本。数据集包括：1、课堂评分（使用 CLASS 和 MQI 两个权威观察工具评分） 2、学生数据（成绩、人口统计、问卷调查） 3、教师数据（背景、经验、学历、信念、教学实践问卷） 4、价值增值分数（教师对学生成绩增长的估计贡献） 5、课堂对话标注（每轮对话是否包含以下五种“教学话语行为”） |
| [CS1QA](https://github.com/cyoon47/CS1QA)                    | **CS1QA**是一个包含 9,237 个问答对的编程教育问答数据集，附带学生代码、问题类型标注和与问题相关的代码行，旨在推动代码理解和教育问答系统的发展。 |
| [SIGHT](https://github.com/rosewang2008/sight)               | **SIGHT** 是一个大规模的教育数据集，收录了 MIT 数学公开课的 288 个讲座转录文本和 15,784 条学生评论，并开发了一套基于大语言模型（LLM）的自动化注释方法，用于提炼学生反馈，帮助教师改进教学。 |
| [DataShop > 主页](https://pslcdatashop.web.cmu.edu/)         | **PSLC DataShop** 汇聚了来自真实智能辅导系统的大规模学生互动数据，内容包含各种学科、研究项目与模型结果，适合教育数据挖掘、认知建模与学习科学研究。 |
| [MOOCCubeX/README-cn.md at main · THU-KEG/MOOCCubeX](https://github.com/THU-KEG/MOOCCubeX/blob/main/README-cn.md) | **MOOCCubeX**收集了多样化的MOOC资源和外部教育资源，以及学生的学习、练习和讨论的数据记录。它是面向大规模在线教育（如慕课）的**异构图数据集**，旨在构建更加复杂和真实的学习场景。它集成了课程、知识点、视频、题目、学生、行为等多种实体和关系。主要字段：user、course、video、exercise、concept、teacher、logs。 |

---

## 📖 如何使用

点击“名称”或“地址”栏中的链接即可访问数据集的主页或下载页面。在使用数据时，请务必参考原始数据来源的引用政策和使用要求。

## 🤝 如何贡献

欢迎您为这个项目做出贡献！如果您知道其他应被收录的教育数据集，请通过以下方式之一告知我们：
1.  **提交 Issue**：在项目的 Issue 页面提出建议。
2.  **提交拉取请求 (Pull Request)**：
    - Fork 本仓库。
    - 在 `Education Database.md` 文件中添加新的数据集信息。
    - 创建一个新的 Pull Request。

## 📄 许可证

本列表的组织和呈现方式采用 [MIT 许可证](https://opensource.org/licenses/MIT)。

**请注意**：各个数据集本身拥有独立的许可证，请在使用前务必查阅并遵守其具体规定。 