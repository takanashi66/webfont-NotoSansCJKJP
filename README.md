# Noto Sans CJK JPの設置

Noto Sans CJK JPをダウンロードして設置  
アスキー文字 + 非漢字文字 + 第1水準漢字をサブセット  
フォントの形式はwoffのみ(モダンブラウザのみ対応)

## Packages

+ laravel-mix
+ cross-env
+ browser-sync
+ browser-sync-webpack-plugin
+ css-mqpacker
+ jquery

## Laravel Mix

[参考](https://readouble.com/laravel/5.6/ja/mix.html "公式ドキュメント")

```
npm install
npm run watch
```
  * dev だと全タスク実行
  * production だとdevに加えて出力を圧縮
  * watch または watch-poll で変更を監視

### SVG Sprite

*src/svg/* のSVGからSVG Spriteを作る

```
npm run svg
```

## 参考

[Noto Sans CJK JP フォントをダウンロードしてサイトに適用する手順](https://qiita.com/nowri/items/1c69b9b25f2958bd9f97)
