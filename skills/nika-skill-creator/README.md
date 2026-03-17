# Nika Skill Creator

用于创建和更新符合 Nika 平台约束的技能文档。

## 功能

- 生成符合 Nika 规范的两级文档结构（主文档 + 子文档）
- 校验技能文档是否符合 Nika 约束
- 支持 @子文档名 引用格式

## 快速开始

### 1. 初始化技能骨架

```bash
python3 scripts/init_nika_skill.py "你的目标技能中文名"
```

### 2. 校验技能

```bash
python3 scripts/validate_nika_skill.py "skills/目标技能中文名"
```

## 项目结构

```
nika-skill-creator/
├── SKILL.md                    # 技能主文档
├── references/                 # 参考模板
│   ├── nika-spec.md           # Nika 平台约束规范
│   ├── main-doc-template.md   # 主文档模板
│   ├── sub-doc-template.md    # 子文档模板
│   └── validation-checklist.md # 校验清单
└── scripts/
    ├── init_nika_skill.py     # 初始化技能骨架脚本
    └── validate_nika_skill.py # 校验技能合规性脚本
```

## 参考

- [Nika 平台约束规范](references/nika-spec.md)
- [主文档模板](references/main-doc-template.md)
- [子文档模板](references/sub-doc-template.md)
