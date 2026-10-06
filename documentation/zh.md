<!-- ELUCENIA technical documentation · ipi-linfoma · zh · no clinical/professional/rights approval -->

# IPI（国际预后指数）

[条件、来源与许可](https://elucenia.org/zh/tools/ipi-linfoma)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 年龄 \> 60 岁

`idade`

### 血清 LDH 高于正常上限

`ldh`

### ECOG ≥ 2

`ecog`

### Ann Arbor III 或 IV 期

`estadio`

### 超过 1 个结外部位

`extranodal`

## 方法版本

International Prognostic Index 1993：5因素，0–5；非NCCN-IPI或R-IPI

## 已记录的公式

每项因素1分：年龄\>60岁·LDH升高·ECOG ≥2·III或IV期·超过1个结外部位。最高：5。

## 限制与适用人群

这是用于成人侵袭性非霍奇金淋巴瘤的经典预后指数，在历史上采用多柔比星治疗的队列中，于治疗前开发。应区分经典IPI、年龄调整IPI、R-IPI和NCCN-IPI。历史概率不能证明其对所有亚型或当前治疗均已校准。

## 参考文献

- [The International Non-Hodgkin's Lymphoma Prognostic Factors Project. A predictive model for aggressive non-Hodgkin's lymphoma. N Engl J Med, 1993.](https://doi.org/10.1056/NEJM199309303291402)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

低风险：5年生存率为73%

87% 完全缓解（利妥昔单抗前时代）。


### 2

高中间风险：5年生存率为43%

55% 完全缓解。


### 3

低中间风险：5年生存率为51%

67% 完全缓解。


### 4

高风险：5年生存率为26%

44% 完全缓解。

