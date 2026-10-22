# 智能客服系统

Intelligent Customer Service System

软件工程课程专业领域项目，对应实践项目说明第3部分第7项“智能客服或校园事务问答系统”，本项目选择智能客服方向。

## 开始协作

先读[初始化入口](initialization/skills/README.md)，再完整阅读[共同大纲](initialization/skills/共同大纲.md)、[协作协议](initialization/skills/协作协议.md)、[文档格式规范](initialization/docs/文档格式规范.md)和[提交要求对照](initialization/docs/提交要求对照.md)。

ABCD目前是职责标识，尚未与具体组员或GitHub账号对应。小组共同确定大纲、具体服务业务和首轮范围后，各成员再读取分配给自己的角色skill：

| 角色 | 入口 | 主责 |
|---|---|---|
| a | [需求与业务](initialization/skills/req-a-spec/SKILL.md) | 第1章、第2章业务及第4章 |
| b | [领域与模型](initialization/skills/req-b-model/SKILL.md) | 第3、5章及主要模型 |
| c | [原型与质量](initialization/skills/req-c-prototype/SKILL.md) | 交互、接口、质量、原型及质量报告汇编 |
| d | [验收与复核](initialization/skills/req-d-verify/SKILL.md) | 验收、来源核查、独立复核及AI报告汇编 |

## 文件组织

- `initialization/`：共同大纲、协作协议、四份角色skill及文档规范。
- [实践项目说明](实践项目说明.pdf)：课程选题与专业领域要求。
- 正文、模型、原型、验证、证据和报告按实际工作逐步建立，初始材料不代表业务已确认或验证已完成。

## 版本协作

`main`保存小组当前认可的版本。成员从最新`main`建立本批工作分支，通过Pull Request说明修改、依据、未决事项及下游交接，审阅后合并。开始下一批任务前同步已合并内容，保留他人的修改，不强制推送覆盖历史。

共同正文用Markdown维护，Word与PDF作为同版交付。每位成员维护自己的图表、格式和真实证据；最终形成需求规格说明书、需求分析质量验证报告及AI智能体使用验证报告三份文档和相应附件。
