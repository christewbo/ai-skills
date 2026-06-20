# 理解了 branch 的安全区机制

用户完成 Lesson 3 和实际演示，能正确解释：
- `git switch` 会把工作目录替换为目标 branch 的快照（安全区的核心）
- `git branch -d` 被拒是因为 branch 上有未合并的 commit，Git 保护数据
- 未 commit 的改动会阻止 branch 切换，Git 要求先保存

用户还主动追问了 merge 的两种方式（fast-forward 和 three-way merge），理解了合并不是"标签覆盖"。

**Evidence:** Lesson 3 的三个检查问题全部正确，并亲眼观看了 demo 全过程（包括 `-d` 被拒和 `-D` 强制删除）。

**Implications:** 已具备进入 Lesson 4（实际操作：init → commit → push 到 GitHub）的条件。
