---
layout: contents
language: ja
title: chmpxpx_set_debug_level_warning
short_desc: CHMPX PHP Extension - PHP Extension library for CHMPX
lang_opp_file: chmpxpx_set_debug_level_warning.html
lang_opp_word: To English
prev_url: chmpxpx_set_debug_level_silentja.html
prev_string: chmpxpx_set_debug_level_silent
top_url: chmpxpxja.html
top_string: chmpxpx Functions
next_url: chmpxpx_slv_receiveja.html
next_string: chmpxpx_slv_receive
---

# chmpxpx_set_debug_level_warning
ライブラリのログレベルをwarningにする

## 説明

```
function chmpxpx_set_debug_level_warning(): void {}
```

ライブラリのログレベルをwarningにします。

## パラメータ
この関数にはパラメータはありません。

## 戻り値
値を返しません。 

## 例
- 例 1 - ライブラリのログレベルをwarningにする

```
<?php
var_dump(chmpxpx_set_debug_file("/tmp/chmpx.log"));
chmpxpx_set_debug_level_warning();
?>
```

上の例の出力は以下となります。

```
NULL
```


## 参考
- [chmpxpx_bump_debug_level](chmpxpx_bump_debug_levelja.html) - ログレベルを変更する
- [chmpxpx_set_debug_file](chmpxpx_set_debug_fileja.html) - ログ出力先ファイル名を指定する
- [chmpxpx_set_debug_level_error](chmpxpx_set_debug_level_errorja.html) - ライブラリのログレベルをerrorにする
- [chmpxpx_set_debug_level_message](chmpxpx_set_debug_level_messageja.html) - ライブラリのログレベルをmessage(info相当）にする
- [chmpxpx_set_debug_level_silent](chmpxpx_set_debug_level_silentja.html) - ライブラリのログを出力しない
- [chmpxpx_unset_debug_file](chmpxpx_unset_debug_fileja.html) - ログ出力先を標準エラーに指定する