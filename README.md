# 求职咨询备课与演练助手

给求职咨询顾问和主管使用的 AI 教练：围绕已有诊断报告备课、整理岗位证据，扮演客户或家长进行完整咨询演练，结束后评分复盘，并根据真实咨询记录制定跟进动作。

**公开体验版 0.1.0-public.1。** 用于试用和收集反馈；不是“已经复制顶级顾问”的证明，也不承诺求职或成交结果。

[下载完整包](https://github.com/HDCareer/career-consultation-coach/releases/latest/download/career-consultation-coach-0.1.0-public.1.zip) · [反馈体验](https://github.com/HDCareer/career-consultation-coach/issues/new?template=feedback.yml) · [查看已知限制](VALIDATION.md)

## 能做什么

- 会前备课：报告解读、岗位证据、方向论证与关键风险。
- 客户／家长／付款者角色演练，覆盖 R1—R9 咨询过程。
- 演练中只扮演对方，结束后再评分、复盘和给参考表达。
- 会后跟进建议与主管复盘摘要。

适合已有求职咨询业务的顾问、培训负责人及研究顾问工作流的人。它不是给求职者练招聘面试的面试官，而是让顾问练如何做求职咨询。

## 安装与开始

1. 下载上方 ZIP 并解压，找到直接包含 `SKILL.md` 的 `career-consultation-coach` 文件夹。不要只上传这一个文件。
2. 将整个文件夹放进当前项目的 `.agents/skills/`，或个人目录的 `~/.agents/skills/`。Windows 的 `~` 指你的用户目录。
3. 在 Codex 新建对话，输入下方体验指令。若没识别到，请让 Codex检查安装路径；不要只凭“已启用”判断安装成功。

```text
使用 $career-consultation-coach。请读取 examples/try-it.md，按其中明确标记的虚构案例启动Preparation。产品事实未提供的部分保持未知，先告诉我目前准备到哪一步。
```

目录依据：[Codex 官方技能说明](https://learn.chatgpt.com/docs/customization/overview#skills)。这里提供的是技能文件夹，不是应用商店一键安装插件。

首发按 Codex 本地文件工作流提供。核心规则为 Markdown，不依赖额外 Python 包。普通聊天界面无法按约定保存案例状态时，不能算完整安装验收；Gemini/Gem 的完整流程本版尚未实测。

## 实际使用前

公开版不含任何机构的实际价格、合同、退款比例、服务次数或客户案例。`references/product_facts/` 是待填写接口：请在私有案例的 `input/product_facts/` 提供当前有效资料；缺失项保持‘未确认’，不能凭空报价。

一客一目录，使用匿名编号。真实材料放在安装目录和 Git 仓库之外，遵循所在机构的授权和保留政策。不要把简历、聊天截图、合同、联系方式或模型密钥发到本仓库的 Issues。模型输出先由顾问审阅，再用于客户沟通。

## 请反馈什么

告诉我们：用了哪个模型、哪个环节、你期待它怎样做、实际哪里有用或没用。可贴一小段脱敏后的输入与回复。无需只报好评，卡住、过于啰嗦、判断错误都欢迎记录。

[另一个相关助手：求职诊断与报告助手](https://github.com/HDCareer/career-diagnosis-assistant) · [留学辅导销售助手](https://github.com/HDCareer/study-abroad-sales-coach)

## 许可

允许免费下载、试用、内部业务辅助和反馈；暂不授权商业再分发或收费托管。详见 [LICENSE.md](LICENSE.md)。这是公开可用项目，不采用标准开源许可证。
