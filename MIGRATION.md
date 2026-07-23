# なるちゃんプロジェクト移行記録

移行日: 2026-07-23

## 統合先

`/Users/naru/Documents/Codex/2026-07-23/v/naruchan-project`

## 移行元

| 種別 | パス | 扱い |
| --- | --- | --- |
| VSCode側の新しい本体 | `/Users/naru/Projects/naruchan-project` | ベースとして全内容をコピー |
| 旧GitHubクローン | `/Users/naru/Documents/GitHub/naruchan-project` | 差分確認後、旧READMEを `docs/archive/github-readme-legacy.md` に保存 |
| ChatGPT側の構想・投稿支援 | `/Users/naru/naru-life-os` | `life-os/` 配下へコピー |
| 空の候補フォルダ | `/Users/naru/Desktop/なるちゃん` | 空だったため未移行 |

## 元Git情報

- VSCode側の本体: `1e651ef73ae7f6bb15de789df11cd0f836278865`
- 旧GitHubクローン: `451200198d39aea6f5a99bfd9670d81cbca16025`
- remote: `https://github.com/otake060946-naru/naruchan-project.git`

## 方針

- `.git` と `.DS_Store` は統合先へ持ち込まない
- 新しい `naruchan-project` を正本として扱う
- 旧GitHubクローンにだけ残っていた情報は README に反映する
- ChatGPT由来の Naru Life OS は、なるちゃんプロジェクトの将来構想・Instagram投稿支援として `life-os/` に同居させる
- 既存データは削除せず、今後の更新は原則として追記方式で行う

## 取り込んだ追加情報

- 誕生日: 2025-12-11
- 現在の状況:
  - ワクチン3回接種済
  - 狂犬病未接種
  - お迎え準備中
- 今後の予定:
  - 購入履歴データ整理
  - 医療記録管理
  - 訓練記録管理
  - 管理アプリ開発
  - Instagram投稿支援
  - 写真・動画・会話ログのライフログ化

## 確認結果

- `naruchan-project` 本体のデータ、写真、CSV、Markdown記録をコピー済み
- `naru-life-os` の構想ドキュメントとInstagram画像アセットをコピー済み
- 旧GitHubクローンは新しい本体より古く、README以外の独自ファイルは見当たらなかった
