---
layout: contents
language: ja
title: chmpxpx_bump_debug_level
short_desc: CHMPX PHP Extension - PHP Extension library for CHMPX
lang_opp_file: chmpxpx_bump_debug_level.html
lang_opp_word: To English
prev_url:
prev_string:
top_url: chmpxpxja.html
top_string: chmpxpx Functions
next_url: chmpxpx_createja.html
next_string: chmpxpx_create
---

# chmpxpx_bump_debug_level
ログレベルを変更する

## 説明

```
function chmpxpx_bump_debug_level(): void {}
```

ログレベルを変更します。ログレベルは、関数が呼ばれるごとに変わります。順番は、error -> warning -> message(info) -> dump(debug) -> silent(出力しない) の順番です。silentの状態で呼ばれると、errorになります。PHPのログレベルにあたる、emergency, alert, noticeは未定義です。 

## パラメータ
この関数にはパラメータはありません。

## 戻り値
値を返しません。 

## 例
```
php -r 'var_dump(chmpxpx_bump_debug_level());'
```

上の例の出力は以下となります。

```
NULL
```


## 参考
- [chmpxpx_set_common_attr](chmpxpx_set_common_attrja.html) - キーの基本属性を設定する
- [chmpxpx_set_debug_file](chmpxpx_set_debug_fileja.html) - ログ出力先ファイル名を指定する
- [chmpxpx_set_debug_level_error](chmpxpx_set_debug_level_errorja.html) - ライブラリのログレベルをerrorにする
- [chmpxpx_set_debug_level_message](chmpxpx_set_debug_level_messageja.html) - ライブラリのログレベルをmessage(info相当）にする
- [chmpxpx_set_debug_level_silent](chmpxpx_set_debug_level_silentja.html) - ライブラリのログを出力しない
- [chmpxpx_set_debug_level_warning](chmpxpx_set_debug_level_warningja.html) - ライブラリのログレベルをwarningにする
- [chmpxpx_unset_debug_file](chmpxpx_unset_debug_fileja.html) - ログ出力先を標準エラーに指定する