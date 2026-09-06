# 🧬 Mutant Primer Designer



[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)



A browser-based, client-side bioanalytical application designed for **site-directed mutagenesis** plasmid mapping and custom primer design. Perform rapid sequence processing, translation verification, and custom oligonucleotide primer generation locally without uploading sensitive sequence data to remote servers.



---



## ✨ Features



**🔒 100% Client-Side Privacy:** All sequence processing, translation, and primer generation algorithms run locally in your web browser. No backend server transfers.
**🧬 Plasmid & Target Sequence Parsing:** Easily input wild-type plasmids, select specific CDS/target regions, and parse reading frames.

**🎯 Precision Site-Directed Mutagenesis:** Supports substitution, insertion, and deletion mutagenesis workflows.

**📐 Automated Primer Design:**

- Calculates melting temperature ($T\_m$), GC content, sequence lengths, and thermodynamic properties.

- Ensures overhang/flanking sequence optimization for high-efficiency PCR cloning.

**📊 Visual Feedback:** Visualizes primer overlaps, mutant codon transitions, and sequence alignments.

**💾 Export Options:** Export designed primer tables and mutagenesis summaries directly.



---



## 🚀 How to Run



No installation, build process, NodeJS, or Python environment is required!



1. Download or save the `index.html` file from this repository.

2. Double-click `index.html` or drag and drop it into any modern web browser (Chrome, Edge, Firefox, or Safari) to open and run it locally.



---



## 🛠️ Usage Workflow

1. **Upload / Paste Plasmid Sequence:** Provide your base sequence in FASTA, GenBank, or raw sequence format.

2. **Define Target Region:** Select the Coding Sequence (CDS) or target gene for mutagenesis.

3. **Specify Mutations:** Input single/multiple amino acid or nucleotide modifications (e.g., codon substitution).

4. **Configure Design Parameters:** Set preferred primer length, target Tm range, and flanking region requirements.

5. **Generate & Export:** Review generated forward and reverse primers alongside quality checks, then export the primer table.



---



## 📄 License



Distributed under the [MIT License](LICENSE).


# 🧬 突变引物设计器 (Mutant Primer Designer)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

这是一个基于浏览器的纯前端生物分析应用，专为**质粒图谱定点突变（Site-Directed Mutagenesis）及定制引物设计**而开发。无需将敏感序列数据上传至远端服务器，即可在本地快速完成序列处理、翻译验证与定制寡核苷酸引物生成。

---

## ✨ 核心功能

* **🔒 100% 本地隐私安全：** 所有序列处理、翻译及引物生成算法均在浏览器本地运行，绝不进行后端服务器传输。
* **🧬 质粒与目标序列解析：** 支持快捷输入野生型质粒，选择特定 CDS/目标区域并解析阅读框。
* **🎯 精确定点突变：** 支持替换（Substitution）、插入（Insertion）及缺失（Deletion）突变工作流。
* **📐 自动化引物设计：**
  * 计算退火温度 ($T_m$)、GC 含量、序列长度及热力学性质。
  * 优化重叠区（Overhang）与两侧序列，确保高效率 PCR 克隆。
* **📊 视觉反馈：** 实时可视化展示引物重叠区、突变密码子转换及序列比对。
* **💾 数据导出：** 支持直接导出生成的引物表格与突变汇总信息。

---

## 🚀 使用方式

无需任何安装、构建过程、NodeJS 或 Python 环境，本地直接运行：

1. 下载或保存本项目中的 `index.html` 文件。
2. 在电脑上双击 `index.html`，或直接将其拖入任意现代浏览器（Chrome、Edge、Firefox 或 Safari）中打开即可使用。

---

## 🛠️ 操作流程

1. **输入/粘贴质粒序列：** 提供 FASTA、GenBank 或纯文本格式的野生型序列。
2. **选定目标区域：** 选择编码序列（CDS）或需要突变的目标基因。
3. **设置突变位点：** 输入单个或多个氨基酸/碱基修改（如密码子替换）。
4. **配置设计参数：** 设置偏好的引物长度、目标 $T_m$ 范围以及两侧保护序列要求。
5. **生成与导出：** 查看生成的正反向引物及质量检查结果，导出引物表格。

---

## 📄 开源许可证

本项目基于 [MIT License](LICENSE) 协议开源。

