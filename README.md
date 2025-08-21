# X.WEN's Bioinformatics Replication Projects

这是一个用于存放我复现各类生信（单细胞测序、空间转录组、表观遗传学等）论文分析的代码仓库

## 🗂️ 项目列表 (Projects List)

按复现时间排列：

| 项目名称 | 技术 | 状态 | 原文章/数据链接 | 主要工具 |
| :--- | :--- | :--- | :--- | :--- |
| **[2024_scRNA_seq_Lung_Cancer_Xie_et_al](./projects/2024_scRNA_seq_Lung_Cancer_Xie_et_al)** | scRNA-seq | ✅ Completed | [DOI](...) | Seurat, Scater |
| **[2023_Spatial_Transcriptomics_Brain](./projects/2023_Spatial_Transcriptomics_Brain)** | Spatial Transcriptomics | 🚧 In Progress | [GSE...](...) | Scanpy, Giotto |
| ... | ... | ... | ... | ... |

## 🚀 快速开始 (Quick Start)

1.  **克隆仓库**:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2.  每个项目都是独立的。请进入你感兴趣的项目文件夹，查看其独立的 `README.md` 文件以获取具体的环境配置和运行指南。

## 📁 仓库结构 (Repository Structure)

your-repo-name/                 # 仓库根目录
│
├── README.md                   # 总说明文件（仓库首页）
├── LICENSE                     # 开源许可证（例如MIT）
├── .gitignore                  # 告诉Git哪些文件不用上传（如大文件、临时文件）
│
├── scripts/                    # 【共享】公共脚本目录
│   ├── utilities/              # 你自己写的常用工具函数
│   │   ├── plot_utils.R
│   │   └── data_utils.py
│   └── setup/                  # 环境配置脚本
│       ├── conda_env_r.yaml    # R分析的Conda环境
│       └── conda_env_py.yaml   # Python分析的Conda环境
│
├── data/                       # 【共享】公共数据目录（存放小型、共用的数据）
│   └── reference_genomes/      # 例如，存放常用参考基因组信息
│
└── projects/                   # 【核心】所有复现项目都放在这个目录下
    │
    ├── 2024_scRNA_seq_Lung_Cancer_Xie_et_al/  # 项目1：具体名称
    │   ├── README.md           # 该项目独有的详细说明
    │   ├── config/             # 配置文件
    │   ├── src/                # 该项目的源代码
    │   ├── data/               # 该项目的数据（只放小型处理后的数据或链接）
    │   └── results/            # 该项目的结果（图片、表格等）
    │
    ├── 2024_ATAC_seq_Leukemia_Chen_et_al/     # 项目2：具体名称
    │   └── ... (类似结构)
    │
    └── template/               # 【可选】创建一个项目模板文件夹，方便未来复制粘贴
        ├── README.md
        ├── config/
        ├── src/
        ├── data/
        └── results/

## 🤝 贡献与联系 (Contributing & Contact)

这是一个个人学习项目，但非常欢迎讨论和建议，随时欢迎提交 Issue 或 Pull Request

- **邮箱**: carinotus@163.com

## 📜 许可证 (License)

这个仓库下的所有代码，除非特别说明，均基于 [MIT License](LICENSE) 开源。
