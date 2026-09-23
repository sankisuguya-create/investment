# investment

個人専用の投資指標分析ツール「投資指標ワークベンチ」。
we.love-profit.com「シストレのススメ」の方法論（指標探索 → IC検証 → 累積リターン → 分位別 → 分布 → 演繹 → ストラテジー評価）を単一HTMLで実装。

## ファイル
- `index.html` — 本体（ブラウザで開くだけ・オフライン・外部通信なし・データは端末内のみ保存）
- `events_2007_2023.csv` — 経済指標・中央銀行発表カレンダー 2007〜2023/03（予想/結果入り・約7万件・ForexFactory由来）
- `glossary.txt` — 素人向け用語集
- `design.html` — 設計書

## 使い方
1. `index.html` をブラウザで開く
2. データ画面： 市場CSV（日経公式・VIX・stooq等）と `events_2007_2023.csv` を取込
3. 指標画面： 候補指標を追加（イベント系4種も可）
4. 分析 → 比較 → ストラテジーの順に検証
5. 週次蓄積： `nfs.faireconomy.media/ff_calendar_thisweek.xml` を保存して取込
