# 漓雨行楷 · Liyu Xingkai

---

## 简介 · Introduction
<img width="1536" height="777" alt="漓雨行楷演示图" src="https://github.com/user-attachments/assets/f4cc2e93-4b02-4ef0-ad2e-c7261dfd1c35" />


**漓雨行楷**（Liyu Xingkai）是一款以日本开源毛笔字体「佑字【肅】」为基础开发的简体中文行楷字体。字体以广西漓江的雨为名，融合了传统楷书的端正结构与行书的自然顿挫，兼具古典气质与现代排版的适用性。

**Liyu Xingkai** is a Simplified Chinese Xingkai typeface developed upon the Japanese open-source brush font *Yuji "Syuku"*. Named after the rain over the Li River in Guangxi, it blends the structural clarity of Kaishu with the natural rhythm of Xingshu, suited to both classical aesthetics and contemporary typographic use.

---

## 字体特点 · Features

- **字符覆盖**：收录 **16,058** 个 CJK 统一汉字（总字符数约 17,721），覆盖 GB/T 2312 及 GB 18030 常用字集，并包含完整的平假名与片假名。
- **字重**：目前提供 Regular 一个字重。
- **版本**：v0.100
- **格式**：TTF（TrueType，glyf 轮廓）。

---

## 设计说明 · Design Notes

### 来源与改造 · Origin & Modifications

本字体以以下来源为基础融合开发：

| 来源 | 作者 | 授权 | 用途 |
|---|---|---|---|
| [Yuji Syuku](https://github.com/Kinutafontfactory/Yuji) | 片岡佑之（Yuji Kataoka） | SIL OFL 1.1 | 提供原始开源字体 |
| [LXGW ZhenKai](https://github.com/lxgw/LxgwZhenKai) | LXGW | SIL OFL 1.1 | 补充拉丁字母、数字、标点符号等内容 |
| [zi2zi-JiT](https://github.com/kaonashi-tyc/zi2zi-JiT) | Yuchen Tian | MIT（字体产物需注明出处） | 部分汉字由 zi2zi-JiT 生成 |


> **关于 zi2zi-JiT 的授权要求**：根据 zi2zi-JiT 的许可条款，当分发的字体产品中使用了超过 200 个由该工具生成的字符时，须注明出处。本字体符合此条件，已在致谢中列出。

### 字体版本 · Version

当前版本：**v0.100**（开发测试版）

Current version: **v0.100** (development/preview release)

---

## 安装与使用 · Installation

### 下载 · Download

前往本仓库 [Releases](../../releases) 页面，下载最新版本的 `.ttf` 字体文件。

Visit the [Releases](../../releases) page of this repository to download the latest `.ttf` font file.

---

## 已知问题 · Known Issues

- **当前版本为 v0.100 开发预览版**，部分字形结构与笔画仍在持续优化中，欢迎通过 Issues 反馈。
- **不建议用于 12pt 以下小字**：漓雨行楷的细节在极小字号下可能损失，建议正文最小 12pt，标题建议 18pt 以上。
- **Extension A / B 汉字覆盖有限**：生僻字（CJK 扩展区 A/B）仅收录少量，如有特殊需求请通过 Issues 提交。


---

## 授权协议 · License

本字体基于 **SIL Open Font License 1.1** 发布，可免费用于个人及商业用途，允许二次修改和再发布，但须保留原授权声明，且**不得单独出售字体文件本身**。

This font is released under the **SIL Open Font License 1.1**. It is free for both personal and commercial use, modification, and redistribution, provided the original license notice is retained. The font files themselves **may not be sold standalone**.

- 授权全文 · Full license text: [OFL.txt](./OFL.txt)
- SIL OFL 官网 · SIL OFL homepage: https://scripts.sil.org/OFL

---

## 致谢 · Acknowledgements

- **Yuji Kataoka（片岡佑之）** — [Yuji Syuku](https://github.com/Kinutafontfactory/Yuji) 原始毛笔字形
- **LXGW** — [LXGW ZhenKai](https://github.com/lxgw/LxgwZhenKai) 提供拉丁字母、数字以及标点符号等
- **Yuchen Tian** — [zi2zi-JiT](https://github.com/kaonashi-tyc/zi2zi-JiT) 部分汉字由 zi2zi-JiT 生成

### zi2zi-JiT Citation

```bibtex
@article{zi2zi-jit,
  title  = {zi2zi-JiT: Font Synthesis with Pixel Space Diffusion Transformers},
  author = {Yuchen Tian},
  year   = {2026},
  url    = {https://github.com/kaonashi-tyc/zi2zi-jit}
}
```

## 联系与反馈 · Contact & Feedback

如发现字形问题（结构不协调、笔画偏细/偏粗、缺字等），欢迎通过 [Issues](../../issues) 页面提交反馈，请附上：

- 字符本身
- Unicode 码位
- 问题描述或截图

If you encounter glyph issues (structural imbalance, stroke weight inconsistency, missing characters, etc.), please submit feedback via [Issues](../../issues) with:

- The character itself
- Its Unicode code point
- A description or screenshot of the problem
