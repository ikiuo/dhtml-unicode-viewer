# Unicode による文字表

ストレージ上の HTML ファイル サイズを小さくしたいので文字表を動的に生成して表示します。

- unicode-viewer1.html -- Unicode 文字表その１
- unicode-viewer2.html -- Unicode 文字表その２
- country-flags.html -- 国旗表

## Unicode 文字表

Unicode 14.0 における分類を選択して文字表を設定に応じて表示します。

## 国旗表

アルファベット('A'〜'Z')の２文字による国コードの一覧（26×26）です。

アルファベットを

- A → U+1F1E6
- ...
- Z → U+1F1FF

に変換するだけの単純なものです。

例えば、日章旗(JP) 🇯🇵 は U+1F1EF と U+1F1F5 の組み合わせです。
UCS-4 では２文字ですが、UCS-2 では

- U+1F1EF は U+D83C と U+DDEF
- U+1F1F5 は U+D83C と U+DDF5

の組み合わせ（サロゲート コード）になるので、４文字に見えます。
