# HTML,CSS演習

## 各ファイル概要
### index.html
HTMLファイル

### main.scss
SCSSファイル。
SCSS記法で記述する。

### package.json
[【初心者向け】NPMとpackage.jsonを概念的に理解する](https://qiita.com/righteous/items/e5448cb2e7e11ab7d477)

npm にとってパッケージというのはpackage.jsonというファイルの親ディレクトリに含まれるファイル群である。
例えばディレクトリ~/projects/my-project/にpackage.jsonがあれば、~/projects/my-project/がそのプロジェクトのルートディレクトリ(一番根っこのディレクトリ)となる。
npm のコマンドは常にルートディレクトリで実行することになる。

### webpack.config.js
webpackの設定ファイル

webpackとは？？

> Webpackは自分で書いたJSとライブラリとして読み込んでいるJSを一つのJSファイルに
> まとめてくれます。
> また、JSライブラリで読み込む必要があるCSSファイルたちもJSにまとめてくれます。（私達が書くCSSもまとめることが可能です。）
> そして、それらのCSSで読み込む画像ファイルもDataURI(Base64形式)に変換してJSファイルに
> まとめてくれます。
> 
> つまり、JS、CSS、画像ファイルを一つのJSファイルにまとめてくれます。

[Webpackってどんなもの？](https://qiita.com/kamykn/items/45fb4690ace32216ca25)

## SCSS記法

### ディレクトリ構成
色々あるみたいだけれど以下参考。

[Webサイトのディレクトリ構造とその命名規則に悩む](https://qiita.com/y_hokkey/items/871c23c24d31021d7c40)

```
 dest       -- コンパイル結果
 src        -- コンパイル前
  index.html
  assets    -- コンパイル後に残らないフォルダは、先頭に「_」を付ける
    _coffee -- CoffeeScript
    _sass   -- Sass
      lib   -- Sassの共通ライブラリ
    vendor  -- 外部ライブラリはここ。bower_componentの名前を変えて運用
    js
    css
    img 
```
