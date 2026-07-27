# 法考备考 Skill · Legal Exam Prep

> 帮助法学院学生通过**国家统一法律职业资格考试（法考）**的 OpenClaw Skill。
> 让考生**可查可练**，内容**权威、可溯源**。覆盖客观题 + 主观题，全 18 科目。

[English README →](./README_EN.md)

---

## 一、为什么需要这个 Skill

法考被称为"天下第一考"，其核心难点在于：

- **两阶段考试**：客观题（300分，合格成绩 2 年内有效）→ 主观题（180分，案例分析/法律文书/论述）。
- **18 个科目**：卷一（法治思想/法理/宪法/中法史/国际法/司法制度/刑法/刑诉/行政法）+ 卷二（民法/知产/商法/经济法/环境法/劳保/国际私法/国际经济法/民诉）。
- **真题不公开**：2018 年起司法部不再公布真题与标准答案，2018 年后仅有"回忆版"。练习资源缺口大。
- **权威要求高**：法律年年修订（如 2024 年新《公司法》《刑法修正案（十二）》《行政复议法》），内容必须准确、可溯源。

本 Skill 以"可查可练"为核心，帮助考生在**无官方真题**的现实下，依然能**体系化复习、精准练习、权威溯源**。

---

## 二、四大核心功能

| 模块 | 功能 | 说明 |
|------|------|------|
| **1. 考点速查** | Knowledge Lookup | 按科目 / 学科 / 考点检索，关联法条、司法解释与官方教材依据，权威可追溯 |
| **2. 客观题专项练习** | Objective Practice | 单选 / 多选 / 不定项练习，含解析、考点映射、易错分析 |
| **3. 主观题案例分析训练** | Subjective Training | 案例分析 / 法律文书 / 论述的答题思路训练与范文拆解 |
| **4. 趋势驱动模拟题** | Mock Generation | 基于大纲 + 新法修订 + 命题趋势生成高质量模拟题，填补练题缺口 |

---

## 三、权威性保障

每一处输出均标注来源，遵循分级溯源规范（详见 `references/authoritative-sources.md`）：

| 层级 | 来源 |
|------|------|
| L1 | 法律（全国人大及其常委会制定，如《民法典》《刑法》） |
| L2 | 司法解释与立法解释 |
| L3 | 行政法规与部门规章 |
| L4 | 司法部《考试大纲》+ 法律出版社《辅导用书（九大本）》等 |
| L5 | 最高人民法院指导性案例、公报案例 |
| L6 | 学术通说（仅作辅助，不作唯一依据） |

> **时效优先**：新法优于旧法。涉及修订法律的考点，一律以最新生效版本为准。

### 诚信边界
- 2018年（含）以后司法部不再公布真题与答案，仅有"回忆版"（未经官方确认）。
- 本 Skill 命制的题目**强制标注 `【模拟题 · 非真题】`**，**绝不冒充**官方真题或标准答案。
- 任何无法核实的内容，均标注 `【待核实】` 并提示以官方最新文件为准。

---

## 四、目录结构

```
legal-exam-prep/
├── SKILL.md                      # 技能主文件
├── references/                   # 8 份参考文档
│   ├── exam-system-overview.md       # 法考制度总览
│   ├── exam-syllabus-subjects.md     # 18 科目大纲详解
│   ├── objective-question-guide.md    # 客观题解题指南
│   ├── subjective-question-guide.md   # 主观题解题指南
│   ├── high-frequency-points.md       # 高频考点速查
│   ├── authoritative-sources.md       # 权威来源与溯源规范
│   ├── study-plan-templates.md        # 备考计划模板
│   └── exam-tips-strategies.md        # 应试策略与技巧
├── templates/                    # 8 个生成模板
│   ├── objective-single-template.md
│   ├── objective-multiple-template.md
│   ├── subjective-case-template.md
│   ├── subjective-document-template.md
│   ├── subjective-essay-template.md
│   ├── knowledge-point-template.md
│   ├── mock-question-template.md
│   └── mock-exam-template.md
├── examples/                     # 4 个完整示例
│   ├── sample-objective-question.md
│   ├── sample-subjective-case.md
│   ├── sample-knowledge-point.md
│   └── sample-mock-question.md
└── docs/images/                  # 7 张流程图（英文版）
    ├── system-overview-en.svg
    ├── exam-structure-en.svg
    ├── question-types-en.svg
    ├── knowledge-query-en.svg
    ├── practice-loop-en.svg
    ├── mock-generation-en.svg
    └── study-workflow-en.svg
```

---

## 五、流程图

| 图 | 内容 |
|----|------|
| `system-overview-en.svg` | 系统总览：四大模块 + 权威溯源底座 |
| `exam-structure-en.svg` | 考试结构：客观题 → 主观题 两阶段 |
| `question-types-en.svg` | 题型分布：客观题（单/多/不定项）+ 主观题（案例/文书/论述） |
| `knowledge-query-en.svg` | 考点速查流程 |
| `practice-loop-en.svg` | 练题闭环：练 → 析 → 诊 → 固 |
| `mock-generation-en.svg` | 模拟题命制流程（明确非真题标注） |
| `study-workflow-en.svg` | 备考全流程：基础 → 强化 → 客观题 → 主观题 → 拿证 |

---

## 六、使用方式

1. **速查**：向 OpenClaw 提问"善意取得的构成要件"，获取考点卡 + 法条依据。
2. **练题**：请求"出一道新《公司法》相关的客观题"，获得带解析的模拟题。
3. **主观训练**：要求"写一道民法合同纠纷的主观题案例分析示范"，获得三段式范文。
4. **规划**：让 Skill 生成"零基础 12 个月备考计划"。

---

## 七、重要声明

- 本 Skill 为**学习辅助工具**，所有内容基于公开大纲与法律文件生成。
- 本 Skill **不提供、不声称拥有**任何官方真题或标准答案。
- 模拟题仅供练习，与司法部真题无直接关联。
- 请以司法部官方公告与最新法律法规为最终依据。

---

## 八、License

本项目采用 MIT License。详见 [LICENSE](./LICENSE)。

如需引用，请参见 [CITATION.cff](./CITATION.cff)。
