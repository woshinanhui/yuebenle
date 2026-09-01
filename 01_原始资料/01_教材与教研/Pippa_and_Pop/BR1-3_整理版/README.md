# Pippa and Pop · 整理版知识库

> 来源：教材扫描件 PaddleOCR 文本，经人工深整理（修复单词粘连与错字、按单元重构结构、生成目录与索引）。
> 全库共 **12** 本，分 3 类；每本均为结构清晰的 Markdown，见 [`index.md`](index.md)。

## 目录结构

```
F:\工具\知识库\PaddleOCR_Project\output\Pippa and pop\知识库_整理版
├── README.md            # 本文件（说明）
├── index.md             # 全库索引（每本书的板块清单）
├── 01_教师用书_TeachersBooks/   # 3 本
├── 02_教材与练习册_PupilsBooks/ # 6 本
└── 03_绘本内容_BigBooks/        # 3 本
```

## 整理规范

- 每本：H1 标题 + 来源免责声明 + 目录（锚点链接）+ 正文分区。
- 修复 OCR 粘连词语（如 `Teacher'sBook` → `Teacher's Book`）与明显拼写错误；拿不准处保留并在其后标注 `[?]`。
- 移除封面/版式噪声、页码、`www.yiyaqimeng.com` 页脚水印等；封面乱码页标注「封面/插图，无法识别」。
- **未虚构内容**：仅修正 OCR 与整理版式，不增写原文没有的内容。正文多为英文，说明用中文。

## 使用提示

- 检索所需单元：打开 `index.md` 按分类/级别定位书本，再按书内板块（Unit、Review、Games Bank 等）跳转。
- 因源为 OCR，含插图/表格的页面信息有限，涉图内容请以原版为例。