# .github

@ymtezo の全リポジトリ共通の既定ファイル置き場です。各リポジトリに同じ種類のファイルが無いとき、ここのファイルが使われます。

Default community health files for all repositories owned by @ymtezo.

### 👤 人間向け

| ファイル | 内容 |
|---|---|
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | 行動規範（Contributor Covenant 3.0 日本語版） |
| [CONTRIBUTING.md](CONTRIBUTING.md#-人間の方へ--for-humans) の「人間の方へ」 | 参加のしかた |
| [SECURITY.md](SECURITY.md) | 脆弱性の報告方法 |
| [SUPPORT.md](SUPPORT.md) | 質問の窓口 |
| [.github/ISSUE_TEMPLATE/](.github/ISSUE_TEMPLATE/) | 「この地域・このデータを見てほしい」依頼フォーム |

### 🤖 AI エージェント向け

| ファイル | 内容 |
|---|---|
| [CONTRIBUTING.md](CONTRIBUTING.md#-ai-エージェントへ--for-ai-agents) の「AI エージェントへ」 | AI が PR／Issue を作るときのルール（AI 製と明記・人間の確認・出典必須など） |

AI 向けのルールを別ファイルにせず CONTRIBUTING.md の中に置いているのは、`AGENTS.md` などは既定ファイルとして全リポジトリに配れず、CONTRIBUTING.md なら配れるうえに AI エージェントも読むからです。各リポジトリに `AGENTS.md` などがあれば、そちらが優先されます。

仕様：[GitHub Docs — Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
