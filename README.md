# bsb-qa-web-fixture

bellme.ai の develop 環境で「Webサイトを登録」の取り込みを確かめるための、**架空のサービス案内** を1枚だけ置いた公開ページです。顧客の資料・実在のサービスは含みません。

- 公開URL: https://zerocolored.github.io/bsb-qa-web-fixture/
- 書き換える場所: `index.html` の「1. 月額料金」の数字 **1か所だけ**
  - v1 = `4,800円`（既定）
  - v2 = `7,200円`
- `versions/index-v1.html` / `versions/index-v2.html` に2版の全文を置いてあります（戻すとき用）

## 書き換え手順（GitHub の画面だけで完結します）

1. https://github.com/zerocolored/bsb-qa-web-fixture/edit/main/index.html を開く
2. 「1. 月額料金」の行の `4,800円` を `7,200円` に直す（他の文字は触らない）
3. 緑の **Commit changes...** を押し、もう一度 **Commit changes** を押す
4. 公開ページに反映されるまで待つ

反映の実測値は `MEASURED.md` に書いてあります。
