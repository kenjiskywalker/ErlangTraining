2016/06/27

## nunulk

### やったこと

Dialyzer 使ってみた。

### 困ったこと

rebar3 dialyzer 実行時に謎のエラー

```
The variable _ can never match since previous clauses completely covered the type 'false'
```

原因はこれっぽい
https://github.com/erlang/otp/pull/1002/files

assert の代わりに assertEqual 呼ぶようにしたら消えた。

### 次回やること

いきなりこの辺やってみようかな…
https://www.ymotongpoo.com/works/lyse-ja/ja/16_what_is_otp.html

