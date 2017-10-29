# quick-search

コマンドラインからGoogle検索ができるツールです。マウスを使わず検索し、タイトルやリンク、内容を表示します。対話形式で実行することができ、気になったリンクには番号を入力することで辿ることができます。

# コンセプト

quick-searchは学習コストを少なくするため、可能な限りオプションやコマンド特有の使い方を省いています。「シンプル」に「見やすく」を基本設計として、直感的に操作できるようになっています。

# 実行環境

現行は、以下の環境でのみ実行検証を行なっています。

|ツール/OS|バージョン|
|:-----------|:------------|
|python|python3.5 or later|
|OS|CentOS6 or later|

# 使い方

```
# 構文
$ ./quick-search [検索クエリ]

# 例
$ ./quick-search テスト クエリ
```

# 実行後オプション

実行後は対話形式でオプションを指定することができます。デフォルトでは5つずつリンク数が表示されます。

|オプション|説明|
|:-----------|:------------|
|Enter| 次へ進む|
|リンク番号|指定したリンク番号を表示する|
|q|Quit|