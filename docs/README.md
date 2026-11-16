# AD-EDIT5 技術仕様書 / Technical Documentation

## AIによる開発・カスタマイズを支援する公開技術仕様書

AD-EDIT5では、AIを活用したWebサイト構築・CMSカスタマイズ・保守作業を支援するため、技術仕様書をMarkdown形式で整備し、一般公開しています。

これらの仕様書は、人間が読むための技術資料であると同時に、**AI開発支援ツールがCMSの構造や動作仕様を理解するための参照資料**として作成されています。

ChatGPT、Codex、ClaudeなどのAI開発支援ツールに仕様書を参照させ、人間が自然言語で指示することで、AD-EDIT5の仕様に沿った開発・修正作業を進めることを想定しています。

### AIとの協働による開発

基本的な作業の流れは次のとおりです。

1. **人間が指示する**  
   Webサイトの構築、機能追加、デザイン変更、CMSのカスタマイズなど、実施したい作業をAIに指示します。

2. **AIが仕様書を参照する**  
   関連するMarkdown仕様書をAIに読み込ませ、AD-EDIT5の構造・設定・動作仕様を把握させます。

3. **AIが作業を支援する**  
   仕様書に基づいて、HTML・CSS・JavaScript・Perl CGIなどのコード作成や修正を支援します。

4. **人間が確認・検証する**  
   AIによる変更内容を確認し、必要な動作検証を行います。

※ AD-EDIT5自体に生成AIが組み込まれているわけではありません。外部のAI開発支援ツールとの協働を想定した技術仕様書です。

## 公開技術仕様書

導入・初期設定、スキン構築、CMSの内部構造、各エディタ、APIなどに関する仕様書を公開しています。

技術仕様書は公式サイトで随時更新しており、ファイル名を維持しながら内容を更新する運用です。

**最新の仕様については、必ず公式サイトをご参照ください。**

**[AD-EDIT5 公式技術仕様書一覧（最新版）](https://adedit.net/docs/)**

### 配布パッケージに含まれる仕様書

AD-EDIT5 v5.1.0の配布パッケージ `adedit5.1.0.pack.zip` には、`/docs/` フォルダに公開技術仕様書33ファイル（Markdown形式）が同梱されています。

これらはv5.1.0リリース時点の仕様書です。

- [GitHub Releases（v5.1.0）](https://github.com/NorenzPRO/AD-EDIT5/releases/tag/v5.1.0)
- [公式ダウンロードページ](https://adedit.net/download/)

---

## English — AI-Readable Technical Documentation

AD-EDIT5 provides publicly available technical documentation in Markdown format, designed to support **AI-assisted website development, CMS customization, and maintenance**.

The documentation is intended not only for human developers but also as a reference for AI coding assistants.

By providing these documents to AI tools such as
