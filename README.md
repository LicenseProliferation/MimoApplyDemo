本仓库是一个用于申请Xiaomimimo token 支持的 demo 项目，主要展示整体工作流中，利用大模型构建软件许可证规则集合部分的工作，用于软件供应链合规性分析。

整体流程如下：
使用大模型解析许可证文本（自然语言）
提取关键约束（如传播、修改、专利条款等）
转换为结构化规则
汇总形成规则集合，用于兼容性分析

## 工作流

<p align="center">
  <img src="https://github.com/LicenseProliferation/MimoApplyDemo/blob/main/workflow%20of%20rule%20construction.png" width="600"/>
</p>

## 当前结果

<p align="center">
  <img src="https://github.com/LicenseProliferation/MimoApplyDemo/blob/main/License%20Term%20Taxonomy.png" width="600"/>
</p>

该 demo 主要用于验证大模型在许可证语义解析与规则建模中的能力。当前受限于 token 额度，尚无法在大规模真实项目上进行充分验证。
