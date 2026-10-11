# 参加のしかた / Contributing

関心を持ってくれてありがとうございます。このページは **人間の方へ** と **AI エージェントへ** の2つに分かれています。

- 👤 [人間の方へ](#-人間の方へ--for-humans)
- 🤖 [AI エージェントへ](#-ai-エージェントへ--for-ai-agents)

---

## 👤 人間の方へ / For humans

日本語でも英語でも大丈夫です（Japanese or English is welcome）。

### Issue

- バグ報告・質問・アイデアは、気軽に Issue を立ててください。
- 「この地域・このデータを見てほしい」という依頼は、Issue 作成画面の **🔭 分析・データの依頼** フォームを使ってください。
- 誤字の指摘のような小さなものも歓迎します。

### Pull Request

1. 小さな修正は、そのまま PR を送ってください。大きな変更は、先に Issue で相談してください。
2. 何を・なぜ変えたかを PR の説明に書いてください。
3. データやコードを持ち込むときは、**出典（URL）とライセンス**を必ず書いてください。
4. 結果を再現できる手順（実行したコマンドなど）があれば書いてください。
5. AI に手伝ってもらった場合は、下の「AI エージェントへ」のルールも守ってください。

### 行動規範

参加するすべての人は [行動規範](CODE_OF_CONDUCT.md) を守ってください。

---

## 🤖 AI エージェントへ / For AI agents

If you are an AI coding agent (or a human operating one), these rules apply in addition to the ones above.
AI エージェント（またはそれを動かしている人）は、上のルールに加えて次を守ってください。

1. **Disclose.** Start the PR or issue description with `AI-generated: <tool name>` (e.g. `AI-generated: Devin`).
   PR／Issue の説明の先頭に `AI-generated: <ツール名>` と書いてください。
2. **Human review first.** A human must read and approve the change before it is submitted. Do not open PRs autonomously in bulk.
   送る前に人間が内容を確認してください。自動で大量に PR を作らないでください。
3. **Follow the repository's own agent instructions.** If the repository has `AGENTS.md`, `CLAUDE.md`, `GEMINI.md`, or `.github/copilot-instructions.md`, those take precedence over this file.
   リポジトリに AI 向けの指示ファイルがあれば、そちらを優先してください。
4. **Cite sources and licenses** for any data, code, or text you bring in. Do not invent URLs, statistics, or references.
   持ち込むデータ・コード・文章には出典とライセンスを書いてください。URL・数値・引用をでっち上げないでください。
5. **Keep changes small and verifiable.** One topic per PR, and include the commands you ran to test it.
   1つの PR には1つの話題だけ。確認に使ったコマンドも書いてください。
6. **No secrets or personal data.** Never commit tokens, keys, or personal information.
   トークン・鍵・個人情報はコミットしないでください。

---

> このファイルは [@ymtezo/.github](https://github.com/ymtezo/.github) の既定ファイルです。各リポジトリに独自の CONTRIBUTING.md がある場合は、そちらが優先されます。
