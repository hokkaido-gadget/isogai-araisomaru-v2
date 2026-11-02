# isogai-araisomaru-v2（LP改修版・検証用）

磯貝嘉市商店「日高昆布豚まん あらいそまる」公式LPの**改修版ドラフト**を、本番とは分けて検証するためのリポジトリです。

## 本番はこちら（このリポジトリではありません）
- 本番リポジトリ: https://github.com/hokkaido-gadget/isogai-araisomaru
- 本番サイト（GitHub Pages）: https://hokkaido-gadget.github.io/isogai-araisomaru/
- 購入先: https://www.kaichi-shoten.com/

## このリポジトリの状態
- `index.html` は改修ドラフトです。画像・動画（assets）は容量の都合で本番Pagesのものを絶対URLで参照しています。正式に切り替える際は assets の移行が必要です。
- 主な改修点: 購入案内セクション追加（送料目安表・まとめ買い試算・注文の流れ・FAQ）、価格表記の「税込」統一、OGP・favicon追加、フッター拡充。
- GitHub Pagesを有効化すると https://hokkaido-gadget.github.io/isogai-araisomaru-v2/ で確認できます（Settings → Pages → Deploy from a branch → main / (root)）。

## 公開前の要確認
- あらいそまるの送料にクール便加算が適用されるか（試算は加算込み前提）。
- アクセス解析（GA4等）は測定ID未取得のため未設置。index.html 内に設置場所のコメントあり。
