SONG FOR LIFE v25.2 DEBUG NAV

追加:
- index.html 上部に開発用DEBUGメニュー
  ADV START / TUTORIAL / LIVE / AFTER LIVE / RELOAD
- live.html に簡易DEBUG
  ADV / LIVE / AFTER
- adv_after.html に簡易DEBUG
  ADV / LIVE / RELOAD
- ルートはすべて相対URLで統一
- ?v=252 を付与してキャッシュを回避
- RELOAD はタイムスタンプ付きで強制再読み込み

確認用URL例:
https://song-for-life.netlify.app/index.html?v=252
https://song-for-life.netlify.app/live.html?v=252
https://song-for-life.netlify.app/live.html?tutorial=1&v=252
https://song-for-life.netlify.app/adv_after.html?v=252

GitHub Desktop:
このZIPの中身をリポジトリへ上書き
→ Summary: v25.2 debug nav
→ Commit to main
→ Push origin
