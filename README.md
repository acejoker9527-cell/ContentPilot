# ContentPilot

增长营销顾问 AI Skill — 根据产品信息、行业、目标受众、价格带和商业目标，输出 KOL 推荐、内容策略、平台分发等可执行增长方案。

## 安装使用

将仓库克隆到本地，把 `SKILL.md` 放到 OpenCode 的 skills 目录：

```
# 项目级（团队成员共享）
mkdir -p 你的项目/.opencode/skills/growth-marketing-consultant
cp .opencode/skills/growth-marketing-consultant/SKILL.md 你的项目/.opencode/skills/growth-marketing-consultant/

# 全局（个人使用）
mkdir -p ~/.config/opencode/skills/growth-marketing-consultant
cp .opencode/skills/growth-marketing-consultant/SKILL.md ~/.config/opencode/skills/growth-marketing-consultant/
```

重启 OpenCode，输入 `/skill growth-marketing-consultant` 即可加载。

## 功能

1. **产品诊断** — 逐步引导你完成产品定位、行业分析、客单价、用户画像、商业目标
2. **KOL 推荐** — 精准推荐达人类型 + 平台 + 粉丝量 + 合作形式 + 避坑建议
3. **内容策略** — 内容定位、比例分配、10 个爆款方向、20 条具体选题
4. **平台分发** — 小红书 / 抖音 / 视频号 / 私域的差异化打法
5. **执行方案** — 冷启动 → 增长期 → 转化阶段 + 三档预算方案
6. **实战导向** — 不输出空话，所有建议结合行业特点，可直接落地

## 适用行业

高端旅游 · 家居装修 · 留学教育 · 医美 · 婚礼策划 · 定制服务 · 奢侈品 · 企业服务 · 本地生活服务 · 更多

## 目录结构

```
.
├── AGENTS.md                                          # 项目规则（跳过图片文件等）
└── .opencode/skills/growth-marketing-consultant/
    └── SKILL.md                                       # Skill 主体文件
```

## 许可

MIT
