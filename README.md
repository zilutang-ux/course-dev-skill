# 🎓 课程研发设计 Skill（ADDIE × 大片课融合版）

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-green.svg)](https://docs.openclaw.ai)
[![Version](https://img.shields.io/badge/Version-1.2.0-brightgreen.svg)](CHANGELOG.md)

> 融合ADDIE体系化框架与大片课实战方法论，让每一门课都成为「大片级」学习体验。
> **课程的本质是「换脑」，唯有大片式课程才能实现深度认知改变。**

---

## ✨ 核心理念

本 Skill 融合两大方法论：

| 方法论 | 角色 | 核心价值 |
|--------|------|---------|
| **ADDIE** | 流程骨架 | 分析→设计→开发→实施→评估（系统性+可追溯） |
| **大片课** | 内容质量 | 天龙八部（冲击力+换脑效果） |

### 课程四部曲（好莱坞映射）

```
策划（课程准备·说清）→ 编剧（课程内容·说服）→ 导演（课程演绎·说动）→ 发行（课程销售·说销）

顺序不可逆：说不清 → 无法说服 → 无法说动 → 无法说销
```

---

## 🎯 适用场景

- 💼 商业课程打磨升级
- 🏢 企业内训课程开发
- 🎬 AI漫剧培训设计
- 🌟 知识IP打造
- 📋 课程评审/诊断/优化

---

## 📋 五阶段全景

```
阶段一：分析 × 定位 ──→ 阶段二：设计 × 框架 ──→ 阶段三：开发 × 内容
  (找钉子)                (传信任)               (写剧本)
                                                      │
                                                      ▼
阶段五：评估 × 销售 ←── 阶段四：实施 × 演绎 ←────────┘
 (闭环迭代)              (说动学员)
```

### 阶段一：分析 × 定位（找钉子）
- 学员调研（≥10人深度访谈）
- 钉子公式：**「你有病，我有药，就我有」**
- 钉子三要素：一痛 + 一招 + 一不
- **"一"的哲学：** 取一舍九、一箭穿心、一直敲

### 阶段二：设计 × 框架（传信任）
- 框架三重身份：专业标志 + 治学态度 + 感召武器
- 三把利剑：一脉相承 + 一剑封喉 + 一首诗词（进阶：环环相扣、严丝合缝）
- 1/3/5分钟检验：入眼 → 入耳 → 入心

### 阶段三：开发 × 内容（写剧本）
- 开场三步曲：定义使命→愿景→标准（决心改命）
- 中场三步曲：揭示现状→挑战现状→标杆对比
- 收场三步曲：一招制胜→做标准→给信心
- **实效教学法：** 我做你看→我说你听→你做我看→你说我听
- 全程贯穿：共情（四标准）+ 悬疑（三价值）

### 阶段四：实施 × 演绎（说动学员）
- 讲师磨课SOP
- 每节课演绎自检五问

### 阶段五：评估 × 销售（闭环迭代）
- 柯氏四级评估（L1-L4）
- 换脑八问评估
- 钉子营销（不销而销）

---

## 📁 项目结构

```
course-dev/
├── SKILL.md                    ← 核心技能文件（200行，导航仪）
├── references/                 ← 按需加载的详细资料
│   ├── addie-detail.md         ← ADDIE五阶段完整细节+检查清单
│   ├── blockbuster-detail.md   ← 大片课天龙八部完整细节
│   ├── ttt-guide.md            ← 讲师能力模型+磨课SOP
│   └── templates.md            ← 所有模板（开场/中场/收场/自检/文档模板）
├── README.md                   ← 项目说明（本文件）
├── LICENSE                     ← MIT协议
├── CHANGELOG.md                ← 版本更新记录
└── .gitignore                  ← Git忽略规则
```

### 设计理念：分层加载

| 层级 | 文件 | 用途 | 加载时机 |
|------|------|------|---------|
| 元数据 | SKILL.md frontmatter | 触发判断 | 始终加载 |
| 核心流程 | SKILL.md body | 决策逻辑+五阶段框架 | 触发后加载 |
| 详细参考 | references/ | 检查清单+模板+完整方法论 | 按需加载 |

**效果：** SKILL.md 保持精简（205行），节省上下文窗口；详细内容按需查阅。

---

## 🔑 关键概念速查

### 钉子公式
> **「你有病，我有药，就我有」**
> - 一痛：学员最大的痛点
> - 一招：你的核心解决方案
> - 一不：与竞争对手的最大不同

### 换脑八问
1. 定位清楚？学员能一句话说清课程内容吗？
2. 框架可信？学员能复述课程框架吗？
3. 开场改命？学员听完开场有改变决心吗？
4. 中场挑战？学员承认旧认知被挑战了吗？
5. 收场行动？学员有具体的行动方案吗？
6. 共情懂你？学员觉得"讲师懂我"吗？
7. 全程投入？学员全程投入吗？
8. 愿意推荐？学员愿意推荐/复购吗？

### 90分钟课堂节奏
```
开场 15min（决心改命）→ 中场 50min（挑战现状）→ 收场 25min（促使行动）
     全程贯穿：共情 + 悬疑
```

---

## 🚀 安装方法

### 方式一：Git Clone（推荐）

```bash
# 进入你的 OpenClaw workspace skills 目录
cd ~/.openclaw/workspace/skills/

# Clone 仓库
git clone https://github.com/zilutang-ux/course-dev-skill.git course-dev
```

### 方式二：下载 Release 解压

1. 前往 [Releases](https://github.com/zilutang-ux/course-dev-skill/releases) 页面
2. 下载最新版本的 Source code (zip)
3. 解压到你的 OpenClaw workspace skills 目录：
```bash
unzip course-dev-skill-x.x.x.zip -d ~/.openclaw/workspace/skills/
mv ~/.openclaw/workspace/skills/course-dev-skill-x.x.x ~/.openclaw/workspace/skills/course-dev
```

### 方式三：手动下载 SKILL.md

如果只需要核心文件（不包含 references/ 详细资料）：

```bash
mkdir -p ~/.openclaw/workspace/skills/course-dev/references
curl -o ~/.openclaw/workspace/skills/course-dev/SKILL.md \
  https://raw.githubusercontent.com/zilutang-ux/course-dev-skill/master/SKILL.md
curl -o ~/.openclaw/workspace/skills/course-dev/references/addie-detail.md \
  https://raw.githubusercontent.com/zilutang-ux/course-dev-skill/master/references/addie-detail.md
curl -o ~/.openclaw/workspace/skills/course-dev/references/blockbuster-detail.md \
  https://raw.githubusercontent.com/zilutang-ux/course-dev-skill/master/references/blockbuster-detail.md
curl -o ~/.openclaw/workspace/skills/course-dev/references/ttt-guide.md \
  https://raw.githubusercontent.com/zilutang-ux/course-dev-skill/master/references/ttt-guide.md
curl -o ~/.openclaw/workspace/skills/course-dev/references/templates.md \
  https://raw.githubusercontent.com/zilutang-ux/course-dev-skill/master/references/templates.md
```

### 验证安装

安装完成后，重启 OpenClaw Gateway 或重新加载配置：

```bash
openclaw gateway restart
```

然后你可以在对话中测试：「帮我开发一门XX课程」，Agent 应自动触发 course-dev skill。

---

## 💬 使用示例

### 开发新课程
```
我要开发一门「AI短视频制作」课程，目标学员是企业新媒体运营，想解决从0到1出片的问题
```

### 打磨现有课程
```
我有一门「直播带货实战课」，学员反馈"听不懂、用不上"，帮我诊断并升级
```

### 课程评审
```
这是我的课程大纲，帮我用换脑八问评估一下课程质量
```

---

## 📖 参考资料

| 文件 | 内容 |
|------|------|
| [references/addie-detail.md](references/addie-detail.md) | ADDIE五阶段完整操作细节、检查清单、进化模型对比、AI时代实践建议 |
| [references/blockbuster-detail.md](references/blockbuster-detail.md) | 大片课天龙八部完整细节、钉子哲学、框架三重身份、实效教学法、共情四标准、悬疑三价值 |
| [references/ttt-guide.md](references/ttt-guide.md) | TTT讲师能力三层模型、常见问题对策、磨课SOP（10步诊断法） |
| [references/templates.md](references/templates.md) | 开场/中场/收场模板、钉子定位模板、课程框架模板、换脑八问评估表、输出文件清单 |

---

## 📝 License

MIT License - 详见 [LICENSE](LICENSE)

## 🙏 致谢

- ADDIE 教学设计模型（Instructional Systems Design）
- 夏晋宇《好课像大片——一门课,一个亿》
- TTT（Training the Trainer）培训体系

---

**让每一门课都成为大片。** 🎬
