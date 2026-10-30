<p align="center">
  <b>Brian</b> · Hanoi, Vietnam<br>
  <i>Building software. Recording lessons. Sharing knowledge.</i>
</p>

---

I work on AI engineering and cloud, and I write down what the work teaches.

Most of what I build sits around the work rather than inside it: the harness a coding agent runs in, the spec a team and a model can both read the same way, the note that stops the next project paying for the same lesson twice. Every system leaves a trace, and most of that trace disappears when the project ends. I try to keep it.

**What I focus on**

- **Agents in production** - harnesses, specs and guardrails for AI coding agents. Rules that fail the build, not rules that advise.
- **Cloud as an operating model, not a place** - the useful question is rarely "is cloud better", it is who should carry a particular risk and what it is worth to hand it over.
- **Writing it down** - in English, Vietnamese and Japanese, because a lesson only counts if the reader can read it.

**What I am working on**

- **[agent-security-audit](https://github.com/nguyenhx2/agent-security-audit)** - a read-only security audit skill for Claude Code. It fingerprints the stack and the industry, runs pinned scanners, checks what you actually deploy against live advisories (CISA KEV, NVD, EPSS, IPA, JPCERT/CC, JVN), has models hunt what scanners miss, and tries to refute every finding before it reaches the report. Markdown, HTML and Excel, in English and Japanese. Scanners update on a schedule, smoke-tested and reviewed, never on their own. [Guide](https://nguyenhx2.github.io/agent-security-audit/).
- **[agent-harness-bootstrap](https://github.com/nguyenhx2/agent-harness-bootstrap)** - two Claude Code skills. One turns an idea, a transcript or a pile of legacy docs into a spec. The other reads your repo and generates the `.claude/` frame the agent runs inside.
- **[Engineering Journal](https://www.engineeringjournal.dev/)** - a living notebook for modern engineering. Notes from actually building the thing. Not a news blog.
- **[From Ground to Cloud](https://fromgroundtocloud.com/)** - an open, vendor-neutral guide to cloud computing, in English, Vietnamese and Japanese.
- Smaller public things: **[ggchat-manager](https://github.com/nguyenhx2/ggchat-manager)** for running Google Chat at scale (bulk actions, conversation export, a job queue), **[transora-cloud](https://github.com/nguyenhx2/transora-cloud)**, the optional Cloudflare Worker behind the Transora translation extension.

**Three rules I hold myself to**

- An unknown never becomes an invented fact. It becomes a flagged assumption with a named owner.
- If a rule matters, make it fail the build. Advice that only advises gets ignored.
- Write it down in the language the reader thinks in.

<details>
<summary><b>日本語</b></summary>

<br>

AIエンジニアリングとクラウドを中心に開発し、そこで学んだことを書き残しています。

作っているものの多くは、仕事そのものよりもその周りにあります。コーディングエージェントが動く枠組み、人とモデルが同じように読める仕様書、次のプロジェクトが同じ授業料を払わずに済むための記録です。システムは必ず痕跡を残しますが、その多くはプロジェクトが終わると消えてしまいます。それを残しておきたいと思っています。

**取り組んでいる分野**

- **本番環境でのAIエージェント** - ハーネス、仕様、ガードレール。助言するだけのルールではなく、ビルドを止めるルールを。
- **クラウドは場所ではなく運用モデル** - 問うべきは「クラウドが優れているか」ではなく、そのリスクを誰が負い、手放す価値がいくらあるかです。
- **書き残すこと** - 英語・ベトナム語・日本語で。読み手が読めなければ、教訓は残らないからです。

**取り組んでいるもの**

- **[agent-security-audit](https://github.com/nguyenhx2/agent-security-audit)** - Claude Code向けの読み取り専用のセキュリティ監査スキル。技術スタックと業種を判定し、固定したスキャナを実行し、実際にデプロイするものを最新の脆弱性情報（CISA KEV、NVD、EPSS、IPA、JPCERT/CC、JVN）と照合し、スキャナが見逃す欠陥をモデルが探し、すべての指摘を報告前に反証にかけます。報告書は Markdown、HTML、Excel、日本語と英語。スキャナは定期的に、スモークテストとレビューを経て更新され、勝手に切り替わることはありません。[ガイド](https://nguyenhx2.github.io/agent-security-audit/guide/ja/)
- **[agent-harness-bootstrap](https://github.com/nguyenhx2/agent-harness-bootstrap)** - Claude Code向けの2つのスキル。アイデアや議事録、レガシー資料から仕様を作り、エージェントが動く `.claude/` の枠組みをリポジトリに合わせて生成します。
- **[Engineering Journal](https://www.engineeringjournal.dev/)** - 現代のエンジニアリングのための「生きたノート」。実際に作った経験からの記録です。
- **[From Ground to Cloud](https://fromgroundtocloud.com/)** - ベンダーニュートラルなクラウド入門。英語・ベトナム語・日本語。
- 小さめの公開リポジトリ：Google Chat を大規模に運用するための **[ggchat-manager](https://github.com/nguyenhx2/ggchat-manager)**、翻訳拡張機能 Transora のための任意の Cloudflare Worker **[transora-cloud](https://github.com/nguyenhx2/transora-cloud)**。

</details>

**Support**

Everything above is free and open. If it saves you time, you can support the upkeep (re-verifying standards and feeds, keeping scanners current, paying for real benchmark runs) through **[GitHub Sponsors](https://github.com/sponsors/nguyenhx2)** or **[Buy Me a Coffee](https://buymeacoffee.com/nguyenhx2)**.

<p align="center"><sub>Most of what is here is working notes. The links above are the ones worth your time.</sub></p>
