# 第1周书籍电子文本化成果仓库

该仓库包含了第一周将书籍进行电子文本化处理的全部成果。

## 目录结构说明

*   `input_scanned/`
    *   该目录下存放的是通过扫描物理书籍得到的 PDF 文件。

*   `input_native/`
    *   该目录下存放的是原生的（非扫描的）PDF 文件。

*   `output_scanned/`
    *   该目录下存放的是对 `input_scanned` 目录下的扫描版 PDF 进行 OCR 识别后的结果。
    *   每个文件都提供了 **JSON** 和 **Markdown** 两种格式。

*   `output_native/`
    *   该目录下存放的是从 `input_native` 目录下的原生 PDF 中直接提取文本后的结果。
    *   每个文件都提供了 **JSONL** 和 **Markdown** 两种格式。
