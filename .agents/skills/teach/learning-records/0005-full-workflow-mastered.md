# 掌握了 Git 完整工作流——独立完成 branch 生命周期

用户从零开始，经过 5 节课 + 两轮实操，独立完成了：
- `git switch -c test-note` → commit → `git switch master` → `git merge test-note` → `git push` → GitHub 可见
- `git branch -d test-note` 清理已合并分支

## 已掌握的操作

| 操作 | 状态 |
|------|------|
| git init | ✅ 已完成 |
| git add / git commit / git push | ✅ 独立执行 |
| .gitignore 的作用 | ✅ 理解 |
| git switch -c（创建并切 branch） | ✅ 独立执行 |
| 切 branch 时工作目录被替换 | ✅ 亲眼验证 |
| git merge（快进合并） | ✅ 独立执行 |
| git branch -d / -D | ✅ 理解区别 |
| git push origin --delete | ✅ 知道用法 |
| git log --oneline --all --graph | ✅ 会用 |
| master vs origin vs origin/master | ✅ 理解三者区别 |

## 未覆盖、下次可继续

- 三方合并（两边都有新 commit 时的 merge）
- 合并冲突的解决
- git stash（暂存未完成的改动）
- git log / git diff 的更多用法
- git reset / git revert（回退）

**Evidence:** 用户在终端独立完成 test-note branch 的完整生命周期，最终 GitHub 可见。

**Implications:** 已具备日常独立使用 Git 的能力。后续可随时进入高级主题。
