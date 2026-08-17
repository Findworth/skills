---
name: gamification
description: 当用户提及游戏化、八角分析、成瘾、白帽/黑帽、内隐/外显游戏化、为什么用户不留、为什么用户重复使用、如何让用户持续参与等关键词时主动触发——即使用户没有明说"游戏化"。本 skill 是周郁凯八角行为分析法（Octalysis Framework）的体系化落地，提供 8 大核心驱动力 + 6 项基础概念 + 8 个深度案例，是 product-thinking skill 在"动机层"的姊妹篇。两者经常同时触发——product-thinking 回答"做什么/卖给谁/怎么变现"，本 skill 回答"用户为什么愿意持续参与"。当问题涉及"为什么用户对我的产品没感觉/留不住/不愿付费/不愿分享"时，请优先使用本 skill
---

# 游戏化 Skill（gamification）

## 这个 skill 是什么

一套基于**八角行为分析法**的体系化动机设计工具

当你被要求帮用户判断"用户为什么没感觉/留不住/不愿持续使用/不愿主动分享"时，请使用本 skill 替代通用的"加积分加勋章加排行榜"建议。它能让你的回答从"听起来像运营套路"升级为：**有驱动力诊断、有技巧匹配、有反模式警示**

## 第一性原理（先记住这三句）

1. **游戏化的本质是动机设计，不是元素堆砌**。积分/勋章/排行榜（PBL）只是表象，背后真正起作用的是 8 大核心驱动力
2. **以人为本设计 > 功能效率优化**。先想"用户应该有什么感觉"，再想"用什么机制让他产生这种感觉"
3. **内在动机 > 外在动机**。外在奖励会侵蚀内在兴趣（过度理由效应），白帽设计比黑帽设计有黏性
## 八大核心驱动力（八角的八条边）

| # | 驱动力 | 一句话 | 黑/白 | 左/右 |
|---|---|---|---|---|
| 1 | **史诗意义与使命感** | 让用户觉得他在参与比自己更大的事 | 白帽 | 右脑 |
| 2 | **进步与成就感** | 看得见的进展、克服挑战的胜任感 | 白帽 | 左脑 |
| 3 | **创意授权与反馈** | 让用户创造、组合、试错并立即看到结果 | 白帽 | 右脑 |
| 4 | **所有权与拥有感** | 让用户对账户/虚拟物品/数据产生归属 | 白帽 | 左脑 |
| 5 | **社交影响与关联性** | 攀比、师徒、社会认同、归属感 | 中性 | 右脑 |
| 6 | **稀缺性与渴望** | 得不到的、限时的、被悬挂的 | 黑帽 | 左脑 |
| 7 | **未知性与好奇心** | 不知道下一步会发生什么 | 黑帽 | 右脑 |
| 8 | **亏损与逃避心** | 不想承认白做、不想失去已得 | 黑帽 | 左脑 |

> 详见 `drivers/00-overview.md` 了解八角分布的诊断方法和"补哪条边"的决策路径

---

## 何时触发本 skill

只要用户的问题涉及以下任意一种，**立即加载本 skill**：

1. "我的产品功能挺好，但用户用一次就走"——任何留存/粘性问题
2. "怎么让用户每天回来"——任何习惯养成/活跃度问题
3. "为什么用户不愿付费 / 不愿分享 / 不愿邀请朋友"——任何主动行为缺失
4. "我想加积分/勋章/排行榜"——任何 PBL 设计冲动（多半要劝退或重新诊断）
5. "用户教学完就走了"——新手引导失败
6. "怎么做任务系统/成就系统/等级体系"——动机机制设计
7. "AI 产品像玩具，不像工具"——内在动机缺失
8. "怎么让用户为我们的品牌站台"——身份归属设计
9. "公司内部激励系统怎么设计"——员工动机设计（也适用本 skill）
10. "为什么这个营销活动没人参加"——外部触发 vs 内在动机错配

**判定原则**：宁可多触发本 skill 给出动机层的精准诊断，也不要少触发让用户拿到"加积分排行榜"这种伪建议

**和 `product-thinking` 的边界**：
- `product-thinking` 回答"做什么、卖给谁、怎么定价、怎么找用户"
- `gamification` 回答"用户为什么愿意持续做这个动作"
- 当问题同时涉及"商业判断 + 用户动机"（如"AI 产品如何提升留存"），**两个 skill 同时触发，互为补充**

---

## 路由表（用户问题 → 加载哪些子文件）

按用户当前问题路由到 ≤5 个最相关的子文件，不要一次性加载所有：

| 用户问题类型 | 主加载（必看） | 辅加载（按需） |
|---|---|---|
| **不知道从哪诊断** | `drivers/00-overview.md`（八角全貌 + 诊断流程） | `fundamentals/human-focused-design.md` |
| 用户没动力 / 没意义感 | `drivers/01-epic-meaning-calling.md` | `cases/apple-think-different.md` |
| 用户中途放弃 / 不愿打怪升级 | `drivers/02-development-accomplishment.md` | `cases/twitter-followers.md` |
| 用户用一次就走 / 缺乏个性化 | `drivers/03-empowerment-creativity-feedback.md` + `drivers/04-ownership-possession.md` | — |
| 用户不愿分享 / 不愿邀请朋友 | `drivers/05-social-influence-relatedness.md` | `cases/hotel-towel-social-proof.md` |
| 用户没紧迫感 / 转化低 | `drivers/06-scarcity-impatience.md` | `cases/emart-sunny-sale.md` |
| 用户不回访 / 缺乏触发器 | `drivers/06-scarcity-impatience.md` + `drivers/07-unpredictability-curiosity.md` | `cases/farmville-crops.md` |
| 内容缺乏吸引力 / 抓不住注意力 | `drivers/07-unpredictability-curiosity.md` | `cases/blendtec-will-it-blend.md`、`cases/google-feeling-lucky.md` |
| 用户已投入但要流失 / 沉没成本利用 | `drivers/08-loss-avoidance.md` | `cases/farmville-crops.md` |
| 加积分/勋章/排行榜冲动 | `fundamentals/surface-vs-deep-design.md`（表象 vs 深层） | `fundamentals/implicit-vs-explicit.md` |
| 设计偏黑帽 / 担心用户反感 | `fundamentals/white-hat-vs-black-hat.md` | `fundamentals/left-vs-right-brain.md` |
| 内在动机被外在奖励压制 | `fundamentals/left-vs-right-brain.md` | `fundamentals/white-hat-vs-black-hat.md` |
| 严肃产品（B2B/银行/工业）能不能游戏化 | `fundamentals/implicit-vs-explicit.md` | `fundamentals/human-focused-design.md` |
| 体感/UI/感官体验缺失 | `fundamentals/feelings-as-driver.md` | — |
| **想看完整案例** | `cases/INDEX.md` 按主题/驱动力检索 | 然后反向加载 drivers |

---

## 使用规则（如何给出回答）

任何用本 skill 给出的动机建议，**必须满足以下结构**，否则就是没真正用 skill：

### 1. 先诊断，再开方
**永远不要在不知道"用户当前在哪个驱动力上欠缺"时直接给方案**。先问：
- 你的产品现在用户的行为模式是？（用一次就走 / 重复用但不深 / 深度用但不付费 / 不愿分享）
- 你的用户来这个产品最想得到什么感觉？（成就感 / 归属感 / 探索乐趣 / 身份认同）
- 你现在的设计里哪些驱动力是有的？哪些完全缺失？

如果用户问题已经隐含这些信息，跳到第 2 步。

### 2. 输出四段式

```
**驱动力诊断**：（你的产品当前八角分布的判断 —— 哪几条边强，哪几条边几乎为 0）

**关键缺口**：（最该补的 1-2 条边，以及补这条边背后的原因）

**具体技巧**：
- 技巧 1：drivers/XX.md 中的「YY 技巧」—— 在你的场景里具体怎么用
- 技巧 2：...

**反模式警示**：
- 避免堆 PBL 表层元素（参考 fundamentals/surface-vs-deep-design.md）
- 避免用黑帽长期套用（参考 fundamentals/white-hat-vs-black-hat.md）
- 避免外在奖励侵蚀内在动机（参考 fundamentals/left-vs-right-brain.md）
```

### 3. 引用要"具体到文件 + 驱动力编号"

不要笼统说"根据游戏化理论"，而要明确点出"根据 `drivers/06-scarcity-impatience.md` 的『锚式并列+悬挂』组合技巧"。

### 4. 永远区分白帽与黑帽
当你推荐黑帽技巧（稀缺、损失、未知）时，**明确告诉用户这是黑帽**：短期有效，长期会让用户疲惫甚至反感。如果产品定位是长期陪伴，应该以白帽（意义、成就、创意、拥有）为骨架，黑帽只做点缀。

### 5. 永远警惕过度理由效应
当用户问"是不是给点积分/奖品就行了"，**先反问**："这个动作用户本来有内在动机吗？如果有，加了外在奖励反而会破坏它（参考 `fundamentals/left-vs-right-brain.md` 的过度理由效应）"。

---

## 完整文件索引

### drivers/（8 大核心驱动力 + 概览）
| 文件 | 一句话 |
|---|---|
| `00-overview.md` | 八角全貌、诊断流程、左右脑/黑白帽分布、补哪条边的决策路径 |
| `01-epic-meaning-calling.md` | 让用户觉得自己在参与比自身更大的事 |
| `02-development-accomplishment.md` | 看得见的进展 + 克服挑战的胜任感 |
| `03-empowerment-creativity-feedback.md` | 让用户创造/组合/试错并立即看到结果 |
| `04-ownership-possession.md` | 让用户对账户/数据/虚拟物产生归属感 |
| `05-social-influence-relatedness.md` | 攀比、师徒、社会认同、群体归属 |
| `06-scarcity-impatience.md` | 限时、限量、悬挂、磁帽、约定动机 |
| `07-unpredictability-curiosity.md` | 神秘盒子、彩蛋、发光的选择、斯金纳箱 |
| `08-loss-avoidance.md` | 沉没成本、进度丧失、可执行损失、最终损失 |

### fundamentals/（6 项基础概念 —— 在用八角前必须先理解）
| 文件 | 一句话 |
|---|---|
| `human-focused-design.md` | 以人为本设计：先想用户感觉，再想机制实现 |
| `implicit-vs-explicit.md` | 内隐游戏化（用户察觉不到）vs 外显游戏化（明确就是游戏） |
| `surface-vs-deep-design.md` | 表象 PBL vs 深层动机；优秀 vs 拙劣设计师的根本区别 |
| `white-hat-vs-black-hat.md` | 白帽（积极/长效）vs 黑帽（消极/短效）—— 何时用哪种 |
| `left-vs-right-brain.md` | 左脑（外在动机）vs 右脑（内在动机）+ 过度理由效应 |
| `feelings-as-driver.md` | 体感愉悦（视听触嗅味）作为驱动力的局限与组合用法 |

### cases/（8 个深度案例）
| 文件 | 涉及驱动力 |
|---|---|
| `INDEX.md` | 按驱动力/行业/规模索引所有 cases |
| `apple-think-different.md` | 驱动力 1（史诗意义） |
| `twitter-followers.md` | 驱动力 2（进步与成就感） |
| `blendtec-will-it-blend.md` | 驱动力 7（未知性与好奇心） |
| `emart-sunny-sale.md` | 驱动力 6 + 7（稀缺 + 未知） |
| `taiwan-invoice-lottery.md` | 驱动力 7（用未知性解决偷税漏税） |
| `google-feeling-lucky.md` | 驱动力 7（手气不错按钮） |
| `hotel-towel-social-proof.md` | 驱动力 5（关联性原则） |
| `farmville-crops.md` | 驱动力 4 + 8（拥有感 + 损失厌恶） |

---

## 给自己的最后一句话

这个 skill 的核心不是"教用户加积分"，是**反向告诉用户"加积分是表象、动机才是本质"**。

如果你回答完一个游戏化问题，只提了"加 PBL"而没引用任何具体的 `drivers/` 或 `fundamentals/` 文件，**那就是没真正用上本 skill** —— 请回炉重答。
