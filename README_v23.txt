HARMONIA v23 TUTORIAL PATCH

実装内容
- チュートリアルを実際のLIVE画面へ統合
- 最初に6枚のコンボスキル候補から4枚を選択
- チュートリアルでは最初にSHOUTをガイド
- 4枚SET後、実際の存在波盤面で「声響→声響」をなぞってSHOUTを成立
- cutin_1.png が発動
- 試験官「……凄まじい歌力だ！」→「もっと！」→凛「……言われなくても」
- TUTORIAL COMPLETE後、本番LIVEへシームレス移行
- 本番は 5ターン × 各30秒
- 毎ターン、8種のコンボプールから6枚ランダム提示 → 4枚選択
- 成立コンボ数に応じ cutin_1〜4.png を使用
- DEBUGから旧LIVE UI B/Cを撤去

GitHub Desktop:
この2ファイル(index.html / live.html)をローカルの song-for-life-prototype に上書き
→ Summary入力 → Commit to main → Push origin
