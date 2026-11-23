<!-- BEGIN G-AGENT-PLATFORM RULES -->
## G-agent-platform 共通規約

このプロジェクトでは、まず `.agent/policies/workspace-agents.md` を読み、その共通規約に従う。
次に、このファイルの管理ブロック以外に記載されたプロジェクト固有ルールに従う。

- 共通の安全規約は、プロジェクト固有ルールや個別タスクで緩和しない。
- プロジェクト固有の共通ルールは `AGENTS.md` に記載する。`CLAUDE.md` と `GEMINI.md`
  の管理ブロック以外は、それぞれのCLI固有の補足として扱う。
- 高リスク操作では共通規約が指定するスキル・承認・検証を先に適用する。

このブロックは `.agent/1-loop/rules-sync.sh` により管理される。AGENTS.md 固有の指示はこのブロックの外に記載する。
<!-- END G-AGENT-PLATFORM RULES -->

## 学習記録と実習

- 学習ノートは `docs/` に、実習で作る ROS 2 パッケージは `src/` に置く。
- 手順を記録するときは、確認に使った環境、実行コマンド、期待する動作と実際の結果を記載する。
