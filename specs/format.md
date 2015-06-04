# 青空文庫のテキスト形式

そのままでも人が読めることを前提に作られた点で、Markdownなどに通ずるものがあります。ただし、注記など複雑なルールが多数存在。テキストからXHTMLするツールが作られた時点で文法が厳格化されたようです。

## 本文

全体像については、[入力ファイルを「テキスト版」に仕上げるために](http://www.aozora.gr.jp/KOSAKU/textfile_checklist/index.html)を参照のこと。

- [ルビ](http://www.aozora.gr.jp/KOSAKU/MANUAL_2.html#ruby) - 文字種境界または`|`が基準
- [見出し](http://www.aozora.gr.jp/annotation/heading.html) - 「開始／終了型」になるものあり
- [強調](http://www.aozora.gr.jp/annotation/emphasis.html) - 「開始／終了型」になるものあり
- [外字](http://www.aozora.gr.jp/annotation/external_character.html) - 文字コードについて言及
- [外字注記辞書](http://www.aozora.gr.jp/gaiji_chuki/)
- そのほか全ての[注記一覧](http://www.aozora.gr.jp/annotation/index.html)

説明のまとまった部分を見つけられませんでしたが、注記には

- 「前方参照型」 - `腹がへっても［＃「腹がへっても」に傍点］`
- 「開始／終了型」 - `［＃傍点］青空文庫で読書しよう［＃傍点終わり］`

があります。ルビの場合は文字種境界または`|`を基準に前方参照します。

## メタデータ

- 冒頭と末尾 - [青空文庫収録ファイルへの記載事項](http://www.aozora.gr.jp/guide/kisai.html)
- 冒頭に加える記号の説明 - [テキスト中に現れる記号について](http://www.aozora.gr.jp/KOSAKU/txt_chu_kigo.html)
- [青空文庫における書誌データのとりかた](http://www.aozora.gr.jp/metadata_collection/index.html)

メタデータも本文と同じファイルに書き、冒頭/本文/末尾 の区切りタグはありません。

### 参考

- [青空文庫の注記記法改訂検討のまとめ](http://togetter.com/li/61118)
