# OceanBase & seekdb 智能运维与混合检索助手（魔搭 Skill）

> **OceanBase 2026 数据库大赛 · 生态赛题交付（魔搭社区 ModelScope）**  
> 赛题名称：上传并分享自己的 Skill（题目组: `600075`，子题 ID: `800512`）  
> 赛题分值：**20 分**  
> 核心产物：`SKILL.md`（已注入本队专属验证行）

---

## 一、Skill 简介与核心亮点

`oceanbase-seekdb-copilot` 是面向 OceanBase 及 AI 原生嵌入式分支 seekdb 的专业智能体 Skill，深度结合大赛主题技术栈：
1. **向量 + 全文 + 标量过滤的单 SQL 构造**：支持原生余弦距离算子与 BM25 全文检索的 RRF 窗口函数多路重排。
2. **全文索引与 CJK 调优指南**：针对中文切词、BlockMax 倒排跳表及内存预算分配（`memory_budget`）提供专业调优方案。
3. **PowerContext 记忆工程整合**：提供对话切片、情景记忆保存与断点恢复指南。
4. **规范与生产安全**：严格内置 YAML Frontmatter 与破坏性操作（DDL/DML）防护机制。

---

## 二、魔搭社区（ModelScope）从 GitHub 导入指引

在魔搭社区创建 Skill 时，选择 **“从 GitHub 导入”**：
- **GitHub 仓库地址**：`https://github.com/zhang0894/oceanbase-seekdb-copilot`
- **默认分支**：`main`
- **Skill 文件**：`SKILL.md`
- **验证行**：已内置 `<!-- OB-S:VX2ihxVCnH3P69UJynyIaA -->`
