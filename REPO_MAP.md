# REPO_MAP — jma-pmi-playbook

最終更新: 2026-08-12

## 正の所在（Single Source of Truth）

このリポジトリは**公開出力とエージェントの実行場所**であり、書類の正本置き場ではない。

- **PMIのやり方の正** = Drive上の「PMI_現場PMIプレイブック概要」最新版（現在 v2.9）
- **タスクの正** = Drive上の shinozuka / goto ダッシュボード xlsx
- **週次の正** = Drive「PMI定例」フォルダの最新アジェンダ doc

## フォルダ/ファイル分類

### 稼働中（公開URLが生きている・動かさない）

| パス | 内容 |
|---|---|
| `qsc/index.html` | QSCチェック表 v1.3（眼科クリニック 受付・予約・電話・患者対応） |

※経営理念のページはこのリポジトリには存在しない（別の場所でホスティングされている可能性。要確認）。

### エージェント関連（2026-08-12 プライベートリポジトリへ移設）

PMI状態エージェント（agent/・state/・SPEC.md）は、内部情報を公開リポジトリに
置かないため **非公開リポジトリ `jma-pmi-agent`** に移設した。
このリポジトリには公開ページのみを置く。

### レガシー候補（後日 archive/ へ移動予定。今日は未着手）

| パス | 内容 | 備考 |
|---|---|---|
| `index.html` | PMI資料体系マップ（INDEX）v0.1 | 削除済みの shinozuka/goto へのリンクを含む（リンク切れ） |
| `plan-100days.html` | 一医院PMI 100日プラン v0.1（汎用） | |
| `todo-tracker.html` | PMI 100日 TODOトラッカー v0.1（汎用） | |
| `batch-questions.html` | P0起動パック バッチ質問リスト v0.1（汎用） | |
| `tpl-06-d1-announce.html` | ⑥ D1アナウンス台本＋従業員説明資料 テンプレート v0.1 | |
| `tpl-07-interview.html` | ⑦ 個別面談シート テンプレート v0.1 | |
| `tpl-08-faq.html` | ⑧ FAQ 2種 テンプレート v0.1 | |
| `tpl-14-kickoff.html` | ⑭ キックオフパック テンプレート v0.1 | |

### 削除済み（2026-08-12、git履歴から復元可能）

- `shinozuka/`（100日プラン・TODOトラッカー・バッチ質問リスト）— 内容が白紙に戻ったため公開停止
- `goto/`（100日プラン・TODOトラッカー）— 同上
- 復元する場合: `git checkout a39df31^ -- shinozuka goto`
