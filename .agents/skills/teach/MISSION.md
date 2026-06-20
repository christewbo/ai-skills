# Mission: Git

## Why
理解 Git 的核心模型之后，通过 AI agent 安全地管理代码版本——能随时保存进度、回退错误、以及在多台机器/多人之间同步代码。不是死记命令，而是建立可迁移的心智模型。

## Success looks like
- 能用自己的话解释 Git 是什么，以及 commit、branch、remote 之间的关系
- 能在 AI agent 的帮助下执行 init → commit → push 的完整流程，安全备份代码
- 遇到 Git 报错时不慌，能根据提示推断问题出在哪

## Constraints
- 通过 AI agent（Claude Code / Codex 等）操作 Git，不需要记住所有命令
- 当前是单人项目，团队协作暂时不需要

## Out of scope
- 团队协作工作流（pull request、code review、merge strategy）
- Git 内部实现（SHA-1 哈希算法、packfile 格式）
- 高级操作（rebase -i、cherry-pick、bisect）
