# Product walkthroughs

Two 75-second videos with Chinese synthetic narration and bilingual on-screen summaries, assembled on 2026-11-26. Each is an edited tour of original UI screenshots, not a continuous screen recording or a newly executed live task. Screenshots are cropped and scaled for readability; interface text is unchanged.

## xiaoman

[Watch / download the MP4](xiaoman-walkthrough-75s.mp4)

小满：对话交办、事项列表、日终简报和设备动作确认。

The original simulator screenshots match the project’s 2026-11-19 replay acceptance manifest. The data and contacts are synthetic. The alarm test chose **decline**; this video does not demonstrate alarm installation, a real-device workflow, a real email send or remote APNs delivery. The implementation remains private.

| Time | Scene |
| --- | --- |
| 00:00 | 明天的安排，提前理清。 |
| 00:08 | 一句话，记下交办。 |
| 00:22 | 事情有归处，进展看得见。 |
| 00:36 | 明早怎么安排，今晚先知道。 |
| 00:50 | 设备动作，由你拍板。 |
| 01:05 | 能看见状态，也能做决定。 |

### Chinese narration

这是小满，一个开发中的个人助理。接下来用模拟器截图，看看交办、简报和确认。

从对话开始。这个测试里，用户交办准备笔记，小满复述事项和建议日期，并请求确认。画面中的内容是回放测试数据，展示的是事项交办流程。

确认后的交办，可以在事项中找到。我在办、等别人和提醒分开呈现，方便查看期限与下一次复查时间。这里的联系人和账单都是演示数据。

再看日终简报。示例里，明早七点零五有航班，简报给出四点五十出发、四点二十起床的建议。它同时说明，设置闹钟还需要单独确认。

设备动作会先展示确认面板。用户可以设置闹钟，也可以选择不用。这轮验收测试走的是拒绝路径，记录为已拒绝，没有安装真实闹钟。

小满仍是开发中的产品。这段是界面截图导览，使用回放模型和假数据；真实账户、真机和远程推送，还需要继续验收。

## opswitness

[Watch / download the MP4](opswitness-walkthrough-75s.mp4)

OpsWitness：审阅工作范围、查看团队分工、运行历史和报告证据。

The screenshots are the existing public development UI assets from [OpsWitness commit 3e86cc3](https://github.com/opswitness/opswitness/tree/3e86cc34941aa02716905a3fae07ee02699d7dfc/site/assets). DEMO-001 is synthetic. This is an interface tour, not a new execution or an endorsement of the example report’s subject-matter accuracy. **Execution complete does not establish a verified business outcome.** The [download release](https://github.com/opswitness/opswitness/releases/tag/v0.1.0-alpha.1) has its own capabilities and limitations.

| Time | Scene |
| --- | --- |
| 00:00 | 让 AI 工作，有计划也有记录。 |
| 00:08 | 先看清，要完成什么。 |
| 00:22 | 谁做什么，分工看得见。 |
| 00:36 | 每次运行，都有自己的历史。 |
| 00:50 | 看报告，也能追到证据。 |
| 01:05 | 执行完成，还要核验结果。 |

### Chinese narration

这是 Ops Witness。接下来用公开界面截图，看看一次工作如何留下计划、分工和结果记录。

工作概览先写清目标、输入边界和交付物。画面中的演示报告，只使用合成客户数据，并明确要求人工审签。用户可以先审阅这些约束。

再看团队。这个合成案例里，有解读、引用核验和报告编辑三个角色。职责与汇报关系都能查看，方便理解每个角色参与了哪一部分工作。

历史页面保留不同版本和运行记录。完成、失败和停止的轮次，都各自可见。这样可以回看某一轮工作的状态和结果，而不把多次执行混成一个结论。

结果页提供报告入口，并展示引用核验、人工审签和证据绑定。案例内容用于演示流程。这里关注的是结果如何被记录与复核，不是证明报告中的专业判断正确。

执行完成，仍然需要核验业务结果。开发界面和下载版本可能不同，具体能力以发布说明为准。

## Credits

Product work and portfolio: Tianyu Zhou. Narration is computer-generated using a macOS system voice. No background music is used. Publishing these demonstration media does not change any product repository’s license or publish private implementation code.
