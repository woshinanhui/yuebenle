# 思辨入门 · 知识库整理规范

本目录把「THINK 0-2 外研思辨英语青少版（思辨入门）》各册**扫描 OCR 转写**的原始 Markdown，
重新整理成 **AI 知识库可理解的结构化 Markdown**。每册一个输出文件，按「册 → 单元 → 活动」分层。

## 来源与对应

| 输出文件 | 原始转写文件 | 覆盖范围 |
|---|---|---|
| 学生用书入门级A_结构化.md | 外研思辨英语 学生用书 入门级A | Starter + Unit 1–6 |
| 练习册入门级A_结构化.md | 外研思辨英语 练习册 入门级A | Starter + Unit 1–6 |
| 学生用书入门级B_结构化.md | 外研思辨英语学生用书 入门级（B）| Unit 7–12（书内标 Unit 1–6）|
| 练习册入门级B_结构化.md | 外研思辨英语学生包 练习册（B）| Unit 7–12（书内标 Unit 1–6）|
| 教师用书A+B_结构化.md | A+B教师用书 | 全 12 单元教学指引+答案 |

> 单元对照：B 册书内标注的 Unit 1–6，对应整套教材全书的 Unit 7–12
> （Unit1 Living for sport=全书7；Unit2 Feel the rhythm=8；Unit3 Who's hungry?=9；
> Unit4 Big successes=10；Unit5 The animal world=11；Unit6 Moving about=12）。

## 输出结构层级

- 一级标题 `# 书名`（如 `# 外研思辨英语 · 学生用书 入门级A`）＋文件头元信息块。
- 二级标题 `## 概览 CONTENTS`（原书目录摘要）与 `## UNIT n – 英文标题`（如 `## UNIT 1 – All together`）。
- 三级标题 `### 小节`：学生/练习册按需用「课时/主题」或练习册自带的板块（Grammar、Vocabulary、
  Reading、Developing Writing、Listening、Sum it up、Consolidation 等）；教师用书按「课程课时 + 
  Lesson Plan / Answer Key / Audio Script」等。
- 四级标题或加粗：单个 `Activity`／练习。

## 智能清理规则

1. **内容保真**：按原书顺序保留所有活动与正文，不删减、不杜撰、不增补。
2. **修正粘连与误识**：把 OCR 粘连单词拆分（如 `Listen tothe alphabet` → `Listen to the alphabet`、
   `Work inpairs` → `Work in pairs`），在可理解语义基础上修正拼写/大小写/断行。
3. **不确定处标注**：无法确定原文的用 `{??}` 标注，绝不臆造。
4. **保留关键信息**：音频编号（W.01、1.01、① 等）、题号、难度星号（★/★★/★★★）原样保留；
   数字选框类图标（Write 1–4 in the boxes）按指令文字保留，不需要硬凑空行让视觉复原。
5. **处理页面冗余**：不逐页保留 `第 N 页` 标题；封面/CIP/版权等非正文信息精简为一行元信息；
   栏目（Pronunciation、THINK! 价值观、Life Competencies、Culture、Review、
   Towards A2 Key for Schools 等）整理成独立子节，不丢弃。
6. **语言**：英文正文用英文，中文用中文，教学指令照实保留（中文指令给中文，英文指令给英文）。
7. **Markdown 用法**：有序/无序列表、`**加粗**`（指令、栏目标签）、`###`/`####` 层级、代码格式用于
   词汇列表或对话时用列表。保持简洁，不做过度嵌套。

## {??} 约定
- `{??}` 放在无法识别的词/段位置。
- 若一整段无法辨认，写 `[{??} 本段文字无法辨认]`。