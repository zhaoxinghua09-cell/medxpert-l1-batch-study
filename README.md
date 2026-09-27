# MedXpert·本地模型批量精读（L1）
## 许可说明 · License Notice

- **权利状态**：本仓库以 **MIT 许可** 许可发布，可依该许可证条款自由使用、修改与再分发。
- **引用建议**：引用时请标注仓库名与原文链接 `https://github.com/zhaoxinghua09-cell/medxpert-l1-batch-study`
  与权利人「赵兴华 / Steven Zhao·China」。
- **品牌状态限定**：MedXpert、SynomosAI、LGD 等为相关项目标识，
  **均未申请实体注册、未申请商标注册**；出现仅作来源标识，
  不构成对法人实体或商标权的任何主张。
- **完整条款**：见仓库根目录 [LICENSE](LICENSE)。
- **联系**：zhaoxinghua06@126.com ｜ ORCID 0009-0001-0512-1237

---


> 用 DSH 任务桥 + 本地 qwen3.5:4b 批量精读一堆文档/知识库枢纽，逐份产出结构化摘要（核心 3 条 + 表格要点 + 疑点）并汇总疑点总表

MedXpert（美达信医疗）——医疗器械注册与国际化专业团队，让合规成为出海的第一竞争力。

## 仓库内容

本仓库为 `medxpert-l1-batch-study` 技能的发布包：核心文件 `SKILL.md` 遵循 Agent Skills 规范（YAML frontmatter），可直接放入主流 AI Agent 的技能目录使用。

- **分类**：文档处理
- **版本**：1.1.0
- **署名**：注册老炮@MedXpert
- **许可**：MIT（详见仓库 LICENSE）

## 使用方式

1. 克隆本仓库，或将技能目录放入 Agent 技能目录（如 `~/.workbuddy/skills/`）；
2. 按 `SKILL.md` 的描述与触发词调用对应能力；
3. 详细方法与模板见 `SKILL.md` 正文。

---

## 免责声明

本仓库内容为**理论站位与工具化探索**，不代表任何已获认证、已商业化交付或已服务特定客户的声明；文中涉及的外部标准、认证与条款信息为公开资料转述，正式引用前请**独立核实**。API、授权码与形象大使等为路线图（roadmap）事项，尚未上线。
