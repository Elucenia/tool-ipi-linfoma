<!-- ELUCENIA technical documentation · ipi-linfoma · ja · no clinical/professional/rights approval -->

# IPI（国際予後指標）

[条件・出典・許諾](https://elucenia.org/ja/tools/ipi-linfoma)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 年齢 \> 60 歳

`idade`

### 血清LDHが基準値上限を超える

`ldh`

### ECOG ≥ 2

`ecog`

### Ann ArborステージIIIまたはIV

`estadio`

### 節外病変が1部位を超える

`extranodal`

## 方法の版

International Prognostic Index 1993：5因子、0–5；NCCN-IPIやR-IPIではない

## 記載された計算式

各因子1点：年齢\>60歳·LDH上昇·ECOG ≥2·病期IIIまたはIV·節外病変が1部位より多い。最大：5。

## 限界・対象集団

成人の侵攻性非ホジキンリンパ腫に対する古典的な予後指数で、ドキソルビシンを用いた歴史的コホートの治療前に開発されました。古典的IPI、年齢調整IPI、R-IPI、NCCN-IPIを区別してください。歴史的な確率は、全ての亜型や現在の治療で較正されていることを示しません。

## 参考文献

- [The International Non-Hodgkin's Lymphoma Prognostic Factors Project. A predictive model for aggressive non-Hodgkin's lymphoma. N Engl J Med, 1993.](https://doi.org/10.1056/NEJM199309303291402)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

低リスク：5年生存率73%

87%で完全寛解（リツキシマブ前の時代）。


### 2

高中間リスク：5年生存率43%

55%で完全寛解。


### 3

低中間リスク：5年生存率51%

67%で完全寛解。


### 4

高リスク：5年生存率26%

44%で完全寛解。

