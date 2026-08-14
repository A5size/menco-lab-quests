# menco-lab-quests (テンプレート)

MENCO-LAB の依頼書(自作課題)投稿・共有カタログ。このディレクトリは本体リポジトリ側の下書きで、
専用公開リポジトリ新設後にそのまま push する。手順は docs/forge/ugc-repo-spec.md。

- 投稿: Issue テンプレート「依頼書の投稿」にゲーム内発行コード(MENCOQ1…)を貼る
- 検証: Actions が Releases の検証機(タグ `validator`, `menco-validator-linux.tar.gz`)で
  復号→静置→クリア証明再シミュレーションを実行し、合格のみ `catalog/quests.json` へ収載
- ゲームは `catalog/quests.json` を取得して「依頼書」棚に表示する
