# 常务会舆情报告 · WorkBuddy 安装页

[下载技能包 cwh-report-skill.zip](https://raw.githubusercontent.com/zty1307/cwh-report-workbuddy/main/cwh-report-skill.zip)

## 在 WorkBuddy 里安装

把本页链接发给 WorkBuddy，并附上这句话：

> 请下载本页的常务会报告技能包，按说明安装，检查我这台电脑能否运行。检查完告诉我结果，等我发本期数据。

1. 下载上方 ZIP。当前版本为 2026 年 11 月 27 日试用版，SHA-256 为 `66e50a4effbfe6c360d05e82d858caa0975c68044e969cd841f949c0b6d1f266`。
2. 将 ZIP 中的 `cwh-report-skill` 文件夹解压到当前用户的 `.workbuddy/skills/`。安装后应能找到 `~/.workbuddy/skills/cwh-report-skill/SKILL.md`。更新已有版本时先备份原目录。
3. 打开 WorkBuddy 新对话，按包内 `references/local_setup.md` 准备依赖，在技能目录运行 `python scripts/run_with_workbuddy.py --check`。Windows、Mac 使用同一个包。Windows 已实机测试，Mac 的完整报告流程仍待真机验证。模型调用需要使用者自己的 WorkBuddy 登录和模型权限。

## 生成一期报告

在 WorkBuddy 中提供本期监测数据 ZIP 或原始表文件夹，并说：

> 用常务会报告 skill 和 GLM 跑这期数据。完成后给我 Word、配套 Excel 和工作台，并告诉我哪些地方还需要核对。

输入数据和生成的报告保存在本机任务目录。这个仓库用于分发安装包，请在 WorkBuddy 中提供业务材料。
