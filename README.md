# soil-fungi-drought-repro

本项目旨在复现发表于 **Nature Communications** 的研究论文：《土壤真菌在干旱期间保持活跃，并投资于储存化合物，这与未来气候条件无关》（*Soil fungi remain active and invest in storage compounds during drought independent of future climate conditions*）中的核心分析与图表。

## 📋 项目信息

- **论文题目**：土壤真菌在干旱期间保持活跃，并投资于储存化合物，这与未来气候条件无关
- **发表期刊**：Nature Communications
- **发表时间**：2024年
- **论文链接**：[https://www.nature.com/articles/s41467-024-54537-y](https://www.nature.com/articles/s41467-024-54537-y)
- **代码仓库**：[https://github.com/Mingyi-SUN/soil-fungi-drought-repro](https://github.com/Mingyi-SUN/soil-fungi-drought-repro)

## 👥 小组成员

本项目由以下成员共同完成：

- **焦静雨** (2025303120125) - @JIAOjiao0504
- **余虹** (2025303120070) - @hongyu929
- **孙铭仪** (2025303120087) - @Mingyi-SUN

## 🛠️ 复现环境

为确保代码顺利运行，请配置以下环境：

- **操作系统**：Windows
- **编程语言**：R 语言
- **环境要求**：R 版本 4.5.2 及以上，推荐使用 **Positron** IDE 进行开发与分析。

## 📂 仓库结构

仓库主要包含以下目录和文件：

- `code/`：存放复现过程中使用的 R 脚本和分析代码。
- `data/`：存放原始数据及预处理后的数据文件（数据来源于论文补充材料）。
- `results/`：存放复现生成的图表与结果文件（如 `Fig.1.png`）。
- `report.qmd`：使用 Quarto 编写的分析报告源文件，可渲染为 HTML 或 PDF。

## 🚀 复现步骤

1. **克隆仓库**（或直接下载 ZIP 包）：
2. 2. **安装依赖包**：在 R 环境中安装项目所需的包（具体包名请参考 `code/` 中的脚本或 `report.qmd`）。
3. **运行代码**：按顺序执行 `code/` 目录下的脚本，或在 Positron 中打开 `report.qmd` 直接渲染。
4. **查看结果**：复现的图表将保存在 `results/` 目录下，分析报告可通过渲染 `report.qmd` 获得。

## 📊 复现内容

本项目使用 R 语言复现了研究中的核心分析图表，包括：

- 不同气候处理下（干旱、未来气候等）土壤真菌与细菌的生长速率对比；
- 真菌在干旱期间储存化合物（如甘油三酯）的变化趋势；
- 群落水平与质量特异性生长速率的动态变化。

## ✅ 复现可行性

- 所有分析所需数据均可在论文的**补充信息文件和补充数据**中找到；
- 运行环境（R 4.5.2 + Positron）配置简单，复现可行性较高；
- 代码结构清晰，便于理解与二次修改。

## 📌 注意事项

- 请确保 R 版本 ≥ 4.5.2，避免因版本过低导致函数不兼容；
- 数据文件路径请根据本地环境适当调整；
- 如需贡献或反馈，欢迎提交 Issue 或 Pull Request。

---

> 💡 **提示**：本项目仅用于学术复现与学习交流，欢迎对本研究感兴趣的同行参与讨论与改进。
