---
slug: ja-jp/real-world-development/cli
title: "GitHub Copilot CLI"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli)** は、エージェント型コーディング アシスタントの GitHub Copilot をターミナルで利用できるようにします。コードベースを探索し、コードを生成し、コマンドを実行し、外部ツールに接続できます。すべてコマンド ラインから行えるため、グラフィカル エディターに切り替えずに作業を続けられます。

このワークショップでは、Tailspin Toys の一連の作業を進めます。GitHub Codespaces でプロジェクトを準備し、星評価を追加して最初のプル リクエスト (PR) をマージします。続いて、カスタム指示、スキル、MCP ツール、QA エージェント、Agent Merge を使ってフィルター機能を実装します。最後にスラッシュ コマンドを確認し、再利用できる知識を振り返ります。

## 演習

| 演習 | トピック | 説明 |
|----------|-------|-------------|
| [0. 前提条件][ex0] | セットアップ | プロジェクトと Codespace を準備する |
| [1. Copilot CLI をインストールする][ex1] | インストール | Copilot CLI をインストールして認証し、基本操作を確認する |
| [2. 星評価を追加する][ex2] | 最初の変更 | 既存の評価を表示し、最初の PR をマージする |
| [3. エージェント モード: Plan と Autopilot][ex3] | エージェント モード | Issue から計画し、Autopilot で実装して Interactive でレビューする |
| [4. カスタム指示で Copilot をガイドする][ex4] | コンテキスト | 指示を更新してフィルター機能に適用する |
| [5. quality-checks スキルをカスタマイズして使う][ex5] | 繰り返し可能なチェック | スキルのレポート形式を変更してプロジェクトのチェックを実行する |
| [6. Playwright MCP で機能を検証する][ex6] | ブラウザーでの確認 | CLI で MCP を構成し、フィルターの動作を確認する |
| [7. QA エージェントを作成して使う][ex7] | 要件とカバレッジ | 要件、カバレッジ、検証結果を確認する |
| [8. 機能の PR を作成してマージする][ex8] | レビューとマージ | 変更全体をレビューし、Agent Merge を使う |
| [9. GitHub Copilot CLI のスラッシュ コマンド][ex9] | CLI 機能 | コンテキスト、モデル、共有、任意の委任を確認する |
| [10. まとめと次のステップ][ex10] | まとめ | ワークフロー、再利用可能なカスタマイズ、関連リソースを確認する |
| [オプション: Foundry を組み込む][foundry] | ホスト型エージェント | モデルを準備し、カタログを使うエージェントをデプロイして Web サイトに接続する |

## 前提条件

このワークショップに参加する前に、次を準備してください。

- [ ] **Copilot Student、Pro、Pro+、Business、Enterprise** のいずれかの有効なプランがある GitHub アカウント
- [ ] リポジトリと Codespace を作成する権限
- [ ] ターミナルまたはコマンド ライン操作の基本的な知識

> [!TIP]
> 有料プランがありませんか。認証済みの学生は [GitHub Education][callout-student-plan-education] を通じて GitHub Copilot を無料で利用できます。**Copilot Student** プランには、このワークショップで使用する agent、MCP、code review、Copilot CLI の機能が含まれているため、すべての harness を完了できます。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> Copilot Business または Copilot Enterprise を使用している場合は、管理者が Copilot CLI を有効にしていることを確認してください。

## はじめる

**[演習 0: 前提条件から始める →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-install-copilot-cli/
[ex2]: 2-add-star-rating/
[ex3]: 3-agent-modes/
[ex4]: 4-custom-instructions/
[ex5]: 5-agent-skills/
[ex6]: 6-mcp-playwright/
[ex7]: 7-qa-agent/
[ex8]: 8-create-pull-request/
[ex9]: 9-cli-power-tools/
[ex10]: 10-review/
[foundry]: 8-foundry-agent/
