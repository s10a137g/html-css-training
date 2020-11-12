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

## 修正する時に気をつけたこと

- ブロック単位
  - portfolio
  - wrap-clearfix
  - header
  - main
  - sidebar
  - footer

- あとでエレメントごとにCSSがあてられるように、なるべく各要素にclass名をつけるようにした。

## 気になったこと

- 良い設計がいまいちわからない。。。参考にしたほうがいい実際のサイトとかある？
- 最初wrapクラスをmainクラスに統合してしまうと上手くいかなかった。(::after が上手く効かなかった)
