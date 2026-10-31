# 一级市场投资助手

用于非上市公司初筛、深度研判和投资判断更新。入口为 [SKILL.md](SKILL.md)，操作示例见 [使用说明](使用说明.md)。

## 安装与维护

本仓库为技能源文件；本机启用副本位于 `C:/Users/87458/.codex/skills/primary-market-investment`。修改优先在本仓库进行，检查后同步 SKILL.md、agents、assets、references 到启用目录。不要反向覆盖未提交的修改。

## 简单版本流程

1. 修改前运行 `git pull --ff-only`；有未提交修改时先提交或暂存。
2. 修改技能或参考资料，检查文档链接、数字示例及个人信息。
3. 在 CHANGELOG.md 记录变化；运行 `git diff --check` 并查看 `git diff`。
4. 用 `git add` 选择文件，再执行 `git commit -m "docs: 描述本次变化"`，随后 `git push`。
5. 形成可用版本时：`git tag -a v0.1.1 -m "版本说明"`，再 `git push origin v0.1.1`。

日常直接使用 main；较大修改使用 `codex/主题` 分支。补充修订递增补丁版本，新增能力递增次版本，破坏兼容的变化递增主版本。不强制推送，不移动已发布标签。需要撤销已发布修改时使用 git revert。

## 数据边界

只提交通用技能和空白配置。BP、尽调材料、个人投资偏好、公司报告和凭据放在仓库外，或被忽略的 private/、inputs/、reports/ 目录。公开仓库提交前必须检查内容。
