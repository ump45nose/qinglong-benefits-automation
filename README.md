# 青龙签到脚本索引

各来源独立发布、独立配置、独立定时。这个仓库只保存公开索引与状态说明，不包含家庭部署配置、账号、Cookie、会话、代理地址或运行结果。请进入对应项目的 README 安装；不需要安装整套集合。

| 来源 | 独立项目 | 状态 |
| --- | --- | --- |
| laowang.vip | [laowang-checkin](https://github.com/ump45nose/laowang-checkin) | 已有签到后读回验证；需要本地浏览器会话 |
| 什么值得买 | [smzdm-checkin-ql](https://github.com/ump45nose/smzdm-checkin-ql) | 已有签到和奖励查询 |
| V2EX | [v2ex-dailycheckin-ql](https://github.com/ump45nose/v2ex-dailycheckin-ql) | 调用上游签到；连续天数查询单独判断 |
| 阿里云开发者社区 | [aliyun-dev-checkin-ql](https://github.com/ump45nose/aliyun-dev-checkin-ql) | 签到后核对状态与积分；登录态仍可能失效 |
| Epic 免费游戏 | [epic-freebies-verifier](https://github.com/ump45nose/epic-freebies-verifier) | 上游领取流程的商品页拥有状态补充核验 |
| Microsoft Rewards | [microsoft-rewards-snapshot](https://github.com/ump45nose/microsoft-rewards-snapshot) | 只读积分与活动快照，不执行任务 |

京东京豆仍因登录态和实际奖励未确认而不发布为可用签到脚本。中国移动按需求跳过。`qd-today/qd` 是独立上游服务，本项目未修改它。

每个项目的 README 分别给出上游依赖、环境变量、运行方式、验证边界及许可证。公共代码中没有真实账户数据；私有部署文件继续存放在独立的私有仓库中。上游反馈见 [CONTRIBUTIONS.md](./CONTRIBUTIONS.md)。
