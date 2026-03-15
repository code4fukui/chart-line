# chart-line

リアルタイムでグラフを描画できる Webコンポーネントです。CSV データから線グラフを生成し、表示することができます。

## デモ

[デモページ](https://code4fukui.github.io/chart-line/)

## 機能

- 単一または複数の線グラフを描画可能
- コンテナサイズに合わせてグラフがレスポンシブに表示される
- 最小値やグラフ色などをカスタマイズできる属性を持つ
- インライン文字列や外部 CSV ファイルからデータを読み込める

## 使い方

`<chart-line>` 要素にデータを記述するか、`src` 属性で外部 CSV ファイルを指定することで、グラフを表示できます。

```html
<script type="module" src="./chart-line.js"></script>
<chart-line style="height:400px;width:600px;">
name,value
農林水産業,96777
行財政,47496
司法・安全・環境,44875
企業・家計・経済,28641
</chart-line>
```

## ライセンス

MIT License