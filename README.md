# smallscreen-diy

个人 DIY 素材仓库：存放 AI 手帐生成 skill 与后续生成的素材成品。

## 仓库结构

```
smallscreen-diy/
├── skills/
│   └── salt-journal-materials/   # 盐系手帐素材生成 skill（来源：carolinaaafy/salt-journal-materials）
└── journal-outputs/              # 每次生成的手帐素材页归档（按日期-主题建目录）
```

## skills/salt-journal-materials 是什么

一个「盐系手帐素材」生成 skill：给一段日常、一种心情或一个配色，生成一页可打印裁切的
手帐素材（素材纸、便签、纸条、胶带、小装饰），需要时还能继续用同一套素材做拼贴灵感参考。

## 如何在新环境恢复使用

1. 克隆或下载本仓库；
2. 把 `skills/salt-journal-materials/` 整个文件夹复制到 WorkBuddy 的用户级技能目录：
   - Linux / 鸿蒙：`~/.workbuddy/skills/salt-journal-materials`
   - Windows：`C:\Users\<用户名>\.workbuddy\skills\salt-journal-materials`
3. 重启对话即可使用，直接说：「用盐系手帐素材帮我做一组素材：……」

（在 Codex / Claude Code 等其他工具中，则放入各自的 skills 目录，如 `~/.codex/skills/`。）

## journal-outputs 目录约定

每次生成的素材按 `YYYY-MM-DD-主题名/` 归档，内含：

- `*.png`：素材页成品（可直接打印裁切）
- `collage-*.png`：拼贴灵感参考（如有）
- `manifest.md`：素材清单（编号、类型、外观）与生成提示词

## 素材版权说明

- skill 本体遵循上游仓库（carolinaaafy/salt-journal-materials）的授权；
- `journal-outputs/` 中由 AI 生成的素材供个人手帐使用。
