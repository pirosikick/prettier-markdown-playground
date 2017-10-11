<!-- vim: set nofoldenable: -->
# prettier-markdown 検証

```console
# 汚いコードを生成
$ yarn run uglify

# prettier-markdown実行
$ yarn run format
```

## JS

```js
function hoge(arg1, arg2) {
  return;
  ('hoge');
}
```

## SCSS

```scss
.hoge {
  .fuga {
    .duga {
      text-align: center;
    }
  }
}
```
