# Personal AI Skills

私人 AI 能力仓库。将经过验证的方法沉淀为可复用 Skill，供 Codex、Claude Code 等支持本地 Skill 的工具安装使用。

> GitHub 仓库本身不是自动调用服务。需要在目标工具中安装或同步；普通 ChatGPT 对话不会自动读取 GitHub 文件。

## Skills
- [Problem Clarifier](skills/problem-clarifier/SKILL.md) — 复杂问题澄清、苏格拉底式提问。v1.1 / 待实测
- [Motion Director](skills/motion-director/SKILL.md) — 代码视频动态导演、视觉追踪、节奏。v0.1 / 待实测
- [Business Red Team](skills/business-red-team/SKILL.md) — 商业模式反方审查。v0.1 / 草案

## 原则
1. 明确任务直接执行，不为提问而提问。
2. 区分事实、假设、判断和未知；未经验证不得声称已验证。
3. 以实际产出、可检验证据和迭代记录为准。
4. 不在仓库提交密钥、客户敏感资料、个人隐私。
5. Skill 更新应保留案例、失败原因和版本记录。

## 使用
将需要的 skills/<name> 目录安装或同步到目标工具支持的 Skill 目录，并按该工具的发现机制调用。不同客户端的安装、自动发现与权限机制可能不同。