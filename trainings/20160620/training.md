# 20160620

- やったこととか所感とかはまってることとか書く

## 阿部（み）

- `brew install erlang`
- 構文を書いてみる
- 変数代入できないことを体験

## nunulk

### やったこと

- [Cowboy](http://ninenines.eu/docs/en/cowboy/1.0/guide/) で Hello World

### 困ったこと

- Cowboy は、アプリケーションの作り方が、Makefile 使う方式で、他にも rebar 使う方式があったりして統一されてないので、依存関係の管理とかが分かりにくかった
  - 正解は Makefile に DEPS = cowboy を追加

### 次回やること

- [Dialyzer](http://erlang.org/doc/apps/dialyzer/dialyzer_chapter.html) 導入してみたい
