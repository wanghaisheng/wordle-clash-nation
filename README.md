
# Wordle Clash: Nation Domination - 产品需求文档 (PRD)

## 📖 产品概述

### 产品名称
**《Wordle Clash: Nation Domination》**  
中文名：词汇冲突：国家统治战

### 产品定位
基于地域竞争的智力竞技游戏，通过词汇解谜激发州际对抗情绪，打造具有强社交属性的休闲益智游戏。

### 目标用户
- **主要用户**：25-45岁，受过高等教育的美国用户
- **次要用户**：喜欢智力游戏的全球英语用户
- **核心特征**：具有地域认同感，喜欢竞争，有一定消费能力

## 🎯 产品目标

### 业务目标
- **用户规模**：首年获取100万注册用户
- **收入目标**：年收入1000万美元
- **留存率**：7日留存>45%，30日留存>25%
- **付费率**：整体付费率>8%

### 用户目标
- 提供有挑战性的智力竞技体验
- 满足用户的地域归属感和竞争欲望
- 创造持续的社交互动价值

## 🏗️ 核心功能架构

### 三模式挑战系统

#### 每日挑战模式（硬核竞技场）
- **谜题规格**：全球统一4x4固定谜题（每日0点更新）
- **游戏规则**：禁用所有卡片，3次错误即失败
- **计分机制**：通关=100分 + 时间奖励（每提前1秒+1分）
- **参与限制**：每人每日仅1次机会
- **核心价值**：纯粹比拼脑力，决定"州智商排名"

#### 自由挑战模式（贡献战场）
- **谜题规格**：AI实时生成动态谜题（尺寸3x3至6x6可选）
- **游戏规则**：自由使用卡片，错误上限5次
- **计分机制**：动态计算 = 基础分×尺寸系数 - 卡片惩罚 + 时间奖励
- **参与限制**：无限次数挑战
- **核心价值**：为州积累"知识财富值"

#### 地狱模式（Lull and Shock）
- **设计理念**：诱饵+地狱双关卡设计，激发社交传播
- **第一关**：3x3极简单谜题，96-98%通关率，建立虚假信心
- **第二关**：6x6极困难谜题，1.5-2.5%通关率，制造话题性
- **开放时间**：每周末48小时开放，制造稀缺性
- **社交机制**：通关自动生成炫耀卡片，一键分享到社交媒体
- **核心价值**：病毒传播工具，高端玩家身份象征

### 双榜单贡献系统

#### 地区每日榜（荣誉榜单）
- **数据源**：仅统计每日挑战成绩
- **排名算法**：(通关率×60%) + (战神率×30%) + (1/平均时间×10%)
- **视觉反馈**：榜首州显示💎钻石特效，进步最快州显示🚀火箭动画

#### 地区总分榜（统治榜单）
- **数据源**：仅统计自由挑战贡献分
- **积分规则**：
  - 通关3x3: 20分
  - 通关4x4: 50分  
  - 通关5x5: 120分
  - 通关6x6: 300分
  - 地狱模式通关: 1000分 + 专属徽章
  - 使用卡片: -10分/张
  - 战神通关: ×2倍基础分

## 🎮 游戏系统设计

### AI动态谜题引擎
- **智能难度调节**：基于玩家技能水平和州排名动态调整
- **主题生成逻辑**：结合文化适配和热点话题
- **质量控制**：多层自动检测+人工审核机制
- **地狱模式专项**：超高难度算法，包含文化陷阱、多义词迷惑等

### 卡片系统（仅自由模式）
- **🔍 提示卡**：高亮2个正确词，-10分，看广告获得
- **🧩 解构卡**：显示1组主题，-20分，邀请好友获得
- **✨ 净化卡**：移除1干扰词，-30分，$0.99购买
- **⚔️ 战神卡**：通关后×2倍基础分，无惩罚，每日挑战奖励
- **👹 地狱通行证**：地狱模式失败后复活机会，$1.99购买

### 反刷分机制
- **收益递减**：连续通关同尺寸谜题，基础分每次-20%
- **难度跃升**：3次连续通关，强制升级到更大尺寸
- **AI监考**：异常速通玩家弹出验证题

### 地狱模式社交传播系统
- **炫耀卡片自动生成**：通关瞬间创建个性化成就卡片
- **一键分享**：集成Facebook、Twitter、Instagram、TikTok
- **挑衅功能**：向好友发起地狱模式挑战
- **排行榜**：地狱征服者专属排行榜，按州展示

## 📱 用户界面设计

### 主界面布局
```
[ 每日挑战 ]   [ 自由挑战 ]   [ 🔥地狱模式 ]
--------------------------
🔥 今日加州排名：#2（需守护！）
💎 自由贡献分：8,400（州内TOP 12%）
👹 地狱征服者：本州仅3人通关
--------------------------
>> 选择你的战场 <<
```

### 战报系统
- **每日挑战成功**："你以2分11秒跻身加州前10%！ #SpeedMaster"
- **自由挑战成功**："为加州赢得300知识财富！再赢2场超越德州 #KnowledgeConqueror"
- **地狱模式征服**："🔥你成为全美仅0.8%的地狱征服者！#HellConqueror #加州之光"

## 💰 商业化模型

### 收入来源
- **广告收入**：自由挑战看广告得卡，$3.99去除广告
- **内购收入**：$4.99=50张净化卡，$9.99解锁名人词库，$1.99地狱通行证
- **特权订阅**：$14.99/月动态战争特效徽章 + 地狱模式无限复活
- **地狱模式专项**：$19.99地狱征服者限定皮肤包

### 贡献分经济
- 2000分 = 1张净化卡
- 5000分 = 专属称号"州之智将"
- 10000分 = 参与设计新谜题
- 地狱通关 = 专属称号"地狱征服者" + 限定头像框

## 📊 数据指标体系

### 关键指标
- **每日挑战通关率**：目标15%-25%
- **自由挑战人均场次**：目标5.8场/日
- **地狱模式参与率**：目标35%（周末开放时）
- **地狱模式通关率**：严格控制在1.5-2.5%
- **社交分享率**：地狱通关后分享率目标>90%
- **州间差距**：榜首/榜末＜3倍
- **付费转化率**：目标8%+
- **用户留存率**：7日>45%，30日>25%

### 监控维度
- 用户行为数据：游戏时长、挑战次数、卡片使用情况
- 社交数据：分享次数、邀请转化率、地狱模式话题热度
- 商业化数据：ARPU、付费渗透率、广告eCPM
- 地狱模式专项：参与率、通关率、社交传播效果

## 🚀 产品路线图

### Phase 1 (MVP, 0-3个月)
- ✅ 基础游戏玩法实现
- ✅ 州选择与双榜单系统
- ✅ AI题库生成引擎
- 🔄 iOS App发布

### Phase 2 (3-6个月)
- 卡片系统完善
- 社交分享功能
- 🔥 地狱模式上线
- 推送通知系统
- Android版本开发

### Phase 3 (6-12个月)
- 公会系统
- 赛季竞技模式
- UGC内容创作
- 国际化扩展
- 地狱模式主题活动

## ✅ 验收标准

### 功能验收
- [ ] 每日挑战模式正常运行，全球同步更新
- [ ] 自由挑战模式AI生成题目质量达标
- [ ] 地狱模式双关卡难度控制精准（96-98% vs 1.5-2.5%）
- [ ] 双榜单实时更新，排名计算准确
- [ ] 卡片系统平衡性测试通过
- [ ] 社交分享功能完整实现
- [ ] 商业化功能完整实现

### 性能验收
- [ ] 应用启动时间<3秒
- [ ] 游戏页面加载时间<2秒
- [ ] 支持并发用户数>10万
- [ ] 崩溃率<0.1%
- [ ] 地狱模式社交分享成功率>95%

### 用户体验验收
- [ ] 用户完成率>80%（新手引导）
- [ ] 用户满意度>4.2分（应用商店评分）
- [ ] 用户反馈问题解决率>90%
- [ ] 地狱模式话题传播热度达标

---

**文档版本**：v1.1  
**最后更新**：2025-01-05  
**负责人**：产品团队
