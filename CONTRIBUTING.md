# Contributing / 贡献说明

[English home](README.md) · [中文首页](README.zh-CN.md)

## Scope / 贡献范围

Welcome improvements to instructions, source locators, paraphrases, and fictional examples. Explain the issue, proposed change, and evidence. Keep the two platform versions consistent where they share rules, and update both READMEs when changing usage instructions.

欢迎改进执行指令、页码定位、释义和虚构例子。请说明问题、修改内容及依据；共用规则要检查两个平台版本，使用说明变动需同步中英文首页。新增规则须核对相应版本和上下文，不用其他流派或记忆补齐。

## Checks before submission / 提交前检查

- Check relative links and distinguish original quotations from paraphrases. Record edition and page conventions for source claims.
- Do not submit full book transcriptions, scans, private charts, conversation exports, credentials, or machine-specific paths. Review Markdown text as well as attachments.
- Label synthetic examples as authored illustrations. Actual evaluations must record model version, input, output, and assessment; do not present expected answers as observed results.
- See [acceptance cases](tests/acceptance-test-cases.zh-CN.md), [LICENSE](LICENSE), and [NOTICE.md](NOTICE.md). A checklist is not proof that tests have run or that third-party rights are cleared.

检查相对链接、版本页码和引文标记；不要提交全书、扫描页、真实命盘、咨询记录、密钥或电脑路径。虚构演示和实际测试记录必须分开。实际测试需保存模型版本、输入、输出和评审结果；验收用例不能冒充已通过的测试。

## Publishing a separate copy / 发布自己的副本

For a separate repository, upload the reviewed public folder's contents while preserving its directory structure. Upload expanded files, not just a ZIP. Review the file list and rendered README before publishing. Never upload the private working directory wholesale. Git ignore rules do not inspect or block manual browser uploads.

如需发布到自己的仓库，上传检查过的公开目录内容，保持目录结构；上传展开后的文件，不只上传 ZIP。提交前检查文件清单，公开前检查首页与链接。不要把私人工作目录整体拖入；`.gitignore`不能检查或阻止浏览器手动上传。私有仓库也不代替第三方版权许可。
