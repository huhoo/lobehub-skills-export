# lobehub-skills-export

<!-- SOURCE-ANCHOR:start -->
本仓列＝主仓 274ac43 的取值窗（构建时现取，不手打）。
<!-- SOURCE-ANCHOR:end -->


导出镜像（export-only），**唯一真值源是 https://github.com/huhoo/cue-awesome**。本仓不写独立内容：文件一律由主仓构建口生成，改进回主仓改、过主仓门禁后重新导出。

- 收录范围：**本仓 `skills/` 目录现列**，逐枚见下条清单（本句有意不写枚数）。本仓现列取自主仓的某一取值窗——主仓新增件在本仓下一次重导前不在本仓，两边对不上时以主仓为准并重新导出。本仓 `skills/` 目录实测值与下面清单同涨同落。
- 清单（每次导出重新生成，顺序为名称序）：`catalyst-calendar`、`civil-appeal-turnaround`、`cn-contract-clauses`、`cn-earnings-note`、`cn-link-to-note`、`cn-research-brief`、`cn-resume-jd-fit`、`competitive-brief`、`cue-lead-pieces`、`cue-omni-ontology`、`dd-checklist`、`event-brief-cn`、`event-risk-scan`、`ic-memo-cn`、`journal-draft`、`long-doc-translation`、`meeting-minutes-cn`、`omni2docx`、`paper-study-cn`、`sector-overview`、`skill-review-cn`、`tear-sheet`、`watchlist-digest-cn`
- 每枚件的目录形：`skills/<名>/SKILL.md`（渠道导入器要求的布局）；包内机检、随包自测入口与面文承诺都随件带着，不在这儿另写一份。
- 出处与许可：`LICENSE.md` 与 `NOTICE.md` 随主仓同源同版；方法论基座的出处行以主仓 README／NOTICE 为准，本仓不另写一套。
- 安装与使用以主仓 README 为准；本仓不声明渠道收了几枚、店卡显示什么，那些以渠道页面为准。

## 这条导出链怎么跑（谁导、按什么号、多久一次）

| 问题 | 答案 |
|---|---|
| 谁导 | 主仓的同一维护者。用主仓构建口 `scripts/pack_skill.sh` 逐枚出包，解包后按 `skills/<名>/` 摆进本仓——人不手改任何文件内容，改内容＝回主仓改。 |
| 按什么号 | 每次导出取主仓 `main` 当时的 HEAD 那一个 commit；用的哪个短号写在那一次导出的 commit message 里，逐次可查（本仓 `git log`）。本次导出号同时写在本仓 README/NOTICE 的锚块与导出 commit message（构建时现取，不手打）。 |
| 多久一次 | 没有固定周期，也不承诺周期。触发条件是主仓那一批件变了、且主仓门禁跑绿；导完逐枚核对「本仓 `skills/` 目录 == 主仓表列」，任一边不一致就重导而不是改文档去迁就。 |
| 渠道那一步 | 把仓库交给渠道导入只有第一次需要（要账号持有者那一下）；此后每次发版由维护者自己跑 CLI。渠道侧收录与展示不归本仓说话。 |
| 发现对不上怎么办 | 以主仓为真值源：本仓任何一句与主仓冲突，错的是本仓这一句。 |
