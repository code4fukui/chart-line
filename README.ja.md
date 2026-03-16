Here is the Japanese translation of the provided English markdown chunk:

# chart-line
English README: [README.md](README.md)

CSVデータからラインチャートを作成するWebコンポーネント。

## デモ
[https://code4fukui.github.io/chart-line/](https://code4fukui.github.io/chart-line/)

## 機能
- 1行または複数行のデータセットをサポートします
- コンテナサイズに合わせてスケーリングするレスポンシブなデザイン
- 最小値、色などの属性をカスタマイズできます
- インラインテキストや外部CSVファイルからデータをロードできます

## 使用方法
`<chart-line>` 要素を使用するには、`chart-line.js` ファイルを読み込み、HTML にその要素を追加します:

```html
<script type="module" src="./chart-line.js"></script>
<chart-line>
  name,value
  A,30
  B,20
  C,70
</chart-line>
```

あるいは、外部の CSV ファイルからデータを読み込むこともできます:

```html
<chart-line src="https://example.com/data.csv"></chart-line>
```

## データ / API
このプロジェクトでは、データ可視化に [D3.js](https://d3js.org/) ライブラリを使用し、CSV データの解析に [CSV.js](https://js.sabae.cc/CSV.js) ライブラリを使用しています。

## ライセンス
このプロジェクトは [MIT License](LICENSE) のもとで公開されています。
